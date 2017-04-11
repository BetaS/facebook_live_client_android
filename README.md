 # Facebook-Live client for Android

 An unofficial client for facebook-live video streaming
 
 ## Summary
 
 * Android NDK
 * OpenCV4Android
 * FFmpeg(which supports H/W Accelarate)
 
 ## Usage
 
 1. Change in 'app/CMakeLists.txt' 
    - set(pathOPENCV "OpenCV SDK Path")   
       - ex) set(pathOPENCV /User/sss989870/OpenCV-android-sdk)
    - set(pathPROJECT "Project Path")     
       - ex) set(pathPROJECT /Users/sss989870/facebook_live_client_android)
 1. Sync Project with gradle files        
    - Tools -> Android -> Sync Project with gradle files
 1. Run
