Beat cops - Paid off to not interfere! They work a different sector than the detectives
Conflict: Find incriminating evidence; Fight the guards!

- Charisma
    * Pay 20 gold
      You pay off the guards!
      **goto guardSuccess**
    * Refuse to pay!
      **goto guardCombat**
- Stealth
    You sneak past the guards!
- Combat
    *Guart Post Combat!* (#guardCombat)
      You fight with 
      - Knight (MM347)
      - Guard (MM347)
      - Guard (MM347)
      - Guard (MM347)
      - Guard (MM347)
      * on win
        ** goto guardSuccess **
      * on lose
        ** goto guardFailure **
  _Guard Post_(#guardSuccess)
  You've successfully handled the guards!
