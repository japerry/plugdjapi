Event: USER_SKIP
====

##USER_SKIP

This is triggered when the current DJ skips their own turn. It passes the user name of the DJ who skipped.

##USAGE

```
API.on(API.USER_SKIP, listener);
```

Example: API.on(API.USER_SKIP, function(data) { API.sendChat(data + " has skip his song"); });