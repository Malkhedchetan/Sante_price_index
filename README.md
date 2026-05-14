
# Sante Price Index 🛒📈

Sante Price Index is a comprehensive intelligence tool designed for fresh-market vendors and retailers to make data-driven decisions. It provides live mandi prices, profit calculations, inventory management, and an integrated AI assistant to optimize daily business operations.

## 🚀 Key Features

*   **Live Mandi Prices**: Real-time tracking of commodity prices across various mandis.
*   **Sante AI Agent**: An intelligent assistant that understands multi-language queries (English, Hindi, Kannada, etc.) and provides instant price lookups (e.g., "erulli yestu").
*   **Profit Optimizer**: Calculate landed costs, transport expenses, and wastage to find the best market for your produce.
*   **Digital Price Board**: A professional customer-facing display for your daily prices.
*   **Inventory Management**: Track stock levels, buying prices, and estimated profit margins.
*   **Smart Alerts**: Instant notifications on significant price jumps or drops.
*   **Market Trends**: 7-day price movement visualization to predict future market behavior.

## 📱 Screenshots

<p align="center">
  <img src="screenshots/login.png" width="200" alt="Login">
  <img src="screenshots/profile.png" width="200" alt="Profile">
  <img src="screenshots/price_watch.png" width="200" alt="price_watch">
  <img src="screenshots/home.png" width="200" alt="Home Screen">
  <img src="screenshots/price_trends.png" width="200" alt="Price trends Screen">
  <img src="screenshots/best_market.png" width="200" alt="Best Market Screen">
  <img src="screenshots/smart_alerts.png" width="200" alt="Smart Alert Screen">
  <img src="screenshots/Ai_chat_bot.png" width="200" alt="AI Agent">
  <img src="screenshots/profit_calculator.png" width="200" alt="Profit Calculator">
  <img src="screenshots/price_watch.png" width="200" alt="Live Price Screen">
</p>


## 🛠 Tech Stack

*   **Language**: Kotlin
*   **UI Framework**: Jetpack Compose (Modern Declarative UI)
*   **Architecture**: MVVM (Model-View-ViewModel)
*   **Authentication**: Firebase Auth (including Google Sign-In)
*   **Database**: Firebase Realtime Database
*   **AI Engine**: Custom Local Intelligence (Multi-language support)
*   **Navigation**: Jetpack Compose Navigation
*   **Local Storage**: DataStore Preferences

## 📦 Setup & Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Hemanthkumar25s/Sante_Price_index.git
    ```
2.  **Firebase Configuration**:
    *   Add your `google-services.json` to the `app/` directory.
    *   Enable Email/Password and Google Sign-In in the Firebase Console.
3.  **Google Sign-In**:
    *   Update the `default_web_client_id` in `res/values/strings.xml` with your Web Client ID from the Firebase Console.
4.  **Build and Run**:
    *   Open the project in Android Studio.
    *   Sync Gradle and run the `:app` module.

## 🤝 Contribution

Contributions are welcome! Please feel free to submit a Pull Request.

---
*Developed for efficient and smart vegetable trading.*
=======

# Sante Price Index 🛒📈

**Sante Price Index** is a smart market intelligence application designed for vegetable vendors, retailers, and fresh-market traders to make data-driven business decisions.

The app provides live mandi prices, profit analysis, inventory tracking, smart alerts, and AI-powered assistance to improve daily trading operations.

---

# 🚀 Features

## 📊 Live Mandi Prices

Track real-time vegetable and commodity prices across multiple mandis.

## 🤖 Sante AI Assistant

Multi-language AI support for instant price queries.

Examples:

* “Onion price”
* “erulli yestu”
* “tamatar rate”

Supported Languages:

* English
* Hindi
* Kannada
* Tamil
* Telugu

---

## 💰 Profit Optimizer

Calculate:

* transport cost
* wastage
* landed cost
* selling margin
* estimated profit

to identify the best market opportunities.

---

## 🪧 Digital Price Board

Professional customer-facing digital display for daily vegetable prices.

---

## 📦 Inventory Management

Manage:

* stock quantity
* buying price
* selling price
* expected profit

---

## 🔔 Smart Alerts

Get notified when market prices:

* rise sharply 📈
* drop suddenly 📉

---

## 📈 Market Trends

Visualize 7-day price trends and market movement analysis.

---

# 📱 Screens Included

* Login Screen
* Dashboard
* Live Price Screen
* Market Trends
* Profit Calculator
* AI Assistant
* Inventory Manager
* Smart Alerts
* Digital Price Board
* Profile & Settings

---

# 🛠 Tech Stack

| Technology                 | Usage             |
| -------------------------- | ----------------- |
| Kotlin                     | Main Language     |
| Jetpack Compose            | Modern Android UI |
| MVVM Architecture          | App Structure     |
| Firebase Auth              | Authentication    |
| Firebase Realtime Database | Cloud Database    |
| Firebase Google Sign-In    | Login             |
| DataStore Preferences      | Local Storage     |
| Compose Navigation         | Navigation        |
| Material 3                 | UI Design         |

---

# 📂 Project Architecture

```text
MVVM Architecture

UI Layer
│
├── ViewModel Layer
│
├── Repository Layer
│
├── Firebase Realtime Database
│
└── Local DataStore
```

---

# ⚙️ Setup & Installation

## 1. Firebase Setup

Add:

```text
google-services.json
```

inside:

```text
app/
```

---

## 2. Enable Firebase Services

Enable in Firebase Console:

* Email/Password Authentication
* Google Sign-In
* Realtime Database

---

## 3. Add SHA Fingerprint

Run:

```bash
gradlew signingReport
```

Add SHA-1 fingerprint in Firebase Project Settings.

---

## 4. Sync Project

Open project in Android Studio and click:

```text
Sync Gradle
```

---

## 5. Run Application

Run:

```text
:app
```

on:

* Emulator
* Physical Android Device

---

# 🎯 Future Enhancements

* AI Price Prediction
* Voice Assistant
* Offline Market Sync
* Farmer Marketplace
* Cloud Analytics Dashboard
* Multi-user Vendor System

---

# 🤝 Contribution

Contributions are welcome!

Feel free to:

* fork the repository
* create new features
* improve UI/UX
* optimize performance

# 👨‍💻 Developed By

**Chetan Malkhed**

Smart solutions for efficient vegetable trading 🚜📊
