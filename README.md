# FaceDetection
A face detection app that can analyze images using the Firebase ML kit. The app can detect smiley faces 😊from non-smiley faces 😠and return the probability that a face is smiling or not. 0.9 > means a face is smiling and ~0.00 means face is not smiling.

### Setup development environment

* [Android Studio](http://developer.android.com/intl/es/sdk/index.html)

* [Android SDK Tools](http://developer.android.com/intl/es/sdk/index.html#Other)

* [Android NDK](http://developer.android.com/intl/es/ndk/downloads/index.html)

### Build & Run the application

* Get the source code

```
git clone https://github.com/mmohamedali/FaceDetection
```

* Configure the variable `NDK_ROOT` to point to your Android NDK installation path at `jni/build.sh`.

* Open the project with Android Studio, let it build the project and hit _*Run*_
