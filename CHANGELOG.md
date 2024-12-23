# Change Log
All notable changes to the Kotlin extension will be documented here.

## [0.2.36]
d408727 fix syntax highlighting problem for trailing lambda in string interpolation
a53896a fix #158 Kotlin Language Client client: couldn't create connection to server on windows

## [0.2.35]
- Improve keyword highlighting
- Add config options for code generation (needed for Java interoperability), which is now opt-in due to a lack of stability on recent Kotlin versions

## [0.2.34]
- Improve object/function literal highlighting

## [0.2.33]
- Add config options for inlay hints, scripts and diagnostics

## [0.2.27]
- Clean server before updates
- Add override members

## [0.2.24]
- New icon
- Note above JDK
- Minor fixes

## [0.2.23]
- Support for semantic highlighting

## [0.2.22]
- New `kotlin.indexing.enabled` option

## [0.2.21]
- Progress indicators

## [0.2.19], [0.2.20]
- Minor tweaks

## [0.2.18]
- Activate only if the user actually tries to debug a Kotlin application

## [0.2.16], [0.2.17]
- Minor fixes

## [0.2.15]
- Fix issue where debug adapter would not be initialized
- Add `debugAttach` config options for simplifying debugging of the language server itself

## [0.2.14]
- Fix unpacking issue

## [0.2.13]
- Use Webpack to bundle files

## [0.2.12]
- Automatically detect updated Java sources

## [0.2.11]
- Add support for TCP transport
- Re-add support for Kotlin code blocks in Markdown

## [0.2.10]
- Improved class file navigation
- Confirmation prompt before downloading binaries ([#7](https://github.com/fwcd/vscode-kotlin-ide/issues/7))

## [0.2.5]
- Customizable server paths
- Integrated debugging support
- Automatic language server/debug adapter updates
