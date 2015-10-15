Event: WAIT_LIST_UPDATE
====

##WAIT_LIST_UPDATE

This is called when the users in the wait list change, whether somebody joins, leaves, is removed, added to or moved in the wait list. It returns an array of the user objects in order from beginning to last in the wait list.

##USAGE

```
API.on(API.WAIT_LIST_UPDATE, callback);
```
