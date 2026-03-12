# itunes-client
Simple itunes client for interacting with their api

Html script tag 👇

```html
<script src="https://raw.githubusercontent.com/BlazeInferno64/itunes-client/refs/heads/main/itunes-client.js"></script>
```

# Api usage:

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
