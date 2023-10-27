```
{{ foundLocation = true }}
You have found where Rodrac will commit his crime!
* {{ foundPerson == true && foundRelic == true }} Have all three!
  ** goto boss **
* {{ foundPerson == true }} Have person but not relic
  **goto hookReturnGood**
* {{ foundRelic == true }} Have relic but not person
  **goto hookReturnGood**
* Have nothing else, keep going!
  **goto hookReturnGood**
_Location Herring_ (#locationHerring)
You explore around, before realizing you went to the wrong location!
goto hookReturn
```
