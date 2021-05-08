FROM cirrusci/android-sdk:tools-windowsservercore-2019

ENV ANDROID_PLATFORM_VERSION 30
ENV ANDROID_BUILD_TOOLS_VERSION 30.4.5

RUN sdkmanager.bat \
    platforms;android-%ANDROID_PLATFORM_VERSION% \
    build-tools;%ANDROID_BUILD_TOOLS_VERSION%
