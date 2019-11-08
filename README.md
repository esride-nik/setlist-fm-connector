# Setlist.fm Connector Node.js service

## Getting started

### Local operation

* Enter ```npm install``` to install dependencies.
* Get an API key at [setlist.fm](https://api.setlist.fm/docs/1.0/index.html) and enter it in the config.json file .
* Then ```npm start``` the project.

### Alternatives

Install [node.js](https://nodejs.org/en/) and this project on a server machine of your choice or choose a cloud service of your liking. I have a [demo instance](https://setlist-fm-connector.herokuapp.com/) running on a [Heroku](https://www.heroku.com/) free plan.

## Operations

### /artists

|parameter|type|description
|---|---|---|
|artistName|string|performs artist search by artist name|
|name|string|performs search for artist name|

### /setlists

|parameter|type|description
|---|---|---|
|artistName|string|performs setlist search by artist name|
|page|number|defines the page number of the setlist.fm request|

### /demoB

|parameter|type|description
|---|---|---|
|-|-|static demo response 'Black Peaks'|

### /demoT

|parameter|type|description
|---|---|---|
|-|-|static demo response 'Tame Impala'|
