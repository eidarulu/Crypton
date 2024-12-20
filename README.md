# 📊 Crypton - Crypto Tracker App

This app allows users to track the top 100 cryptocurrencies with real-time prices and market trends (up or down). Users can see detailed insights such as market cap, price changes, and custom interactive graphs for visualizing price trends. The graphs were implemented using Compose Canvas. It also integrates Material 3's dynamic colors and supports light/dark modes and ensures a responsive design optimized for phones, tablets, and landscape mode. The app is styled with custom SVG icons.

 Jetpack Compose, Material 3 Design, and modern libraries like Koin, Ktor, and Kotlinx Serialization.

 ## Preview

 ## 🔧 Tech Stack

| **Component**                           | **Details**                        |
|-----------------------------------------|------------------------------------|
| **Language**                            | Kotlin                             |
| **UI Framework**                        | Jetpack Compose                    |
| **Dependency Injection**                | Koin                               |
| **Networking and API handling**         | Ktor Client                        |
| **JSON Parsing and data serialization** | Kotlinx Serialization              |
| **Material Design**                     | Material 3 (Dynamic Colors)        |

Note: Ktor Client for network requests to CoinCap API.
parsed JSON responses from API using kotlin-axe serialization.

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

Utilities
- Generic Result Wrapper: Efficient handling of success and error states.
- Icon Mapping: Custom SVG icons mapped to cryptocurrency symbols.
- API: [CoinCap API](https://docs.coincap.io/) for real-time cryptocurrency data.
