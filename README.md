# itunes-client
Simple itunes client for interacting with the api

## Live demo

<a href="https://blazeinferno64.github.io/itunes-client/">

```
https://blazeinferno64.github.io/itunes-client/
```
</a>

## Html script tag 👇

```html
<script src="https://raw.githubusercontent.com/BlazeInferno64/itunes-client/refs/heads/main/itunes-client.js"></script>
```

## Api usage:

```js
const client = new ITunesClient();

client.search("Bohemian Rhapsody")
    .then(results => {
        console.log(results);
    })
    .catch(err => {
        console.error(err);
    });

client.cancel("User navigated away.");
```
