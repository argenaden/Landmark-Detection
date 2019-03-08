# Landmark-Detection
Landmark detection using Dlib in android studio

1) Opencv 3.4.2
2) NDK r17c
3) you need clone dlib-android from here git clone --recursive https://github.com/tzutalin/dlib-android.git
4) Change in Android.mk OPENCV_PATH = /your opencv sdk/sdk/native/jni   and Application.mk = APP_PLATFORM := android-28
5) go to /dlib-android/   and run here with with your ndk path + ndk-build.cmd -j 4
6)
