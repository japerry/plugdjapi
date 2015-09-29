Moderation: moderateMuteUser
====

```
API.moderateMuteUser(userID, reason, duration)
```

If you have permission, this command mutes a user within the community for a limited time. During this time, they will not be able to chat. You should include a reason id (1-5) to avoid showing the dialog. Valid durations are API.MUTE.SHORT, API.MUTE.MEDIUM and API.MUTE.LONG. If you pass any value other than those it will default to API.MUTE.LONG.

Custom mute durations are not allowed at this time. Currently, the durations are 15, 30, and 45 minutes.
