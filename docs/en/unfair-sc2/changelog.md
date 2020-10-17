# Changelog

## v3.6

В мод добавлено несколько новых режимов игры:

Several new game-mods are added:

* [ALL PICK] - Mod can be used in games with any number of players. Players ban and pick one handicap in random order. More players - more handicaps. Handicap options can be set different for players.

* [ALL RANDOM] - Mod can be used in games with any number of players. Handicaps and their options are selected randomly (and can be different for players). Number of enabled handicaps can be set in the lobby. 

* [MIRROR ALL PICK] - Same as **ALL PICK**, however handicap options are the same for all players.

* [MIRROR ALL RANDOM] - Same as **ALL RANDOM**, however handicap options are the same for all players.

* [MIRROR TOURNAMENT 2/2] - Mod can used only for games with two team (1x1, 2x2, 3x3, 4x4). Each team has a captain (this role is set in lobby). "First pick" is also set in lobby. This mod has only one "ban-pick" phase. Firstly every captain bans one handicap. Then every captain picks one handicap. Handicap options are the same for all players. 

* [MIRROR TOURNAMENT 2/2/2/2] - Same as **MIRROR TOURNAMENT 2/2**, however there are two "ban-pick" phases.

* [MIRROR TOURNAMENT 2/2/2/2/2/2] - Same as **MIRROR TOURNAMENT 2/2**, however there are three "ban-pick" phases. 

Pick and ban time can be set in lobby. It can be 15, 30, 45 or 60 seconds. This affects any mod with "phases".

* [DEFAULT] - Mod can be used in games with any number of players. This mod represents "Unfair SC2" as it was before 3.6. Only one player can select handicaps and their options. Handicap settings can be not same for players.

> All handicaps are available playing "DEFAULT" mod. Other mods have cut list of available handicaps.

* [ALL RACES](./handicaps/all-races.md)
    * [FEATURE] Zergs' Hatchery now is always placed at the player's start point if it's set to create main structures for all races.

* [ATTACK SPEED](./handicaps/attack-speed.md)
    * [BUGFIX] Now handicap is applied correctly for initial units.

* [BLOCKED RAMPS](./handicaps/blocked-ramps.md)
    * [FEATURE] Now blocks on ramps can be destroyable.

## v3.5

* [LIMITED WORKERS](./handicaps/limited-workers.md)
    * [BUGFIX/REFACTORING] Workers count now is calculated using data-editor and not triggers.

## v3.4

* [ALL UPGRADES](./handicaps/all-upgrades.md)
    * [BUGFIX] Upgrade "Evolve Microbial Shroud" is removed.

* [WORKERS BUILD PROCESS](./handicaps/workers-build-process.md)
    * [NEW] Handicap is added.

## v3.3

* [WALKING DEAD](./handicaps/walking-dead.md)
    * [BUGFIX] New vespene geysers are not created after destroying structures to collect vespene.
    * [BUGFIX] Zombies are created for player 15 and not 5. 

## v3.2

* [ATTACK SPEED](./handicaps/attack-speed.md)
    * [NEW] Handicap is added.

* [HP AND SHIELDS](./handicaps/hp-and-shields.md)
    * [NEW] Handicap is added.

* [LIMITED WORKERS](./handicaps/limited-workers.md)
    * [BUGFIX] Workers are no longer destroyed by players for whom this handicap is turned off (bug from 3.0).

## v3.1

* [NO LIMITS](./handicaps/no-limits.md)
    * [BUGFIX] Handicap now enabling correctly (bug from 3.0).

## v3.0

* [FEATURE] Handicap options are moved from lobby to ingame menu. Single player can be set in the lobby to work with handicaps setup after game starts.

* [BUGFIX] Recall is back for Nexuses.

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Clone for warping uit is created only after warp is completed.

* [EXTRA GAS](./handicaps/extra-gas.md)
    * [BUGFIX] Visual effect for vespene geysers is not visible throw the fog of war.

* [EXTRA UPGRADES](./handicaps/extra-upgrades.md)
    * [NEW] Handicap is added.

* [GAME SPEED](./handicaps/game-speed.md)
    * [NEW] Handicap is added.

* [LAST WILL](./handicaps/last-will.md)
    * [FEATURE] Added options 50%, 75% and 100% for the chance of the appearance of the ability.

