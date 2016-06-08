# cordova_tuts
#Taken from
https://www.toptal.com/mobile/developing-mobile-applications-with-apache-cordova
##And also:
https://cordova.apache.org/docs/en/latest/guide/cli/
#Steps
* cordova create app_name com.path.subpath HelloApp
* cordova platform add android --save
##Add minimum plugins
* cordova plugin add org.apache.cordova.console
* cordova plugin add org.apache.cordova.dialogs
* cordova plugin add org.apache.cordova.splashscreen
* cordova plugin add org.apache.cordova.statusbar
##Build solution
* cordova build
* cordova emulate android
* cordova run android
* Install jquery-mobile using: npm install jquery-mobile
#Helpful commands
##See devices list
* adb devices
##Debug in chrome
* chrome://inspect/
##Add Sqlite plugin:
* cordova plugin add https://github.com/litehelpers/Cordova-sqlite-storage.git
##Install dialog plugin
cordova plugin add cordova-plugin-dialogs
##Install console plugin
cordova plugin add cordova-plugin-console
