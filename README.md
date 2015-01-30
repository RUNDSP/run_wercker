# Wercker Box

The base is presently Ubuntu 12.04.

## Making Changes

- Edit wercker-box.yml.
- Increment version number on top of the file.
- Push
- Go to https://app.wercker.com/#applications/52a918bf3602dbd5590096e5 and
check if werker build passed
- Click on a build
- Click on deploy to => registry

Then, in portal etc., change the version number on top of
wercker.yml to the version number of the new wercker box.