* [NO RUSH](./handicaps/no-rush.md)
    * [FEATURE]  Options 7 and 10 minutes duration are added

* [RANDOM UNITS](./handicaps/random-units.md)
    * [BUGFIX] Widow mines now are created correctly.

* [REDUCE MINING](./handicaps/reduce-mining.md)
    * [BUGFIX] Visual effect is not shown on unit with resources if it die.

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [BUGFIX] Don't create new units from killed illusions.

* [TALANDAR](./handicaps/talandar.md)
    * [BUGFIX] Lift Off doesn't require any resources.

* [WALL](./handicaps/wall.md)
    * [FEATURE] Options 7m and 10m are added for wall life time.

## v2.41

* [BUGFIX] [#74 Невозможно создать игру формата больше 1х1](https://github.com/onechiporenko/unfair-sc2/issues/74)

* [APM KING](./handicaps/apm-king.md)
    * [NEW] Handicap is removed.

* [DARKNESS](./handicaps/darkness.md)
    * [FEATURE] Visual effect is added to units with Darkness effect.
    
* [FIGHT CLUB](./handicaps/fight-club.md)
    * [FEATURE] New option is added. Now it's possible to set fighting units "All but not workers"
    * [FEATURE] Visual effect is added for fighting units
    * [FEATURE] Units that doesn't use or provide supply now are excluded
    * [BUGFIX] Amount of fighting units now is equal to selected option (it was x2).
    
* [MACRO DEF](./handicaps/macro-def.md)
    * [BUGFIX] Ingame hint is fixed
    * [FEATURE] Hotkey "D" is added.
    * [FEATURE] "Macro Def" now works as "smart cast".
    
* [NUKED](./handicaps/nuked.md)
    * [FEATURE] Nuke overall time is increased on 3.5 seconds.
    
* [RIOT WORKERS](./handicaps/riot-workers.md)
    * [FEATURE] Visual effect is changed for riot workers.
    
* [VAMPIRISM](./handicaps/vampirism.md)
    * [REFACTORING] Animation now is created using effect and not trigger

## v2.40

* [RANDOM UNITS](./handicaps/random-units.md)
    * [NEW] Handicap is added.

## v2.39

* [RANDOM RALLY POINTS](./handicaps/random-rally-points.md)
    * [BUGFIX] Handicap won't be activated for 1st player when it's disabled.

## v2.38

* [FEATURE] Lobby options are sorted alphabetically.

* [BLOCKED RAMPS](./handicaps/blocked-ramps.md)
    * [BUGFIX] Description for lobby options is added.

* [CONTAMINATION](./handicaps/contamination.md)
    * [FEATURE] Option to set maximum contaminated structured in the same time is added.
    * [BUGFIX] "Contaminate" is used now for all selected structures and not 1 by 1.

* [DECIMATIO](./handicaps/decimatio.md)
    * [FEATURE] Added visual effect for units to be decimated.
    * [FEATURE] Decimatio doesn't work for structures, larvas, interceptors, units that not use and not provide supply, Overlords and Overseers.

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Viper's Abduct doesn't create copy of the pulled unit.
    * [BUGFIX] No more copies for Banelings and Archons.
    * [BUGFIX] Message about amount of resources for copies units now is shown again.

* [GOLD RUSH](./handicaps/gold-rush.md)
    * [FEATURE] Visual effect is added for replaced Mineral Fields and Vespene Geysers.

* [MOTHER CORE](./handicaps/mother-core.md)
    * [FEATURE] Visual effect is added for Mothership Core spawn.

* [PURE MINERALS](./handicaps/pure-minerals.md)
    * [FEATURE] Visual effect is added.

* [REDUCE MINING](./handicaps/reduce-mining.md)
    * [FEATURE] Visual effect is added.

* [RIOT WORKERS](./handicaps/riot-workers.md)
    * [FEATURE] Visual effect is added for riot workers.

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [FEATURE] Visual effect is added.

* [VAMPIRISM](./handicaps/vampirism.md)
    * [FEATURE] Vampirism now restore shields.

* [WALKING DEAD](./handicaps/walking-dead.md)
    * [BUGFIX] Zombies are not created after Viper's abduct.
    * [FEATURE] Visual effect for zombies is added.

## v2.37

* [CRITICAL STRIKE](./handicaps/critical-strike.md)
    * [FEATURE] Visual effect is added for critical strikes.

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] No more copies of Purification Nova.

