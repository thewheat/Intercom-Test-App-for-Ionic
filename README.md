# Sample Ionic App that integrates with Intercom

- Integrates with [Intercom](https://intercom.com) via [@ionic-native/intercom](https://ionicframework.com/docs/native/intercom/)

## How to use

- Download code
- Add any necessary platform
```
ionic cordova platform add android
ionic cordova platform add ios
```
- Add dependencies
```
ionic cordova plugin add cordova-plugin-intercom
npm install --save @ionic-native/intercom
```
- Configure `config.xml` ([install docs](https://developers.intercom.com/installing-intercom/docs/cordova-phonegap-installation#section-step-2-initialize-intercom))
- Run app
```
ionic cordova run ios
ionic cordova run android
ionic cordova emulate ios
ionic cordova emulate android

```

## Other details
- Base app / commit created via `ionic start MyIonicProject tutorial` detailed in the [Ionic Tutorial](https://ionicframework.com/docs/intro/tutorial/)
- If you want to use [intercom-cordova](https://github.com/intercom/intercom-cordova) check out the 
[master](https://github.com/thewheat/Intercom-Test-App-for-Ionic/tree/master) branch
