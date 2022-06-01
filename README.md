Quick start examples for integrating [OEP (Offscreen Effect Player) on iOS](https://docs.banuba.com/face-ar-sdk/ios/ios_getting_started) and WebRTC into Objective C apps.

**Important**  
Please use [v0.x](../../tree/v0.x) branch for SDK version 0.x (e.g. v0.38).

# Getting Started

1. Get the latest Banuba SDK archive for iOS and the client token. Please fill in our form on [form on banuba.com](https://www.banuba.com/face-filters-sdk) website, or contact us via [info@banuba.com](mailto:info@banuba.com).
2. Copy `BanubaEffectPlayer.xcframework` project folder from the Banuba SDK archive into `Frameworks` dir:
    `BNBEffectPlayer/bin/BanubaEffectPlayer.xcframework` => `quickstart-ios-swift/Frameworks/`
3. Copy and Paste your client token into appropriate section of `quickstart-webrtc-ios/quickstart-webrtc-ios/ViewController.m`. See constant BANUBA_SDK_KEY.
4. Execute 'pod install' to get WebRTC framework.
5. Open the project in xCode and run the example.

# Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

# Testing

The project contains XCUITest in `quickstart-ios-swiftUITests`. For correct tests work `UItest` album should be created on device and should contain at least one photo and one video inside.

# Project structure

1. The folder 'Frameworks' - contains Banuba SDK Framework.
2. The folder 'quickstart_webrtc_ios/Resources/effects' - the effects which can be used in the app.
3. Main code of the sample concentrated in ViewController.h and ViewController.m.