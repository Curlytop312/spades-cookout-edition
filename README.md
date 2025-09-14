# Spades Cookout Edition# Playing Cards iOS Assets



A React Native mobile game implementation of the classic Spades card game.Courtesy of https://code.google.com/p/vector-playing-cards/ (public domain)



## FeaturesWith some additional processing to remove borders of cards.



- Modern React Native implementationBuild the png assets with four parallel processes:

- High-quality playing card assets

- Cross-platform (iOS & Android)```

make -j 4 png

## Getting Started```



### Prerequisites# Tools



- Node.js (v14 or later)[xmlstartlet](http://xmlstar.sourceforge.net/) to remove the border path from svg.

- React Native CLI

- iOS: Xcode and iOS Simulator[svg2png](https://github.com/domenic/svg2png) to convert svg to png (based on phantomjs)

- Android: Android Studio and Android SDK

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Curlytop312/spades-cookout-edition.git
   cd spades-cookout-edition
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run on iOS:
   ```bash
   npx react-native run-ios
   ```

4. Run on Android:
   ```bash
   npx react-native run-android
   ```

## Assets

Card assets are located in the `assets/` directory. See [assets/README.md](assets/README.md) for more information about the playing card graphics.

## License

This project uses public domain playing card graphics courtesy of https://code.google.com/p/vector-playing-cards/.