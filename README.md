# Mystery Rider React Native Dev Setup

- The steps below are based on the instructions provided in the official React Native docs. For the most accurate and up to date setup isntructions please view the React Native Docs

<a href="https://reactnative.dev/docs/environment-setup?guide=native&os=windows&platform=android" target="_blank">React Native Setup - Android Emulator with Windows</a>
<br/>
<a href="https://reactnative.dev/docs/environment-setup?guide=native&os=macos&platform=ios" target="_blank">React Native Setup - iOS Emulator with Mac</a>

## Android Studio Emulation setup
- After installing Android Studio and installing all the required packages from the docs, make sure to add a Android Virtual device
- The android virtual device is the emulator for the specified android device selected during creating
- After the AVD has been created, in a terminal run the command `npm start` in the root of the project. This will startup the Metro development server, which will also listen for changes made to the code
- After running `npm start`, run the command `npm run android` or `npm run ios` in a <b>separate</b> terminal in project root. This command will connect the React Native code to the Virtual Device created in the Emulator and the React Native app should soon be visible on the emulator screen. Any changes made to the code should then also be reflected on the emulator
