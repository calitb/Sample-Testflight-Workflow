![Deploy Staging](https://github.com/calitb/SimpleTest/workflows/Deploy%20Staging/badge.svg)

![Deploy Release](https://github.com/calitb/SimpleTest/workflows/Deploy%20Release/badge.svg)

# GitHub Workflows for iOS Apps

### GitHub Secrets

This project uses GitHub Workflows to run Fastlane scripts to build and upload binaries to TestFlight/AppStore.

For this to work the following Github Secrets need to be defined:

`APPLE_USERNAME`: The username for your Apple account

`APP_APPLE_ID`: The apple_id for your application.

`FASTLANE_APPLE_APPLICATION_SPECIFIC_PASSWORD`: A `application specific password` for your apple account.

`GIT_CERT_HTTPS_URL`: The https url for a repository to store the provisioning profiles and distribution certificates generated by Fastlane.

KEYSTORE_PASSPHRASE: The passphrase to decrypt the provisioning profiles and distribution certificates generated by Fastlane. 

### Actions

`Deploy Staging`: It is run every time a push to master is done.

`Deploy Release`: It is run every time a new Release is created in GitHub for your repository.