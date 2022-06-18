pod-template
============

A template for creating pod modules for Sparkle iOS using Clean Architecture with the following features:

- Git as the source control management system
- Clean folder structure
- Project generation
- Commercial license
- Testing as a standard
- Clean Architecture initial structure
- Depedency injections

## Getting started

You will want to work with the ruby classes inside the `setup` folder, and the example base template that it works on from inside `template/swift/`. 


## Commands

* `pod lib create uUpload --template-url=/Users/rafael.reis/Downloads/template/sparkle-ios-pod-template --verbose`
* `pod lib create uLibrary --template-url=/path/to/template --verbose`: creates your library using this custom local pod template with detailed log messages.

* `pod lib create uLibrary --template-url=url/of/template/repository/`: creates your library using a pod template host in a git repository.


## Guideline

https://guides.cocoapods.org/making/using-pod-lib-create.html.

## Requirements:

- CocoaPods 1.0.0+
