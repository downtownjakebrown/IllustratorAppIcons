<img src="./ExampleOutputImages/ReadmeBanner.png"/>

[![Stars](https://img.shields.io/github/stars/downtownjakebrown/IllustratorAppIcons)](https://github.com/downtownjakebrown/IllustratorAppIcons/stargazers)
[![Issues](https://img.shields.io/github/issues-raw/downtownjakebrown/IllustratorAppIcons)](https://github.com/downtownjakebrown/IllustratorAppIcons/issues)
[![Current Version](https://img.shields.io/github/v/release/downtownjakebrown/IllustratorAppIcon)](https://github.com/downtownjakebrown/IllustratorAppIcons)
[![License](http://img.shields.io/badge/license-MIT-lightgrey.svg?style=flat)](./LICENSE) 

# Illustrator App Icon Template

Quickly turn your vector graphics into iOS and iPadOS app icons.

## Description

An Adobe Illustrator template for easily generating a full set of app icons for iOS and iPadOS apps. This project was tested using Illustrator 24.2 and iOS 14.0.

## Installation

Just grab the included [AI file](./IllustratorAppIcons.ai) in this repo.

## Usage Outline

1. Open the included [AI file](./IllustratorAppIcons.ai), and double click on the content of the largest artboard.
2. Confirm that you want to edit the "Symbol" definition, after which you'll enter "Symbol Editing Mode" in isolation.
3. Update the symbol with your app icon's content.
4. When you're done, exit Symbol Editing Mode (by clicking the left-pointing arrow in the top left corner of the canvas). After exiting, you should see all the app icon instances on the canvas update with your new content.
5. Time to export! Click File->Export->Export For Screens...
6. In the "Artboards" tab, choose the following options: 
   * "Select" all artboards.
   * "Export to" your preferred destination.
   * "Formats" should be just be a 1x scale PNG.  
7. Click "Export Artboards" to output you app icon images (see the Example Output directory in this repo for what to expect).
8. Open your XCode project, then drag and drop the images into their respective positions in the AppIcons image set in Assets.xcassets.
9. Install your app and check that the icons are there. Note: if you've previously installed the app without icons, you may need to delete and reinstall the app in order for the icons to show up.

## License
Available under the MIT license. See the [LICENSE](./LICENSE) file for more info.
