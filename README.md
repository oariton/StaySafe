# Welcome to Stay Safe project!

This is the repository for Stay Safe project

## Get the code

```
git clone https://github.com/oariton/StaySafe.git
```
To pull all the 3 repositories run :

```
git submodule update --init --recursive
```

## The mobile application build (apk) to be installed on any android device

Browse the **stay_safe_apk** folder and download the android build

## The mobile application source code

Browse the **stay_safe_mobile** and find the mobile application source  code.

To run the mobile application locally just use :

> npx react-native run-android

To build the production apk run :

> cd android & gradlew assembleRelease & cd ..

## The back-end (server) source code

Browse the **stay_safe_server** and find the mobile application source  code.

To run the application locally use:

> gradlew

To deploy the application on the **heroku**  account run:

> jhipster heroku
