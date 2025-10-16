<p align="center"># Vocabulary Flash</p>

![](https://img.shields.io/badge/Kotlin-Multiplatform-blue)
![](https://img.shields.io/badge/Compose-Multiplatform-green)
![](https://img.shields.io/badge/Architecture-Clean-orange)


## How to run

#### Android
To run the application on android device/emulator:  
 - open project in Android Studio and run imported android run configuration  

To build the application bundle:  
 - run `./gradlew :androidApp:assembleDebug`  
 - find `.apk` file in `androidApp/build/outputs/apk/debug/androidApp-debug.apk`  

#### Desktop
Run the desktop application: `./gradlew :desktopApp:run`  
Run the desktop **hot reload** application: `./gradlew :desktopApp:hotRun --auto`  

#### iOS
To run the application on iPhone device/simulator:  
 - Open `iosApp/iosApp.xcproject` in Xcode and run standard configuration  
 - Or use [Kotlin Multiplatform Mobile plugin](https://plugins.jetbrains.com/plugin/14936-kotlin-multiplatform-mobile) for Android Studio  

## Find this repository useful? ❤️

Support it by joining [stargazers](https://github.com/XDdevv/vocabulary-srs-kmp-clean/stargazers) for this repository. ⭐
Also, [follow me](https://github.com/XDdevv/) on GitHub for my next creations! 🤩

## License
```
Designed and developed by 2025 rainxchzed (Usmon Narzullaev)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```