 # Dcar-Wallet-App #
这款App主要使用NativeScript-Vue技术搭建项目


## 初始化NativeScript项目
### 2018-08-06
**搭建环境**
```sh
  安装 nodejs
  安装 jdk8
  安装 android studio
  安装 NativeScript
  cmd > tns doctor，检查环境，如果没有报错则环境搭建好了
```
**运行项目**
```sh
  npm install //安装依赖
  tns run android //运行项目
```

## 初始化NativeScript-Vue项目
### 2018-08-07
**新建项目**
```sh
  vue init nativescript-vue/vue-cli-template <project-name>
  cd <project-name>
  npm install
  npm run watch:android
```
### 2018-08-08
**真机运行（此处为安卓机，还没有使用苹果机）**
```sh
  电脑连接手机，手机打开开发者模式，usb调试
  npm run watch:android
```
**模拟器运行**
```sh
  安装配置 Android Studio
```
**打包**
```sh
  使用 Android Studiod打包c成apk文件
```
**修改调试**
```sh
  npm run watch:android
```
