# Deployment Instructions

## Local Installation

- Fork this repo and then clone the fork to your local computer
- Run `npm i` to install all dependencies
- Run `npm start` to start local environment and automatically open browser
- Update axios ajax urls to point to your API

# Deploy to Heroku

- Run `heroku create -b https://github.com/mars/create-react-app-buildpack.git` to create heroku app
- Run `git push heroku master` to push code to heroku
- Run `heroku open` to open remote app
