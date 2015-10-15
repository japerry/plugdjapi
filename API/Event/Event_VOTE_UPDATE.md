Event: VOTE_UPDATE
====

##VOTE_UPDATE

This is called when somebody in the community (including you) votes. It passes a JSON object with a user object and the vote, -1 for negative, 1 for positive.

##USAGE

```
API.on(API.VOTE_UPDATE, callback);
```
