# learn-cordova
learn-cordova

# 1、安装Android SDK
SDK是编译安卓程序的必备工具，需提前安装好。

# 2、创建Cordova工程
cordova create .
cordova platform add android
"start": "cordova build android"
npm start

# 手机安装失败
1、安卓版本不兼容
查看编译的安卓版本：cordova platform ls
## cordova platform ls
Installed platforms:
  android 8.1.0
Available platforms:
  browser ^6.0.0
  electron ^1.0.0
  ios ^5.0.0
  osx ^5.0.0
  windows ^7.0.0
对应的：
  "dependencies": {
        "cordova-android": "^8.1.0"
    },

查看安卓的具体信息：npm view cordova-android

查看cordova的安卓版本：https://registry.npmjs.org/cordova-android/
