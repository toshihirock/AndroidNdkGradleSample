AndroidNdkGradleSample
======================

Using custom Andorid.mk with Gradle

## Setup

+ Install AndroidSDK and AndoridNDK
+ Set your `ANDROID_HOME` environment variable
+ Clone this sample project form GitHub

  ```bash
  git clone https://github.com/toshihirock/AndroidNdkGradleSample.git
  ```

+ Modify  `ndkHome` property

  ```bash
  cd AndoridNdkGradleSample
  vi build.grale
  ```

## Build with gradle

Run build(involve `ndk-build`)

  ```bash
  ./gradlew assembleDebug
  ```
Of cource you can run `clean`(involve `ndk-build clean`)

  ```bash
  ./gradlew clean
  ```
## Detail
