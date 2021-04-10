# VS Code Live Share Demo

A simple Node.js project you can use to test out some of the VS Code Live Share extension functionality.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku CLI](https://cli.heroku.com/) installed.

```sh
$ git clone https://github.com/thawkin3/vs-code-live-share-demo.git
$ cd vs-code-live-share-demo
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create  # or `heroku create <app name>`
$ git push heroku master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation and Resources

- [VS Code Live Share Extension](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [VS Code Live Share Use Cases](https://docs.microsoft.com/en-us/visualstudio/liveshare/reference/use-cases)
- [Getting Started on Heroku with Node.js](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
