Event: ADVANCE
====

##ADVANCE

This is triggered when the dj booth advances to the next play. It passes a JSON object with a dj user object, the current media object, a score object, and, if there was something playing before the advance, the lastPlay object, which is a JSON object of the last played item.

##USAGE

```
API.on(API.ADVANCE, callback);
```

##JSON
```
{
    dj: <user Object>,
    media: <media Object>,
    score: {
        positive: <int>,
        negative: <int>,
        grabs: <int>
    },

    lastPlay: {
        dj: <user Object>,
        media: <media Object>,
        score: {
            positive: <int>,
            negative: <int>,
            grabs: <int>
        }
    }
}
```
