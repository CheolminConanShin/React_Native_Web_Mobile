# Install
npm install

# Run
npm run webServer => runs web application
npm run mobilePackager => runs packager for mobile application
npm run iosApp => run iOS simulator and runs app
npm run androidApp => run app in running android emulator
npm run emulator => run emulator but target has to be set in package.json

# Reset project name
npm install -g react-native-cli
change name property in package.json
empty ios and android folders
run react-native upgrade
change the register component name inside index.android.js and index.ios.js
