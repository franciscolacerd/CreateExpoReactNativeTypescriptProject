# Create Expo React Native Typescript Project
Who to create Expo React Native typescript Project

https://github.com/expo/examples/tree/master/with-typescript

https://docs.expo.dev/guides/typescript/

```powershell
# install expo CLI
npm i -g expo-cli

# install eas CLI
npm install -g eas-cli

# create project expo react-native typescript
npx create-expo-app -t

# go to project
cd App

# link to Expo Go
eas init --id 00000000-0000-0000-0000-000000000000

# run
npx expo

# run with clean cache
npx expo start -c

# run localhost with usb
npx expo start --localhost

# check dependencies
npx expo-doctor

# fix dependencies
 npx expo install --fix

# Or fix dependencies
npx expo install --check

# update expo go to latest version
npm install expo@latest

# generate preview apk 
eas build -p android --profile preview

# generate production apk
eas build -p android -e production

# deploy to google store
eas submit -p android --latest 

```
