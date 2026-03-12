# itunes-client
Simple itunes client for interacting with their api

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
