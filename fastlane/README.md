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
## iOS
### ios update_certificates
```
fastlane ios update_certificates
```
Commit new certificates and provisioning profiles to Git if necessary. Only an itunesconnect admin can run this lane.
### ios bump_version
```
fastlane ios bump_version
```

### ios beta_ci
```
fastlane ios beta_ci
```


----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
