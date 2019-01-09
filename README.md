# Goals

- scan image of flyer and look for artist names as text
- generate a see through button on top of text
- create a link on button to artist music on **the Player** of choice from the user
  > **the Players: (more out there)** SoundCloud, Slacker Radio, Spotify, Amazon Music Unlimited (Prime Music), Apple Music, Deezer, Tidal, Google Play Music Store, iHeartRadio, Pandora, Youtube Music

# Stretch Goals

- initialize a database with artist logos
- scan flyer and compare arist logos anywhere in flyer to database artist logos and match artist to music
- web page with an input box that searches and produces a vivid flyer based off search query
- moble app that functions as web page but also utilizes a scan feature with the phones camera

# Full Stack for this app

| Tech                         | Description                                 |
| ---------------------------- | ------------------------------------------- |
| AWS S3                       | Store and retrieve flyers and artist logos  |
| Express                      | Set up server and build API calls           |
| Node.js                      | Use javascript outside of browser           |
| Angular                      | Front end framework                         |
| MySQL                        | SQL database to store finite dj information |
| GraphQL                      | Manage API calls                            |
| Apollo                       | Integrate GraphQL with Angular              |
| TinEye/ Google Custom Search | Reverse image search through AWS S3         |
| _testing solution_           |                                             |
| _deploying solution_         |                                             |

# Objective

- Feed any flyer to app and render a **(rich text with links and an overlaying web or app music player)**

- _"Soundcloud has raised a total investment of $250 kk and was worth to investors $700 kk at inception but now under \$100kk" - Jan 3rd, 2019_
