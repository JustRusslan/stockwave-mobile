# Stockwave 📈🌊  
*Real-time stock-market companion built with Flutter*

Stockwave helps you follow the market **at a glance**: lightning-fast charts, smart trend alerts and a personal watchlist – right in your pocket.

---

## ✨ Key Features
- **Real-time quotes** with local caching to minimise API calls  
- **Interactive charts** (line, candlestick, volume)  
- **Watchlist & portfolio** – add, remove and reorder tickers; holdings value auto-updates  
- **Trend alerts** – configurable percentage / absolute movement with push notifications  
- **Dark & light themes** that follow your system setting  
- **Offline mode** – see the last cached data even without an Internet connection  
- **Built with Flutter 3** – runs natively on Android & iOS

---

## 🚀 Getting Started

### Prerequisites

| Tool | Minimum version | Notes |
|------|-----------------|-------|
| Flutter SDK | 3.22 | `flutter doctor` should pass on your OS |
| Dart | 3.3 | Comes with the Flutter SDK |
| Android Studio / Xcode | latest | For emulators & native builds |
| Market-data API key | — | e.g. MarketStack, Finnhub, TwelveData |

### Clone & run

```bash
git clone https://github.com/<your-username>/stockwave-mobile.git
cd stockwave-mobile
flutter pub get
flutter run          # launches on connected device / emulator
