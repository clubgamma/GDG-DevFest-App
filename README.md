# CLUB GAMMA APP 

<p>
<img width="800px"  src="https://user-images.githubusercontent.com/57007680/109310623-c9a78e80-786a-11eb-8496-7985f0c6d17d.png">
</p>
<p>
<a target="_blank" href='http://bit.ly/2NGMzIc'><img alt='Get it on Google Play' src='https://goldtonemusicgroup.com/img/goldtone/main-page/news/playstore-badge.png' height='48px'/></a>

</p>
<p><a href="#getting-started">:rocket: Get Started</a></p>

## 📸 ScreenShots

|                                Dark Theme                            |                                Light Theme                           |                                   
| :------------------------------------------------------------------: | :-------------------------------------------------------------------:|
| <img src="https://i.imgur.com/A5nRqy6.jpg" width="350" height="685"> |<img src="https://i.imgur.com/FOVf5hN.jpg" width="350" height="685">  |
| <img src="https://i.imgur.com/WWTjQ65.jpg" width="350" height="685"> | <img src="https://i.imgur.com/dFaTNJE.jpg" width="350" height="685"> |
| <img src="https://i.imgur.com/ahjGYix.jpg" width="350" height="685"> | <img src="https://i.imgur.com/0VhpHzo.jpg" width="350" height="685"> |

### Show some :heart: and star the repo to support the project

## Overview

ClubGamma Mobile application is destination of all club related updates in your hand. You can see the upcoming events and it's agenda in the app as well as the speakers, photo library of previous events etc.

## Technology Stack

- Flutter
- Flutter Bloc

## Getting Started

1. [Fork repository](https://github.com/iampawan/GDG-DevFest-App/fork) and clone your fork locally
1. Install [Flutter 1.7.8](https://flutter.dev/docs/get-started/install)
1. Install [Android Studio / IntelliJ / VSCode](https://flutter.dev/docs/development/tools/android-studio)

## Building the project

### Missing Key.Properties file

If you try to build the project straight away, you'll get an error complaining that a `key.properties` file is missing and Exit code 1 from: /Club-Gamma-App-master/android/gradlew app:properties:. To resolve that,

1.  Open [Club-Gamma-App-master\android\app\build.gradle](https://github.com/clubgamma/Club-Gamma-App/blob/master/android/app/build.gradle) file and comment following lines-

    ```
    //keystoreProperties.load(new FileInputStream(keystorePropertiesFile))

    signingConfigs {
    // release {
    // keyAlias keystoreProperties['keyAlias']
    // keyPassword keystoreProperties['keyPassword']
    // storeFile file(keystoreProperties['storeFile'])
    // storePassword keystoreProperties['storePassword']
    // }
    }
    buildTypes {
    // release {
    // signingConfig signingConfigs.release
    // }
    }
    ```


## Contributing

Awesome! Contributions of all kinds are greatly appreciated. To help smoothen the process we have a few non-exhaustive guidelines to follow which should get you going in no time.

### Using GitHub Issues

- Feel free to use GitHub issues for questions, bug reports, and feature requests
- Use the search feature to check for an existing issue
- Include as much information as possible and provide any relevant resources (Eg. screenshots)
- For bug reports ensure you have a reproducible test case
  - A pull request with a breaking test would be super preferable here but isn't required

### Submitting a Pull Request

- Squash commits
- Lint your code with eslint (config provided)
- Include relevant test updates/additions

## Contributors

**Maintainer:** [Harsh Patel](https://github.com/harshptl14)

## License

Project is published under the [MIT license](/LICENSE.md).
This application is made using [Pawan kumar's](https://github.com/iampawan) GDG DevFest repo.

