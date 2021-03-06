[![npm version](https://badge.fury.io/js/react-native-redux-boilerplate.svg)](https://badge.fury.io/js/react-native-redux-boilerplate)

# react-native-redux-boilerplate
This package provides a command line utility that starts the file configuration to begin with your react-native and redux application.


## Getting Started

These instructions would get you an up and running react-native app with redux in Mac OS for iOS.

If you want to run react native in a different operating system or in Android please follow
the instructions in the [React Native Website](https://facebook.github.io/react-native/docs/getting-started.html).

NOTE: This package would still work for development and deployment platforms different from Mac and iOS but the
necessary configurations need to be set up, as mentioned above.

### Prerequisites (Mac and iOS)
The  Prerequisites for this project are:

  * Homebrew
  * Node (npm)
  * Xcode (not necessary for the package itself, but it is necessary to run react native)

To install Xcode in mac:

Xcode can be obtained from the app store.

To install Homebrew in mac:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

To install Node in mac:

```
brew install node
```

### Installing

In order to install react-native-redux-boilerplate use npm

```
npm install -g react-native-redux-boilerplate
```

To create a react-native project with redux in it boilerplate, move to the desired directory and run the command below
and follow the prompt.

```
react-native-redux-boilerplate-install
```
### Running

After running the command line utility and the basic folder structure has been created you can run your app as
a regular react native app.

Step into your project folder:

```
cd [Project Name]
```

And then run your app:

For iOS:

```
react-native run-ios
```

For Android (follow the [website](https://facebook.github.io/react-native/docs/getting-started.html) for proper configuration):

```
react-native run-android
```

Enjoy!!!

## Built With

* [React Native](https://facebook.github.io/react-native/) - The mobile framework used
* [Npm](https://www.npmjs.com/) - Dependency Management

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/mgarciacruzz/react-native-redux-boilerplate/tags).

## Authors

* **Manuel Garcia** - *Initial work* - [Mgarciacruzz](https://github.com/mgarciacruzz)

See also the list of [contributors](https://github.com/mgarciacruzz/react-native-redux-boilerplate/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
