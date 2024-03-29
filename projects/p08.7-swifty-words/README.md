# Project 8: 7 Swifty Words

### Personal Notes
- the `String` class has several helpful methods for splitting and manipulating data:
    - `trimmingCharacters(in:)`
    - `components(separatedBy:)`
    - `replacingOccurrences(of:, with:)`

### Additional Challenges
> 1. Use the techniques you learned in [**project 2**](https://github.com/seventhaxis/hacking-with-ios/tree/master/projects/p02.guess-the-flag/) to draw a thin gray line around the buttons view, to make it stand out from the rest of the UI.
> 2. If the user enters an incorrect guess, show an alert telling them they are wrong. You’ll need to extend the `submitTapped()` method so that if `firstIndex(of:)` failed to find the guess you show the alert.
> 3. Try making the game also deduct points if the player makes an incorrect guess. Think about how you can move to the next level – we can’t use a simple division remainder on the player’s score any more, because they might have lost some points.

### Solution Preview
<img src="https://user-images.githubusercontent.com/4438390/185154624-823d9481-890b-401c-a11e-7be41a1d5490.png">
