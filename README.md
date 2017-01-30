# cordova-plugin-raygun-native
iOS and Android native side integration of Raygun for cordova projects.

**AgriWebb fork updates version of SDKs**

## SETUP

to set your android api use the plugin variable when adding to your project
    cordova plugin add https://github.com/happieio/cordova-plugin-raygun-native.git --variable ANDROID_API_KEY="YOUR_API_KEY_HERE"
    
For iOS pass in your API via the JS Interface during/after the device ready callback
    RaygunNativePlugin.startNativeRaygun('user_email_address', 'YOUR_API_KEY_HERE');