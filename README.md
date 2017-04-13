# Seton Hill University - Shuttle Tracker

Provide student and staff with a way to check a campus shuttles current location and schedule.

<img src="ShuttleTrackerUp1.PNG" alt="Shuttle Tracker Traffic Screenshot" width="40%">
<img src="ShuttleTrackerUp2.PNG" alt="Shuttle Tracker Hybrid Screenshot" width="40%"><img src="ShuttleTrackerSide.PNG" alt="Shuttle Tracker Menu Screenshot">

## Features
* Utilizes Firebase to push changes to all iOS devices with the app currently open. This occurs nearly instantly when data in Firebase is changed.
* Logs analytic data into Firebase.
* Logs crash data into Firebase.
* Manage parameters through Firebase Remote Config.
* Smooth interface that does not require the user to leave the main screen unless they are viewing schedule.
* Use the Google Maps iOS SDK because it is the most up to date map and has a great SDK.
* Flat design.
* Changes to night mode that is easy on the eyes in the dark. Utilizes sunset and sunrise to determine the mode.

## Dependencies
* [Firebase](https://firebase.google.com/)
* [GoogleMaps](https://developers.google.com/maps/documentation/ios-sdk/)
* [Solar](https://github.com/ceeK/Solar)

## Status
Under Development - Currently testing in TestFlight
