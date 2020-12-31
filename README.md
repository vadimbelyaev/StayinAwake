# StayinAwake
A simple app for iOS developers that will keep your device's screen awake while Xcode is building your app so you don't have to unlock your device when the build is finished.

## How to install
This app is not on the App Store, so you need to build and install it on your device yourself.
1. Clone this repository.
1. Open the project in Xcode.
1. Go to project settings and choose your own deveploment team for code signing.
1. Connect your device.
1. Build and run StayinAwake on your device.
1. Stop the execution in Xcode, from now on you can just run it directly from the device.

Note: Every once in a while the build will expire and the app will begin crashing at startup. In this case, build and run it again.

## Usage
Just run the installed app on your device, no need to do it from Xcode once it's installed.
As long as the app running in the foreground, the device will not sleep.
