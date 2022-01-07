# jitsi-maven-repository (v3.6.0)

## Source information

- project: [jitsi-meet](https://github.com/moirognwmonio/jitsi-meet), branch: [sdk-3.6.0-mod](https://github.com/moirognwmonio/jitsi-meet/tree/sdk-3.6.0-mod)

## Changelog

- Customize waiting dialog
- Modified Podfile, in jitsi-meet project, to prevent application crash
- Hide more options button and it's contents
- Build for apps using react-native v0.64.2
- Disable delta updates to prevent crashes in android build
- Package changes from official tag 'android-sdk-3.6.0':

```shell
"react-native": "0.64.2",
"@react-native-community/netinfo": "5.0.0",
"hermes-engine": "0.7.2", // Currently not using hermes in our project
```
- If you use hermes, you should have installed the same version in your project.
- Check your node-modules before you proceed.

## Build

Artifacts for android app, by building custom [jitsi-meet](https://github.com/moirognwmonio/jitsi-meet) using the following command on the jitsi-meet repo:

```shell
npm run build-android
```

This project is used by custom [react-native-jitsi-meet](https://github.com/moirognwmonio/react-native-jitsi-meet).