* [IMMORTALS](./handicaps/immortals.md)
    * [NEW] Handicap is added.

* [NO SUPPLY](./handicaps/no-supply.md)
    * [BUGFIX]  Overseers don't produce supply.

* [RANDOM RALLY POINTS](./handicaps/random-rally-points.md)
    * [NEW] Handicap is added.

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [BUGFIX] Debug-message is not shown in the chat.

* [WALKING DEAD](./handicaps/walking-dead.md)
    * [BUGFIX] Don't create zombies from purification nova

## v2.36

* [ALIENS](./handicaps/aliens.md)
    * [BUGFIX] Broodlings are not spawn after killing unit that doesn't use or provide supply.

* [ALL RACES](./handicaps/all-races.md)
    * [FEATURE] Option to give main structures for all races is added

* [ALL UPGRADES](./handicaps/all-upgrades.md)
    * [BUGFIX] Upgrades "Seismic Spines", "Evolve Microbial Shroud" and "Rapid Reignition System" are added.

* [BLOCKED RAMPS](./handicaps/blocked-ramps.md)
    * [NEW] Handicap is added

* [MACRO DEF](./handicaps/macro-def.md)
    * [REGRESSION] "Macro Def" state is saved on zerg structures morph and terran CC's upgrades.

## v2.35

* [ALIENS](./handicaps/aliens.md)
    * [BUGFIX] Number of Broodlings for options "1" - "10" now is equal to value for player who lost the unit and not who killed it.
    
* [MOTHER CORE](./handicaps/mother-core.md)
    * [REGRESSION] First Mothership Core is spawn after 150 seconds and not 12.
    
## v2.34

* [FAIR MACRO](./handicaps/fair-macro.md)
    * [NEW] Handicap is added

* [FAIR PLAY](./handicaps/fair-play.md)
    * [REFACTORING] Now aura "Fair Cannon" disallow attack and not reduce damage to 0.

* [MACRO DEF](./handicaps/macro-def.md)
    * [FEATURE] "Macro Def" now is not a "single-shot" ability. Its cooldown is 20+ minutes. Cooldown is own for each structure.
    * [FEATURE] "Macro Def" state is saved on zerg structures morph and terran CC's upgrades.
    * [FEATURE] Macro Def сохраняется при мутации Инкубатора в Логово и Логова в Улей.
    * [FEATURE] Given Spine Crawlers, Spore Crawlers and Widow Mines can be "unborrowed" right after they are placed.
    * [FEATURE] Sensor Tower now is placed near the CC and not inside it.

* [NO RUSH](./handicaps/no-rush.md)
    * [REFACTORING] Now effect is used to block enemies buildings.
    * [REFACTORING] "No attack" aura now blocks attacks and not set damage 0.

* [TECH TREE RESTRICTIONS](./handicaps/tech-tree-restrictions.md)
    * [NEW] Handicap is added

## v2.33

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Tactical Jump doesn't create copy of Battlecruiser

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [BUGFIX] Repear's KD8 doesn't create a new unit

## v2.32

* [ALL UPGRADES](./handicaps/all-upgrades.md)
    * [BUGFIX] Upgrades "Mag-Field Accelerator" and "Enhanced Shockwaves" are added.

* [DARKNESS](./handicaps/darkness.md)
    * [BUGFIX] Reduced vision range is applied only for selected players and not for all.

## v2.31

* [GRAPPLE](./handicaps/grapple.md)
    * [BUGFIX] Grapple-button is visible again.

## v2.30

* [APM KING](./handicaps/apm-king.md)
    * [FEATURE] Max APM option is added.

* [FAIR PLAY](./handicaps/fair-play.md)    
    * [BUGFIX] Now all Nexuses have aura "Fair Cannons"

## v2.29

* [AIR GROUND WEAPON](./handicaps/air-ground-weapon.md)
    * [BUGFIX] Colossuses now hits air units too (previously there was only an animation of attack without any damage)

* [APM KING](./handicaps/apm-king.md)
    * [NEW] Handicap is added

