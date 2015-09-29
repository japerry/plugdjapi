Event: GRAB_UPDATE
====

##GRAB_UPDATE

This is called when somebody in the community (including you) grabs what is currently playing to their collection. It passes the user object who added it.

##USAGE

```
API.on(API.GRAB_UPDATE, callback);

function callback(obj) {
    var media = API.getMedia();
    alert(obj.user.username + " added " + media.author + " - " + media.title);
}
```