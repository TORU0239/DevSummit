# 5 features in Android studio 


## A. Network Request Interceptor (Improvement)

- Android Studio Flamingo canary 
- based on fully customazable rule set that I define.
- demo: intercepting request for a screen in Now In Android app.
- filling hostname, path, status code
- replace response codes, headers, and full contents text
- This is a highly recommended feature and we can see how apps behave.

## B. Downloads Impact

- EE beta, a new metric
- when we need to optimize gradle scripts themselves
- shows what part of our build is spent o n downloading dependencies
- helps us notice when artifacts are downloaded needlessly on every build,
  most likely indicating deeper problems with our setup, e.g. using Dynamic dependency versions of snapshots

## C. Android SDK Version update

- Android SDK Version update assistant
- link the code to the document and sdk
- ensuring that users always get the best quality and secutiry privacy in their apps
- Based on built-in rules, detect when we need to update target sdk version in our build
- guide us through the required changes in the Android Studio
- means the IDE shows required information in a separate panel, causing no contect switch between the browser, documentation and our code
- In the future, this feature will detect the code pattern and help us match the platform's behaviors and new APIs.
- Under heavy development

## D. Physical device mirroring 

- Device manager (a new feature) - configuring both the virtual and physical devices for running apps
 - Pairing device (Wear OS too) over wifi
 - Physical device screening mirroring has been added
 - You can stream the UI to the IDE window and interact with it
 - drag and drop APKs onto the device to install them, even use keyboard in the emulator for text input
 - EE, experimental feature
 
## E. Emulator bluetooth support

- can run multiple emulator instances to create arbitrary connections
 - can see seamless changes in the 2 emulators in the demo, just like real devices
 - More use cases will be added to this feature