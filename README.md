# Usage

## Environment required

- [nodejs](https://nodejs.org/) >= 7.9.0   (for ``async/await`` refer [node.green](http://node.green/))
- [mongodb](https://www.mongodb.org/) >= 3.4


## Install dependencies

````
$ npm install
````

## Initialize config file

````
$ cp config.default.js config.js
````

## Start Service

### Development

````
$ npm start
````

### Production

````
$ npm run server
````

or

````
$ NODE_ENV=production Port=8000 node app
