#### bitrise
created with some specific needs, not general
story:
- optimized git clone only fetch last 1 commit
- cache the pod installation
- only build, no test runner included
- use specific xcode version
- update app version through plist
- upload to testflight using ipa file location
- use specific cocoapods version
- have a trigger map on merge-request to developmetn and on push to release branch