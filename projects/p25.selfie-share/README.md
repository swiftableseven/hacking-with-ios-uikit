# Project 25: Selfie Share

### Personal Notes
- all multipeer services for iOS must declare a service type - a unique 15-digit string to identify the service
    - may only contain letters, numbers and hyphens
- if hosting a session with one or more connected peers, an option is available to _List Current Connections_ and see names of all peer devices
- **TODO:** update to support scene pattern for Xcode 11; the following changes were employed in order to get a working app
    - current target is iOS 12.4
    - `SceneDelegate.swift` was removed
    - _Application Scene Manifest_ was removed from `Info.plist`
    - `AppDelegate.swift` was recreated to include all methods provided from previous version of Xcode


### Additional Challenges
> 1. Show an alert when a user has disconnected from our multipeer network. Something like _“Paul’s iPhone has disconnected”_ is enough.
> 2. Try sending text messages across the network. You can create a `Data` from a string using `Data(yourString.utf8)`, and convert a `Data` back to a string by using `String(decoding: yourData, as: UTF8.self)`.
> 3. Add a button that shows an alert controller listing the names of all devices currently connected to the session – use the `connectedPeers` property of your session to find that information.

### Solution Preview
<img src="https://user-images.githubusercontent.com/4438390/185264606-62c49061-98aa-4d6e-9a72-101c5611b5a2.png" style="float:left; width: 30%; margin-left: 1%"><img src="https://user-images.githubusercontent.com/4438390/185264616-16ccd639-9805-48ac-8fdd-b3f92bdfcba8.png" style="float:left; width: 30%; margin-left: 1%"><img src="https://user-images.githubusercontent.com/4438390/185264627-23c3393b-b537-4e77-ad08-74cb02ff7220.png" style="float:left; width: 30%; margin-left: 1%">