* [BLINK WARS](./handicaps/blink-wars.md)
    * [BUGFIX] Overseers now also have Blink.

* [CHARGE WARS](./handicaps/charge-wars.md)
    * [NEW] Handicap is added

* [FAIR PLAY](./handicaps/fair-play.md)
    * [NEW] Handicap is added

* [FIGHT CLUB](./handicaps/fight-club.md)
    * [NEW] Handicap is added

* [INSTANT PRODUCTION](./handicaps/instant-production.md)
    * [BUGFIX] Now morphing of zerg structures, terran CC's upgrades and addon building take a few seconds.

* [QUEEN](./handicaps/queen.md)
    * [NEW] Handicap is added

* [RIOT WORKERS](./handicaps/riot-workers.md)
    * [BUGFIX] Fixed amount of riot workers when option 100% is selected
    * [FEATURE] Riot SCV now stop construction.

## v2.28

* [AIR GROUND WEAPON](./handicaps/air-ground-weapon.md)
    * [FEATURE] All except Disruptors can attack air and ground units
    
* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Adept's Shade doesn't create second Adept

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [BUGFIX] Adept's phase shift doesn't create a new unit
    * [BUGFIX] Friendly fire doesn't create a new unit

* [WALKING DEAD](./handicaps/walking-dead.md)
    * [BUGFIX] Don't create zombies from phase shift
    * [FEATURE] It's possible to set spawn of zombie-structures

## v2.27

* [ALL RACES](./handicaps/all-races.md)
    * [BUGFIX] Now workers are not killed when the game begin

* [ALL UPGRADES](./handicaps/all-upgrades.md)
    * [BUGFIX] Upgrade from campaign is removed. Now CCs have 10 slots and not 15.

* [EXTRA GAS](./handicaps/extra-gas.md)
    * [BUGFIX] Now works with rich geysers.

* [FREE WORKERS](./handicaps/free-workers.md)
    * [BUGFIX] Ingame hint is fixed.

* [INSTANT PRODUCTION](./handicaps/instant-production.md)
    * [BUGFIX] Now ingame hint is shown only once.

* [NO ARMY CONTROL](./handicaps/no-army-control.md)
    * [BUGFIX] Ingame hint is fixed.

* [TALANDAR](./handicaps/talandar.md)
    * [BUGFIX] Short description is added.

## v2.26

* [MOTHER CORE](./handicaps/mother-core.md)
    * [FEATURE]	Now ping on minimap is shown when Mothership Core is spawn.
    * [FEATURE]	Timer with countdown is shown for player when his Mothership Core is lost.

* [WALKING DEAD](./handicaps/walking-dead.md)
    * [NEW] Handicap is added

## v2.23

* [INSTANT PRODUCTION](./handicaps/instant-production.md)
    * [NEW] Handicap is added
    
* [TALANDAR](./handicaps/talandar.md)
    * [NEW] Handicap is added

## v2.22

* [ALL RACES](./handicaps/all-races.md)
    * [NEW] Handicap is added

## v2.21

* [NO ARMY CONTROL](./handicaps/no-army-control.md)
    * [NEW] Handicap is added

## v2.20

* [FEATURE] Добавлена игровая подсказка с описанием выбранных настроек для всех включенных гандикапов. Выводится, если гандикап включен хотя бы для одного игрока.

## v2.19

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [BUGFIX] "Catched Soul" now is called "Caught Soul". 

## v2.18

* [AIR GROUND WEAPON](./handicaps/air-ground-weapon.md)
    * [BUGFIX] High Templars now also can attack air units.

## v2.17

* [AIR GROUND WEAPON](./handicaps/air-ground-weapon.md)
    * [BUGFIX] Handicap is turned of by default.

## v2.16

* [AIR GROUND WEAPON](./handicaps/air-ground-weapon.md)
    * [NEW] Handicap is added

## v2.14

* [ALL UPGRADES](./handicaps/all-upgrades.md)
    * [FEATURE] Upgrade "Anabolic Synthesis" is added.

## v2.11

* [SOULS CATCHER](./handicaps/souls-catcher.md)
     * [BUGFIX] Tactical Jump won't create a new Battlecruiser

## v2.9

* [BOUNTY](./handicaps/bounty.md)
    * [BUGFIX] Table will all player now is shown for all spectators. 

