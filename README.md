In order to run this app:
 
- Install [node.js](https://nodejs.org/en/) (version 8 or above).
- Clone the repository.
- Install dependencies using `npm install`.

Then run the app as follows:

```
$ PUSHOVER_USER=pushover-user-key PUSHOVER_TOKEN=pushover-api-token node index.js
```

Finally, add the webhook to https://app.plex.tv/desktop#!/account/webhooks (it'll be http://localhost:10000).

The app also accepts a custom port number from the `PLEXPUSH_PORT` environment variable.
