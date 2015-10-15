Event: CHAT_COMMAND
====

##CHAT_COMMAND

This is called when the logged in user types a chat command starting with forward slash '/' that is not handled natively by plug.dj. This allows you to run your own chat commands. It passes the entire chat string including the forward slash.

##USAGE

```
API.on(API.CHAT_COMMAND, callback);

function callback(value) {
    alert(value + ' typed as chat command');
}
```
