# Spokes

### Description
Essentially Waze for cyclists, a mobile Android bike routing map with the ability to flag hazards along the way, as well as being informed of upcoming hazards. 


### Project Goals
*Core Features:* 

* Mobile Android app with React Native
* Map bike route directions based on shortest distance/time from Google’s map API or equivalent based on user’s location (GPS/network) and a single destination in downtown Toronto
* Map hazards (potholes, parked cars, construction, etc.) along bike routes based on user input (voice / manual input)
* Warn cyclist as they approach hazards with a combination of on-screen and/or audio cues

*Stretch Features:* 

* Add additional bike route directions based on available designated bike paths, fewest left turns
* Add user account features (link to Google/FB/other social media accounts) such as favourite routes, history of destinations, etc.


### Tech Stack
Front-end: Node, React Native, Redux, Axios
Back-end: Node, Express, mongoDB (hazards, fave routes, …?), Mongoose, Postgres (user accounts), Knex/Bookshelf


### Description of Data
Front-end: Base map visuals provided by map API with layout/design according to UX input
Back-end: Route coordinates, hazard coordinates

test
