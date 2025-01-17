## Raccoon - PC APK Downloader

Raccoon is an APK downloader for fetching apps from Google Play.

- Cross platform (Linux, Windows, Mac OS)
- Avoids the privacy issues that arise from connecting your Android device
  with a Google account
- Easily install apps on multiple devices without downloading them several
  times.

## Quokka Edits

We've forked this repo and will make edits for our use-case as needed.

Changes made:

- Using `--gpa-details` from the CLI will produce output in JSON rather than a `.toString()` of the protobuf message.

## Building

Raccoon is build with gradle. It is recommended to use the "launch4j" task
instead of the standard one. Version can be changed via 'gradle.properties' file.

#### How to build on Linux/MacOS/Windows (git bash/powershell terminal):

./gradlew createExe

#### How to build on Windows (cmd.exe terminal):

gradlew createExe

Prebuild binaries are available at

https://raccoon.onyxbits.de
