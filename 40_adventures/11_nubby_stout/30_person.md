```
{{ foundPerson = true }}
You have found Rolf AssRoids!
* {{ foundRelic == true && foundLocation == true }} Have all three!
  ** goto boss **
* {{ foundRelic == true }} Have relic but not location
  **goto hookReturnGood**
* {{ foundLocation == true }} Have location but not relic
  **goto hookReturnGood**
* Have nothing else, keep going!
  **goto hookReturnGood**
_Person Herring_ (#personHerring)
You talk to the NPC, before realizing it's not the right person!
goto hookReturn
```
