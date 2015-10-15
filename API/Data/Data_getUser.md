Data: getUser
====

```
API.getUser(userID)
```

Returns the user object of a specific user. If you do not pass a userID, it returns the user object of the logged in user.
"role" is user's staff role in the community you are currently in (0-5).
"gRole" is a user's global role. Admins are gRole 5. Brand Ambassadors are gRole 2, 3, and 4.

JSON

```
{
  "id": 123,
  "username": "music lover",
  "avatarID": "classic01",
  "level": 1,
  "role": 0,
  "gRole": 0,
  "joined": TIMESTAMP,
  "status": 0
}
```