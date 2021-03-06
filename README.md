# Blur - A Launcher Replacement

![Promo](https://raw.githubusercontent.com/klinker24/Android-Blur-Launcher/master/promo/images/Feature%20Graphic.png)

This is Blur Launcher, Klinker Apps one stop shop for the most powerful launcher around.

NOTE: This repo does not contain the latest play store version. It will house the 2.0+ releases, which will be based off of Google's latest [Launcher3](https://github.com/klinker24/launcher3/) code. This version will be much more maintainable for the future and will be able to easily incorporate the latest upstream code.


## Features

As the apps feature-set continues to be merged into this new fork, I will continue to add to this repository.

- Support for Blur Pages and Card
- Built from Marshmallow's Launcher3 code, with the latest improvements and Material Design in mind
- Blur puts app predictions at the top of the app drawer
- quick scroll through the app drawer
- hidden apps (still show up when searching in the all apps drawer though, by design)
- revamped settings menu
- gesture support
- configure homescreen and all apps grid
- configure workspace padding
- change the number of dock icons
- select icon scale
- dock is optional
- page indicators are optional
- search bar is optional
- icon names on the homescreen are optional
- Blur can turn off your screen
- backup and restore app settings
- Persister service to try to ensure that the app stays in memory (no statistics as to whether or not this works though...)

## Compiling

The project is built with gradle, so maintenence and compilation is very straightforward. 

```
$ ./gradlew assembleDebug
```

## Contributing

Please fork this repository and contribute back using [pull requests](https://github.com/klinker24/Android-Blur-Launcher/pulls). Features can be requested using [issues](https://github.com/klinker24/Android-Blur-Launcher/issues). All code, comments, and critiques are greatly appreciated.

## Changelog

The full changelog for the app can be found [here](https://raw.githubusercontent.com/klinker24/Android-Blur-Launcher/master/app/src/main/res/xml/changelog.xml).


---

## License

```
Copyright 2015 Luke Klinker

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
