# ALIENS

Some number of Broodlings is spawn after unit is killed. Broodlings count is set for each player. Broodlings won't spawn after structures are destroyed or any unit that not produces or uses supply is killed. Also broodlings are not spawn if player kills own unit.

You can set amount of Broodlings equal to supply used by killed unit.

Created Broodlings have order to attack point where unit-killer is.

Set to each player individually.

**v2.36**

* [BUGFIX] Broodlings are not spawn after killing unit that doesn't use or provide supply.

**v2.35**

* [BUGFIX] Number of Broodlings for options "1" - "10" now is equal to value for player who lost the unit and not who killed it.

**v2.20**

* [FEATURE] In-game hint with handicap's description is added. It's shown only if handicap is turned on at least for one player.

**v2.0**

* [BUGFIX] Number of created Broodlings now is taken from correct player.
* [BUGFIX] Now killed Overseers and Overlords also spawn Broodlings.
* [FEATURE] Now it's possible to set amount of created Broodlings equal to unit's supply limit (but not less than 1).
* [FEATURE] Created Broodlings attack a point where unit-killer is.
* [REFACTORING] Lobby options refactoring.
