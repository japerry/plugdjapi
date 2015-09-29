Data: getWaitListPosition
====

```
API.getWaitListPosition(userID)
```

If the userID is in the wait list, it returns their position (0 index - so 0 means first position). Returns -1 if they're not in the wait list. If you do not pass a userID, it uses the logged in user ID.
