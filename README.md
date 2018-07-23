# Node Js RESTFull microservice
https://immobilien-test.raphael.website/

NodeJS microservice written with ExpressJS, MongoDB and Mongoose to get GitHub API access_token and persist users repositories searches into a MongoDB collection.

## endpoints
- /authenticate: to get GitHub API access_token avoiding CORS and also to ommit client_secret to browsers.
- /repositories?q={USERLOGIN}: to retrive user repositories searches.

### how to clone and install dependencies

- install mongodb
- install nodejs
- install npm
- git clone https://github.com/raphaelkoszalka/repositories-viewer-server.git
- cd repositories-viewer-server
- npm install
- configure project .env

### how to run
- start mongodb
- cd repositories-viewer-server
- npm start

## notes
- since it was written only by myself i reversed my commits on errors instead of utilizing branches strategy, but if it was written by a team of developers I would have used branches strategy.
- written in NodeJS for its proved efficiency in microservices development.
- MongoDB with Mongoose Schema types for the DB.

### further help
rmkoszalka@gmail.com

