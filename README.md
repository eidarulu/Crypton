# 📊 Crypton - Crypto Tracker App

This app allows users to track the top 100 cryptocurrencies with real-time prices and market trends. Users can see detailed insights such as market cap, price changes, and custom interactive graphs for visualizing price trends. The graphs were implemented using Compose Canvas. It also integrates Material 3's dynamic colors and supports light/dark modes and ensures a responsive design optimized for phones, tablets, and landscape mode. The app is styled with custom SVG icons.

This course focuses on building a Crypto Tracker Android App. It emphasizes practical Android development using Jetpack Compose, Material 3 Design, and modern libraries like Koin, Ktor, and Kotlinx Serialization. The app tracks the top 100 cryptocurrencies, displays their trends, and includes a responsive UI with custom graphs and animations.

---

 ## 🔧 Tech Stack

| **Component**           | **Details**                        |
|-------------------------|------------------------------------|
| **Language**            | Kotlin                             |
| **UI Framework**        | Jetpack Compose                    |
| **Dependency Injection**| Koin                               |
| **Networking**          | Ktor Client                        |
| **JSON Parsing**        | Kotlinx Serialization              |
| **Material Design**     | Material 3 (Dynamic Colors)        |

## 📁 Project Structure

```plaintext
Crypto Tracker
├── app
│   ├── ui                # Jetpack Compose UI components
│   ├── data              # Data sources and models
│   ├── model             # Data models for JSON parsing and app state management
│   ├── viewmodel         # State management with ViewModel
│   ├── utils             # Helper functions and utilities
│   └── network           # API client setup using Ktor
```

App Features:

Home Screen: Lists top 100 cryptocurrencies with live prices and trend indicators.
Detail Screen: Includes price trends, market cap, and 24-hour price change. Displays a custom graph of price changes with interactive features.
Responsive Design: Works on tablets, larger screens, and landscape mode with two-column layouts.
Dynamic Theming: Implements Material 3 Dynamic Colors based on the device's theme.

🖼 Features
Cryptocurrency List: Displays the top 100 cryptocurrencies with their current price and market trends (up or down).
Detail Screen: Shows detailed analytics for each cryptocurrency, including market cap, price, and price change over 24 hours.
Custom Graph: Visualize cryptocurrency price changes over a time period with a custom graph built using Jetpack Compose Canvas.
Responsive Design: Supports both tablets and phones, adapting layouts for landscape and larger screens.
Dynamic Theming: Implements Material 3's dynamic colors, adapting the app theme to the system's background color.
Support for Dark and Light Mode

Technologies:

Jetpack Compose for UI.
Material 3 components and theming.
Ktor Client for network requests to CoinCap API.
Kotlinx Serialization for JSON parsing.
Custom Canvas for drawing the graph.

🔧 Tech Stack
Language: Kotlin
UI Framework: Jetpack Compose
Dependency Injection: Koin
Networking and API handling: Ktor Client
JSON Parsing and data serialization: Kotlinx Serialization
Material Design: Material 3 with dynamic colors and theming

Dependency Injection with Koin.
Result handling using a generic wrapper class.
Pre-made assets and themes for faster development.

4. Course Tools & Resources
API: CoinCap API for crypto data.

Master modern Android app development practices.
Learn how to use Jetpack Compose for advanced UI components like custom graphs.
Explore the integration of dynamic theming with Material 3.
Understand and implement dependency injection using Koin.
Work with responsive designs for multiple screen sizes and orientations.
Practice error and result handling with a generic wrapper class.

📖 Documentation
Dynamic Theming
The app's theme dynamically adapts to the system's background using Material 3 guidelines.
For example:

Light Mode: Optimized contrast and readability.
Dark Mode: Eye-friendly colors for low-light conditions.
Utilities
Generic Result Wrapper: Efficient handling of success and error states.
Icon Mapping: Custom SVG icons mapped to cryptocurrency symbols.

🔗 API Integration
This app uses the CoinCap API for real-time cryptocurrency data.
Key Features of the API:

Public access (no authentication required).
Comprehensive cryptocurrency data.
