# custom-discord-jokes
> A npm-module for random and customized jokes.

## Install

```
$ npm install --save custom-discord-jokes
```

## Usage

```js
var customDiscordJokes = require('custom-discord-jokes');

// To get a random dad joke
customDiscordJokes.getRandomDadJoke (function(joke) {
    //=> console.log(joke);
});

// To get a random Chuck Norris joke
customDiscordJokes.getRandomCNJoke (function(joke) {
    //=> console.log(joke);
});

// To get a customized joke
var fn = "Jackie";
var ln = "Chan";
customDiscordJokes.getCustomJoke (fn, ln, function(joke) {
    //=> console.log(joke);
});
```