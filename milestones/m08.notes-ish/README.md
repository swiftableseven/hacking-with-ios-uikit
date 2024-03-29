# Milestone 8: Notes-ish

### Personal Notes
- the optional `UITextViewDelegate` method `textViewDidChange(_:)` allows you to monitor for user-initiated changes to a text view
- custom `Note` class that conforms to `Codable` for saving via `UserDefaults`
- showing note's modified date as subtitle text on table cell
- passing date back to table view using `NoteManagementDelegate` protocol
    - the delegate/protocol is a **one-to-one** communication pattern
    - alternatively, the notification/observer pattern is a **one-to-many** pattern
- managing appearance of `UINavigationbar` within `AppDelegate.swift`

### Challenge
> Have you ever heard the phrase, _“imitation is the highest form of flattery”_? I can’t think of anywhere it’s more true than on iOS: Apple sets an extremely high standard for apps, and encourages us all to follow suit by releasing a vast collection of powerful, flexible APIs to work with.
>
> Your challenge for this milestone is to use those API to imitate Apple as closely as you can: I’d like you to recreate the iOS Notes app. I suggest you follow the iPhone version, because it’s fairly simple: a navigation controller, a table view controller, and a detail view controller with a full-screen text view.
>
> How much of the app you imitate is down to you, but I suggest you work through this list:
> 1. Create a table view controller that lists notes. Place it inside a navigation controller.
> 2. Tapping on a note should slide in a detail view controller that contains a full-screen text view.
> 3. Notes should be loaded and saved using `Codable`. You can use `UserDefaults` if you want, or write to a file.
> 4. Add some toolbar items to the detail view controller – _'Delete'_ and _'Compose'_ seem like good choices.
> 5. Add an action button to the navigation bar in the detail view controller that shares the text using `UIActivityViewController`.
>
> Once you’ve done those, try using **Interface Builder** to customize the UI – how close can you make it look like Notes?


### Solution Preview
<img src="https://user-images.githubusercontent.com/4438390/185702235-7b5226e2-118c-4c9c-982d-9dc1de45672d.png" style="float:left; width: 30%; margin-left: 1%"><img src="https://user-images.githubusercontent.com/4438390/185702256-1c24fce1-6859-44f2-a5ef-4e7810a3ce17.png" style="float:left; width: 30%; margin-left: 1%"><img src="https://user-images.githubusercontent.com/4438390/185702274-72982555-fee7-4072-8af6-9debc884f79f.png" style="float:left; width: 30%; margin-left: 1%">
