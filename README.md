# SimpleSpyware - Black HatEurope 2019 - Demo App 

This repo contains a demonstration spyware app. The app shows how Androids foreground services can be used to collect user data. More technical information can be found within the presentation slides and the whitepaper.

* [Code](https://github.com/7homasSutter/SimpleSpyware/releases)
* [Whitepaper](https://github.com/7homasSutter/SimpleSpyware/releases)
* [Presentation](https://github.com/7homasSutter/SimpleSpyware/releases)

### APK
The latest prebuilt apk can be downloaded from the releases page:
* [APKs](https://github.com/7homasSutter/SimpleSpyware/releases)


### Build
The ExampleA folder contains a Android Studio 3.2 project. The project can be imported in Android Studio or directly build with gradle:

```
./gradlew build
```

You can install and debug via Android Studio or over adb with:
```
adb install ch.zhaw.init.orwell_a
```
### Some Notes
Please do not use or redistribute parts of this code for criminal activity. Spying on others is a crime! This code is only intended for educational purposes and should only be used on your own devices for testing.

Some notes about the features:
- Timings: Executation may change with your phones state.
- Cam: The gallery deletes all the photos after 100 images.
- Location: Remember that GPS data drains a lot of battery power.
- Micrphone: Remeber that only one application can use the microphone. So you can't record phone calls.


### Attributions 
App Material Icons: Attribution: Google Inc. - [Licencse](https://creativecommons.org/licenses/by/4.0/deed.en)
