# negotiating-pseudo-code
If x, then OBJECT VIGOROUSLY, RAISE ERROR, OR WATER DOWN

The idea is to describe a series of negotiating rules in pseudo code that could be expanded upon later, or used to process contracts to pull out issues of concern.

The rules generally assume a client - provider relationship and as most of the time a provider will provide its own standard terms, are written to assist the client in improving the terms to their benefit.

```javascript
if (provider.thirdPartyIndemnity && !conductOfClaims){
   clause.addSubClause(conductOfClaims)
}
```

At the moment one unknown is how to differentiate between a provision that benefits one party, versus a similar provision which is its reverse. For example, if a provider offered a third party indemnity for the benefit of a client, it wouldn't be in the client's interest to introduce conduct of claims provisions into the agreement (on the basis that this would give control to the provider in the event of a claim). One option may be to associate various clauses with a particular entity as the entity that would benefit from the provision...
