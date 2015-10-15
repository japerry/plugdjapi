Event: CHAT
====

##CHAT

This is triggered when an incoming chat arrives. It passes a chat JSON object.

##USAGE

```
API.on(API.CHAT, listener);
```

##JSON
```
{
    type: <string> // "message", "emote", "moderation", "system"
    un: <string> // the username of the sender
    uid: <int> // the user id of the sender
    message: <string> // the chat message
}
```