* [DECIMATIO](./handicaps/decimatio.md)
    * [BUGFIX] Table will all player now is shown for all spectators.

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Table will all player now is shown for all spectators.

* [MINES](./handicaps/mines.md)
    * [BUGFIX] Table will all player now is shown for all spectators.

* [ORDER COSTS](./handicaps/order-costs.md)
    * [BUGFIX] Table will all player now is shown for all spectators.

## v2.6

* [DECIMATIO](./handicaps/decimatio.md)
    * [BUGFIX] First Decimatio now again at 3:30

## v2.4

* [CRITICAL MISS](./handicaps/critical-miss.md)
    * [FEATURE]	Critical miss also hit attacker (sometimes not)

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [FEATURE]	New units now are 85% of their original size.

## v2.3

* [BERSERKER'S BLOOD](./handicaps/berserkers-blood.md)
    * [REFACTORING]	Validators are used instead of triggers to add behavior to units.
    * [FEATURE]	Description is updated.

* [CHAT](./handicaps/chat.md)
    * [BUGFIX] No more messages about cancel Archons morphing.
    
* [CRITICAL STRIKE](./handicaps/critical-strike.md)
    * [FEATURE]	Now it's possible to set chance and damage multiplayer for each player separately.
    * [REFACTORING]	Now only 1 behavior is used and not 5.

* [DARKNESS](./handicaps/darkness.md)
    * [FEATURE]	Description for Darkness effect is updated.

* [MOVE SPEED](./handicaps/move-speed.md)
    * [FEATURE]	Ingame hint is updated.

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [FEATURE]	New description is added to the ingame hint.

## v2.2

* [CHAT](./handicaps/chat.md)
    * [BUGFIX] No more messages about warping units.
    * [BUGFIX] Messages are not posted if handicap Chat is disabled.

## v2.1

* [RIOT WORKERS](./handicaps/riot-workers.md)
    * [NEW] Handicap is added

## v2.0

* [ALIENS](./handicaps/aliens.md)
    * [BUGFIX] Number of created Broodlings now is taken from correct player.
    * [BUGFIX] Now killed Overseers and Overlords also spawn Broodlings.
    * [FEATURE] Now it's possible to set amount of created Broodlings equal to unit's supply limit (but not less than 1).
    * [FEATURE] Created Broodlings attack a point where unit-killer is.
    * [REFACTORING] Lobby options refactoring.

* [BOUNTY](./handicaps/bounty.md)
    * [NEW] Handicap is added

* [CHAT](./handicaps/chat.md)
    * [NEW] Handicap is added

* [CRITICAL STRIKE](./handicaps/critical-strike.md)
    * [REFACTORING] Number of events is reduced.
    
* [DARKNESS](./handicaps/darkness.md)
    * [REFACTORING] Number of event is reduced.

* [DECIMATIO](./handicaps/decimatio.md)
    * [FEATURE] Delay between Decimatio waves now can be set to 35, 40, 45, 50, 55 or 60 seconds.
    * [BUGFIX] Decimatio now triggers only once every wave point and not twice.
    * [FEATURE] Every player have a small block of text at the top left corner with amount of lost resources.
    * [FEATURE] Table will all player now is shown for all spectators.
    * [REFACTORING] Lobby options refactoring.

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Copy of Overlords now are created too.
    * [FEATURE] Unit's copy now has same order as original one.
    * [FEATURE] Every player see amount of "saved" resources at the top left corner.
    * [FEATURE] Tablew with resources for all players is shown for spectators.
    * [REFACTORING] Lobby options refactoring.

* [ENERGY](./handicaps/energy.md)
    * [NEW] Handicap is added

* [FREE WORKERS](./handicaps/free-workers.md)
    * [FEATURE] Number of workers is shown at the top left corner.
    * [REFACTORING] Lobby options refactoring.

* [LAST WILL](./handicaps/last-will.md)
    * [REFACTORING] Lobby options refactoring.

* [LIMITED WORKERS](./handicaps/limited-workers.md)
    * [NEW] Handicap is added

* [MINES](./handicaps/mines.md)
    * [FEATURE] Now it's possible to set safe-zone radius for each player (50 by default).
    * [FEATURE] Now it's possible to set spawn of extra Mines after 6:00.
    * [FEATURE] Show information about lost resources for players and spectators.
    * [REFACTORING] Lobby options refactoring.

* [MOVE SPEED](./handicaps/move-speed.md)
    * [REFACTORING] Only single effect is used instead of five.

* [NO FLY](./handicaps/no-fly.md)
    * [NEW] Handicap is added

* [NO SUPPLY](./handicaps/no-supply.md)
    * [REFACTORING] Refactored to work with data-editor and not triggers.

* [NUKED](./handicaps/nuked.md)
    * [NEW] Handicap is added

* [ORDER COSTS](./handicaps/order-costs.md)
    * [FEATURE] Option "Charity" is added.
    * [FEATURE] Amount of spent on orders resources is shown for players and spectators.
    * [REFACTORING] Lobby options refactoring.

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [NEW] Handicap is added

* [TEMPORAL FIELDS](./handicaps/temporal-fields.md)
    * [NEW] Handicap is added

* [VAMPIRISM](./handicaps/vampirism.md)
    * [REFACTORING] Lobby options refactoring.

* [WALL](./handicaps/wall.md)
    * [BUGFIX] Wall now attacks from max allowed range.

* [ZOMBIES](./handicaps/zombies.md)
    * [FEATURE] Option to select "upgade" waves is added.

* [ZOOM](./handicaps/zoom.md)
    * [NEW] Handicap is added

## v1.37

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Sentries won't create a real unit together with illusion.

## v1.35

* [CONTAMINATION](./handicaps/contamination.md)
    * [BUGFIX] Stasis Ward and Auto-Turret now can't be "contaminated".
    
* [DECIMATIO](./handicaps/decimatio.md)
    * [FEATURE] Ignores larvas, Overlords and Overseers. However counts Transport Overlords.

* [FREE WORKERS](./handicaps/free-workers.md)
    * [NEW] Handicap is added

* [MINES](./handicaps/mines.md)
    * [NEW] Handicap is added

* [ORDER COSTS](./handicaps/order-costs.md)
    * [BUGFIX] Исправлен подсчет потерянных на приказах ресурсов.

* [ZOMBIES](./handicaps/zombies.md)
    * [BUGFIX] Zombies won't spawn on Stasis Wards and Auto-Turrets.

## v1.34

* [CAMERA](./handicaps/camera.md)
    * [BUGFIX] Screen turning off before camera rotation is removed.

## v1.33

* [WALL](./handicaps/wall.md)
    * [BUGFIX] Fixed wall direction when some diagonal option is selected.
    
* [ZOMBIES](./handicaps/zombies.md)
    * [BUGFIX] Option "Zombies Start Delay" is hidden until "Use Zombies" is not selected.

## v1.32

* [CAMERA](./handicaps/camera.md)
    * [NEW] Handicap is added

* [CRITICAL STRIKE](./handicaps/critical-strike.md)
    * [NEW] Handicap is added

* [DECIMATIO](./handicaps/decimatio.md)
    * [FEATURE] Visual effect is added to killed units.
    * [FEATURE] Countdown timer is show for each Decimatio wave.

* [NO LIMITS](./handicaps/no-limits.md)
    * [NEW] Handicap is added
    
* [ZOMBIES](./handicaps/zombies.md)
    * [FEATURE] Option "Zombies Start Delay" is added.
    * [FEATURE] Option "Zombies Waves Delay" is added.
    * [FEATURE] Voice-countdown "3..2..1" is replaced with visual countdown bar (similar to one shown in the co-op mission Cradle of Death).

## v1.31

* [DECIMATIO](./handicaps/decimatio.md)
    * [NEW] Handicap is added

* [GOLD RUSH](./handicaps/gold-rush.md)
    * [FEATURE] Vespene Geysers now are replaced with Rich Vespene Geysers.
    * [BUGFIX] Now all types of mineral fields are replaced correctly.

* [NO RUSH](./handicaps/no-rush.md)
    * [FEATURE] No enemy buildings are allowed in the safe-zone.

* [PURE MINERALS](./handicaps/pure-minerals.md)
    * [BUGFIX] Now all types of mineral fields are replaced correctly.

* [WALL](./handicaps/wall.md)
    * [FEATURE] Wall is visible for all players.
    * [FEATURE] Wall can be cross ("+" or "x").
