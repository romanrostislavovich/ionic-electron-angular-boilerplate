# ionic-electron-angular-boilerplate

## 

Required

- NodeJS: 20.18.3
- Java: 24
- Android studio

## Init

```bash
npm install
npm install ionic --global
ionic cap add android 
```

## Build

#### Windows 

```bash
npm run build:win32
```
Output on `dist` directory

#### Android
```
npm run build:android
```

- Open Android Studio. Build Variant set as release or debug
- Build → Build Bundle(s) / APK(s) → Build APK(s)
- File `.apk`, will be on: `android/app/build/outputs/apk/debug/app-debug.apk`

