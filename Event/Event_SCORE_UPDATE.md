Event: SCORE_UPDATE
====

##SCORE_UPDATE

This is called whenever the score changes and it passes a score object with the properties positive, negative, and grabs.

##USAGE

```
API.on(API.SCORE_UPDATE, callback);

function callback(obj) {
    alert(obj.positive + " woots, " + obj.negative + " mehs, " + obj.grabs + " grabs);
}
```
