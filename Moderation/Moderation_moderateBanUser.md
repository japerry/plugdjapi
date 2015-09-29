Moderation: moderateBanUser
====

```
API.moderateBanUser(userID, reason, duration)
```

If you have permission, permanently bans a user from the community. You can include a reason id (1-5) to avoid showing the dialog. Valid durations are API.BAN.HOUR, API.BAN.DAY and API.BAN.PERMA. If you pass any value other than those it will set it to API.BAN.PERMA (so if you leave it out, it will be a permanent ban) except for bouncers where it will default to API.BAN.HOUR.

Custom ban durations are not allowed at this time.
