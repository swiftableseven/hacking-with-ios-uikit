# Milestone 6: Country Facts

### Personal Notes
- using [**country data**](https://github.com/mledoze/countries) maintained by **@mledoze** in JSON format
- conforming only to `Decodable` protocol; `Encodable` is unused for project
- custom `DetailField` used to stack information on detail screen
- using **nil-coelescing operator** for potentially unknown or undefined country details

### Challenge
> Your challenge is to make an app that contains facts about countries: show a list of country names in a table view, then when one is tapped bring in a new screen that contains its capital city, size, population, currency, and any other facts that interest you. The type of facts you include is down to you – Wikipedia has a huge selection to choose from.
>
> To make this app, I would recommend you blend parts of project 1 project 7. That means showing the country names in a table view, then showing the detailed information in a second table view.
>
> How you load data into the app is going to be an interesting problem for you to solve. I suggested project 7 above because a sensible approach would be to create a JSON file with your facts in, then load that in using `contentsOf` and parse it using `Codable`. Regardless of how you end up solving this, I suggest you don’t just hard-code it into the app – i.e. typing all the facts manually into your Swift code. You’re better than that!

### Solution Preview
<img src="https://user-images.githubusercontent.com/4438390/185700739-782c2c98-1e11-49d0-94e5-1933502894ce.png" style="float:left; width: 46%; margin-left: 1%"><img src="https://user-images.githubusercontent.com/4438390/185700837-f61cd9df-eccc-44e0-a2e8-5f16bcfd1f40.png" style="float:left; width: 46%; margin-left: 1%">
