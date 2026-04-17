# Project 6 - TranslateMe

Submitted by: Sara Kanu

**TranslateMe** is a SwiftUI-based iOS application that allows users to translate words, phrases, or sentences between different languages using the MyMemory API. The app also stores translation history using Firebase Firestore and supports user authentication with Firebase Authentication.

Time spent: 4 hours spent in total

---

## Required Features

The following **required** functionality is completed:

* [x] Users open the app to a home page with an input field, translate button, and output field
* [x] Users can translate text from one language to another
* [x] A history of translations is stored using Firebase Firestore
* [x] Users can clear translation history

---

## Stretch Features

The following **stretch** features are implemented:

* [x] Multiple language selection (source and target)
* [x] Custom UI with gradient backgrounds and modern styling
* [x] Improved language selector layout with swap button
* [x] Persistent login using Firebase Authentication

---

## Video Walkthrough

Here's a walkthrough of implemented user stories:
https://www.youtube.com/shorts/07RALJY6ZCE

---

## Notes

Describe any challenges encountered while building the app:

* Setting up Firebase correctly (Firestore + Authentication + configuration file)
* Debugging Firebase errors like `CONFIGURATION_NOT_FOUND`
* Customizing SwiftUI Picker UI to properly display language names
* Managing environment objects (`AuthManager`) across views

---

## License

```
Copyright [2026] Sara Kanu

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
```
