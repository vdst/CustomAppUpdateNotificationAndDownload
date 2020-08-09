To create a new version:
- change the "latestVersion": "x.x.x" AND "latestVersionCode": x.x.x in the update-changelog.json file
- change the versionName "x.x.x" in the build.gradle (Module: app) AND version = 'x.x.x' in the build.gradle (Module: Android-Project-...)
- create a new release with the TAG x.x.x and add the .apk to the binaries of the release
