# apkinfo

Simple tool to print an APK's package, version, and signing certificate info

Requirements :
- Bash
- ANDROID_HOME environment variable pointing to the Android SDK with build tools installed
- jarsigner
- unzip

Usage :

    ./apkinfo </path/to/apk.apk>
    
Example :
 
    $ ./apkinfo ~/dev/appium/build/selendroid/selendroid.apk
    Checking /home/light/dev/appium/build/selendroid/selendroid.apk
    Package name : io.selendroid.server
    Version name : 0.17.0
    Version code : 1
    Signing certificate SHA1 fingerprint : EA:1F:6D:89:A1:81:8E:9D:81:48:C2:95:85:C3:34:E0:49:44:14:6A
