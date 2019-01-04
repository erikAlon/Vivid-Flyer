# Goals

- Scan flyer and look for artist names as text
- Generate a see through button on top of text
- Create a link on button to artist music on **the Player** of choice from the user

# Stretch Goals

- Initialize a database with artist logos
- Scan flyer and compare arist logos anywhere in flyer to database artist logos and match artist to music

# Full Stack for this app

| Tech    | Description                                     |
| ------- | ----------------------------------------------- |
| AWS S3  | Store and retrieve flyers and artist logos      |
| Express | Set up server and build API calls               |
| Node.js | Use javascript outside of browser               |
| React   | Front end                                       |
| Redux   | Manage state to scale application in the future |
| MySQL   | SQL database to store finite dj information     |
| GraphQL | Manage API calls                                |
| Apollo  | Integrate GraphQL with React                    |
| TinEye  | Reverse image search through AWS S3             |

# Objective

_Feed any flyer to app and render a **(Rich file with links and an overlaying web or app music player)** _

- _Soundcloud has raised a total investment of $250 kk and was worth to investors $700 kk at inception but now under \$100kk_ - jan 3rd, 2019
- **Players:** SoundCloud, Slacker Radio, Spotify, Amazon Music Unlimited, Apple Music, Deezer, Tidal, Google Play Music Store, iHeartRadio, Pandora

# Stack (MERN)

| Tech      | Purpose                                                                                                                                                 |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Netlify   | Deploy website. It will have access to a MongoDB where all links to songs by DJ curated by myself will exist. These links will be soundcloud endpoints. |
| MongoDB   | SQL database that holds a list of all song endpoints                                                                                                    |
| Express   | Handles API's                                                                                                                                           |
| React     | Frontend to handle styling and functionality. Ready app for react native                                                                                |
| Node.js   | Handles API calls                                                                                                                                       |
| _Testing_ |                                                                                                                                                         |
| _GraphQL_ |                                                                                                                                                         |
