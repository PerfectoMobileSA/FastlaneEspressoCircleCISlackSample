# Fastlane + Espresso + Perfecto + slack:
[![CircleCI](https://circleci.com/gh/PerfectoMobileSA/FastlaneEspressoCircleCISlackSample/tree/master.svg?style=svg)](https://circleci.com/gh/PerfectoMobileSA/FastlaneEspressoCircleCISlackSample/tree/master)


This project showcases usage of perfecto fastlane plugin.

The following fastlane actions are possible with the sample project:

## Available Actions:
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

Refer to .circleci/config.yml for steps to setup and execute this project.

### Note: 
Pass the below values as environment variables <br>
PERFECTO_CLOUDURL  [your perfecto cloud url. E.g.: demo.perfectomobile.com]<br>
PERFECTO_TOKEN [your perfecto [`security token`](https://developers.perfectomobile.com/display/PD/Generate+security+tokens)]<br>
PERFECTO_MEDIA_LOCATION	[mention the Perfecto media repository location to upload the file mentioned in file_path. E.g. PUBLIC:Samples/sample.ipa]<br>
file_path [location of your preferred ipa/apk file which needs to be uploaded to perfecto media repository.]<br>
slack_webhook [Slack incoming webhook for slack integration. more info: [`here`](https://docs.fastlane.tools/actions/slack/)]<br>