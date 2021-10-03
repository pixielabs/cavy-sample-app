# Cavy Directory: React Native & Cavy Sample App

Base code borrowed from [Christophe
Coenraets](https://github.com/ccoenraets/employee-directory-react-native).

## How to run the app

 - Make sure your environment is set up to build React Native applications.
   See the React Native documentation for info on how to do this.
 - Install dependencies with `yarn`.
 - If you want to run on iOS, install Cocoapods dependencies:

     ```
     cd ios
     pod install
     ```
 - Run the app with `npx react-native run-ios` or `npx react-native
   run-android`.

## How to run the tests

You will need Cavy CLI to run the tests:

`yarn global add cavy-cli`

Then run the tests with `cavy-run ios` or `cavy-run android`.

Here's what it should look like when the tests run:

![](https://user-images.githubusercontent.com/126989/46582861-98358a80-ca45-11e8-989e-be33742651b1.gif)
