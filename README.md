# Invalid argument(s): Cannot find executable for E:\software\Android\flutter_windows_1.22.2-stable\flutter\bin\cache\artifacts\engine\android-arm64-release\windows-x64\gen_snapshot."


The Android project depends on the flutter module. When I build the release package, I get a message that the file cannot be found.

![](https://imgkr2.cn-bj.ufileos.com/1d625e84-5409-4054-8031-a893f59a87de.png?UCloudPublicKey=TOKEN_8d8b72be-579a-4e83-bfd0-5f6ce1546f13&Signature=EYPgqWjgsoeYygx81gHfryFQvvg%253D&Expires=1603188678)


```
Studio Build: 4.1
Flutter: flutter_windows_1.22.2-stable
Version of Gradle Plugin: 4.1.0
Version of Gradle: gradle-6.5-all
OS: Windows 10
```

# Steps to Reproduce:

1. Download project from `https://github.com/zhaopingfu/FlutterReleaseCrash`.
2. Open project `flutter_crash_module`,  open terminal and exec command `flutter pub get`.
3. Open project `FlutterReleaseCrash`,  open terminal and exec command `./gradlew clean && ./gradlew assembleRelease --stacktrace`.