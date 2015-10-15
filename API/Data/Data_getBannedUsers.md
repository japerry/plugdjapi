Data: getBannedUsers
====

```
API.getBannedUsers()
```

If you are a manager or above and the banned user list has been clicked on in the UI at least once, you can get a list of the banned users. This does not currently load the ban list if you haven't clicked on it in the UI at least once.

##JSON

```
{
    "timestamp": TIMESTAMP,
    "id": 1,
    "username": "Steven",
    "moderator": "jOyama",
    "reason": 1,
    "duration": -1
}

```