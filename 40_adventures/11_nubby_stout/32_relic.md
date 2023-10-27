```
{{ foundRelic = true }}
You have found where the VHS is coming from!
* {{ foundPerson == true && foundLocation == true }} Have all three!
  ** goto boss **
* {{ foundPerson == true }} Have person but not location
  **goto hookReturnGood**
* {{ foundLocation == true }} Have location but not person
  **goto hookReturnGood**
* Have nothing else, keep going!
  **goto hookReturnGood**
_Relic Herring_ (#relicHerring)
You examine the relic, before determining it's not the right one!
goto hookReturn
```
