# Project2
ST10441904
Ratshilingana Mpho


I started my journey by creating a new React Native project called *MastPOE* using the command:  
`npx react-native init MastPOE`  

During the setup, I received a warning that the `init` command was deprecated and was advised to use:  
`npx @react-native-community/cli init`  

After the project was initialized, I encountered issues while attempting to run it on Android with:  
`npx react-native run-android`  

The process failed, indicating that the Android project structure was missing. This required me to reinitialize the project correctly. Once resolved, I began setting up navigation by installing the necessary packages:  

- Core Navigation: `npm install @react-navigation/native`  
- Stack Navigation: `npm install @react-navigation/stack`  
- Additional Dependencies:  
  ```
  npm install react-native-gesture-handler react-native-reanimated 
  react-native-screens react-native-safe-area-context @react-native-community/masked-view
  ```  

After installing these packages, I created a basic navigation structure in the `App.tsx` file. I implemented a stack navigator that included screens like *Home*, *Courses*, *Starters*, *Main*, *Dessert*, *Available Now*, and *Chef Description*. The navigator was wrapped in a `NavigationContainer`, and the initial route was set.  

Challenges Encountered  

1. Port Conflict: Port 8081 was in use, requiring me to switch to port 8082.  
2. ADB Issues: The Android Debug Bridge (ADB) was not recognized on my system, likely due to an Android SDK misconfiguration.  
3. Emulator Setup: No Android emulators were detected, possibly due to a lack of virtual devices or incorrect setup.  
4. Build Errors: The build process failed due to missing plugins and access issues in the `settings.gradle` file.  
5. Deprecated Packages: Running `npm install` completed successfully but highlighted warnings about outdated packages.  

Solutions and Next Steps  

To resolve these challenges, I plan to:  

- Verify the emulator configuration and ensure ADB is properly set up.  
- Investigate and fix errors in the `settings.gradle` file.  
- Use `GestureHandlerRootView` to wrap the app for better gesture handling.  

Despite these technical hurdles, I made good progress in setting up the project and implementing navigation. My next goal is to address the Android environment issues and successfully launch the application.  


https://youtube.com/shorts/tOLx1p_3qs0 
