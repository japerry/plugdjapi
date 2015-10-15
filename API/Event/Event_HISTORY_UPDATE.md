Event: HISTORY_UPDATE
====

##HISTORY_UPDATE

This is called when the community history updates. It returns an array of history objects from newest to oldest.

##USAGE

```
API.on(API.HISTORY_UPDATE, callback);
```

##JSON
```
    "user": {
      "id": 123,
      "username": "Better Call Saul"
    },
    "media": {
      "id": 432,
      "cid": "sbwjdb2beu",
      "format": 1,
      "author": "Neil Diamond",
      "title": "Hot August Night",
      "image": "http://url.tld/image.jpg",
      "duration": 232
    },
    "score": {
      "positive": 12,
      "negative": 15,
      "grabs": 3,
      "skipped": 0/1/2,
      "earn": true,
      "listeners": 95
    }
```