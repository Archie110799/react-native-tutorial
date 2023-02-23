https://reactnative.dev/docs/environment-setup

# Install env

brew install node
brew install watchman

# Install

- Uninstall global react-native-cli @react-native-community/cli
  npm uninstall -g react-native-cli @react-native-community/cli
- Install base source
  npx react-native init BaseReduxApp --template react-native-template-typescript

# Install package

npm install redux react-redux redux-devtools-extension
npm install -g react-devtools
npm install react-i18next i18next --save
npm install axios
npm install react-native-gesture-handler react-native-reanimated react-native-reanimated-carousel react-native-maps --save
npm install moment
npm install react-native-date-picker
npm install @react-native-community/checkbox
npm install --save react-native-calendars
npm install @react-native-async-storage/async-storage
npm install react-native-modals

# Check device

xcrun simctl list
npx react-native run-ios --simulator="iPhone 13 Pro Max"

# Clear cache

npm cache clean --force

# Run app

- Start Metro
  npx react-native start
- Start your application
  npx react-native run-ios
  npx react-native run-android

# Open debugger (https://reactnative.dev/docs/debugging#accessing-the-in-app-developer-menu)

- run : react-devtools
- open 'rndebugger://set-debugger-loc?host=localhost&port=19001'

https://reactnative.dev/docs/environment-setup
