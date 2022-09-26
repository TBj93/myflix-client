# myflix-client v1.0.1 alpha

![alt text](https://github.com/TBj93/myflix-client/blob/myflix-redux/readme%20imgs/myflix1.PNG?raw=true)

## This is a working client rendering a database of movies.

The movies are being displayed in cards using react-bootstrap and contain a movie image, fetched by an external URL, as well as information about the genre and its director.
This client uses axios to fetch movies from a database, with the help of an API that is deployed on heroku  [Link](https://tims-movie-api.herokuapp.com/). 
It's interactive and this client also provides the possiblity to create a user account(by clicking the register button), stored on the database, which is required to log into the site and see the stored movies. 
The account can be updated and deleted. It also shows the user's favorite movies.
A validation for form as well as authorization via JWT is implemented to have a certain security standard. 

## Challenges
Understanding props and states, was a bit tricky in the beginning. Also wrapping my mind around React hooks and lifecycles required me to do a lot of research, reading threads on github, stackoverflow or watching well educating videos on youtube. 

![alt text](https://github.com/TBj93/myflix-client/blob/myflix-redux/readme%20imgs/myflix2.PNG?raw=true)


## Technologies used
- Html
- Css
- JS
- React

## Packages and dependencies
- React-Redux
- React-bootstrap
- Router
- Axios
- Parcel



### Requirements
This app is using react.js as well as react-redux. Latest browser version is required in all popular browsers.


### Install and get started

- Clone repo
- install packages and dependencies as seen in packages.json file
- go to root folder in terminal and run ```bash npm install ```
- to start the app in local browser run ```bash parcel src/index.html ```


