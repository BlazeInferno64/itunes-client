# itunes-client
Simple itunes client for interacting with the itunes public api endpoint

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

or if you wanna use locally then do (you gotta download the file first tho)

```html
<script src="./itunes-client.js"></script>
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


// If you wanna cancel your api call then sinply use 👇 
client.cancel("User navigated away.");
```


## For Node.js support

> Currently under development will be released soon!
