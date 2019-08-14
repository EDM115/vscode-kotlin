# Kotlin IDE for Visual Studio Code
Smart code completion, linting, debugging and more for Kotlin in VSCode using the [language server](https://github.com/fwcd/kotlin-language-server).

[![Version](https://img.shields.io/visual-studio-marketplace/v/fwcd.kotlin)](https://marketplace.visualstudio.com/items?itemName=fwcd.kotlin)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/fwcd.kotlin)](https://marketplace.visualstudio.com/items?itemName=fwcd.kotlin)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/fwcd.kotlin)](https://marketplace.visualstudio.com/items?itemName=fwcd.kotlin)

To use, open a Kotlin file inside a Gradle or Maven project. The language server will then automatically launch in the background.

## Features
* Code completion
* Linting
* Debugging
* Go-to-definition
* Signature help
* Hover
* Document symbols

## Usage

### Debugging
* Setup:
    * Open the `launch.json` file in your project and invoke code completion to create a new launch configuration (or select `Add Configuration...` in the debug tab)
* Launch:
    * `./gradlew build` your project (before every launch)
	* Click the `Run` button in the `Debug` tab or press `F5`
