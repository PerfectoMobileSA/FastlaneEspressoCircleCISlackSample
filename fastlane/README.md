fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## Android
### android test
```
fastlane android test
```
build, upload and run on perfecto
### android apk
```
fastlane android apk
```
Build debug APK and upload to perfecto
### android test_apk
```
fastlane android test_apk
```
Build debug test APK and upload to perfecto
### android run_perfecto
```
fastlane android run_perfecto
```
Run on perfecto
### android slack_report
```
fastlane android slack_report
```
Report perfecto url to slack

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
