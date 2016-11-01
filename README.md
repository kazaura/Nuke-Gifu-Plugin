<p align="center"><img src="https://cloud.githubusercontent.com/assets/1567433/13918338/f8670eea-ef7f-11e5-814d-f15bdfd6b2c0.png" height="180"/>

<p align="center">
<img src="https://img.shields.io/cocoapods/v/Nuke-Gifu-Plugin.svg?label=version">
<img src="https://img.shields.io/badge/supports-CocoaPods%20%7C%20Carthage-green.svg">
<img src="https://img.shields.io/badge/platforms-iOS-lightgrey.svg">
</p>


[Gifu](https://github.com/kaishin/Gifu) plugin for [Nuke](https://github.com/kean/Nuke) that allows you to load and display animated GIFs. You can see it for yourself in a demo, included in the project.


## Usage

The plugin features a pre-configured `Nuke.Manager` with GIF support, and an `AnimatedImageView`:

```swift
let view = AnimatedImageView()
AnimatedImage.manager.loadImage(with: URL(string: "http://...")!, into: view)
```

## Installation

### [CocoaPods](http://cocoapods.org)

To install the plugin add a dependency to your Podfile:

```ruby
# source 'https://github.com/CocoaPods/Specs.git'
# use_frameworks!

pod "Nuke-Gifu-Plugin"
```

### [Carthage](https://github.com/Carthage/Carthage)

To install the plugin add a dependency to your Cartfile:

```
github "kean/Nuke-Gifu-Plugin"
```

## Requirements

- iOS 9
- Xcode 8
- Swift 3

## Dependencies

- [Nuke 4.x](https://github.com/kean/Nuke)
- [Gifu 2.x](https://github.com/kaishin/Gifu)

## License

Nuke is available under the MIT license. See the LICENSE file for more info.
