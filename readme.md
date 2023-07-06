# OnlineRadioBox JSON

As my first mobile app project i wanted to create a radio player with features. I first built this in HTML, CSS and JavaScript and while i won't be using this as a web app i'm sure others will find this useful.

![Data Screenshot](https://github.com/decafdevio/get-online-radio-data/assets/96788931/1aebed80-87a5-460b-a973-f80613dcf403)

## Digest

All data is extracted from JSON files from onlineradiobox.com so while we're not connecting to the back end the host can still be referred to as an API.

I would recommend filtering all the endpoints and combining the values you want into a new JSON to save multiple requests, this is what i plan to do later.
For the sake of testing i created this within one html but the correct way is to have the styles in a CSS file and scripts in a JS file.

## Endpoints

These are examples to collect the data for the radio station: **BBC Radio 1 Dance**
`https://onlineradiobox.com/json/uk/bbcdance`

#### Audio
`https://onlineradiobox.com/json/uk/bbcdance/widget/`   
`{streamURL}`

#### Playlist
`https://onlineradiobox.com/json/bbcdance/playlist/0`

#### Additional
`http://scraper.onlineradiobox.com/uk.bbcdance`

## Support Me
<a href="https://www.buymeacoffee.com/decafdevio"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" width="200" /></a>