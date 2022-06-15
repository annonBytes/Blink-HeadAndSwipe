Page-Turning with Facial Gestures
===================

![Cocoapods Compatible](https://img.shields.io/cocoapods/v/FaceTrigger.svg)


# Introduction
`Digital Page-turning` when playing the piano leads to an interruption of the music if this is not done quickly enough or if the device is not responsive enough. This project is aimed at minimizing page-turning effort and time taken to go through a digital sheet.

This is made possible by the capabilities of the `ARKit` `ARSCNView` library and `ML Kit's` face detection API to recognize facial gestures.

The `library` recognizes the following gestures:
* Smile
* Blink
- Wink Right
- Wink Left
* Brow Down
* Brow Up
* Squint
* Cheek Puff
* Mouth Pucker
* Jaw Open
* Jaw Left
* Jaw Right

# Getting Started
In other to get started, we need to integrate `ML Kit` into out `iOS application`. [Firebase's documentation](https://firebase.google.com/docs/ios/setup) is a good place to start. The following are quick highlights:
- Create a new Firebase project and register the App's bundle ID.
- Download the `GoogleService-Info.plist` file and put it into the Xcode project.
- Next, you have to install the dependencies (via terminal)

Just like this on the terminal path.

```bash
$ pod install
```

# Run and Build
Run the application by selecting the device and hitting `CMD + R` and build the code by hitting `CMD + B`
*Please note that the application will not work on the simulator. Use an Apple device with a TrueDepth camera*

Here is a quick look on how the application will look like when you run it. 
![Demo of the app](https://user-images.githubusercontent.com/20721628/173729406-e2c75aac-19e2-4447-a073-f2b185fabf01.PNG)


