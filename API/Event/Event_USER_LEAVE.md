Event: USER_LEAVE
====

##USER_LEAVE

This is called when a user leaves the community. It passes a user object.

##USAGE

```
API.on(API.USER_LEAVE, callback);

function callback(user) {
    alert(user.username + " left the room");
}
```
