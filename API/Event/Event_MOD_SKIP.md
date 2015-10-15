Event: MOD_SKIP
====

##MOD_SKIP

This is called when a moderator force skips the current DJ. It passes the username of the moderator.

##USAGE

```
API.on(API.MOD_SKIP, callback);

function callback(username) {
    alert(username + " has skipped the current DJ");
}
```