# Changelog

## v2.37

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Больше не создается дубль Сферы Очищения.

## v2.36

* [ALIENS](./handicaps/aliens.md)
    * [BUGFIX] Брудлинги не создаются от других брудлингов, саранчидов и прочих юнитов, которые не занимают или не дают лимита.

* [ALL RACES](./handicaps/all-races.md)
    * [FEATURE] Добавлена опции игрока, указывающая, надо ли создать для него в начале игры главные здания других рас

* [ALL UPGRADES](./handicaps/all-upgrades.md)
    * [BUGFIX] Добавлены улучшения "Сейсмические шипы", "Микробная завеса" и "Поточные турбины"

* [BLOCKED RAMPS](./handicaps/blocked-ramps.md)
    * [NEW] Гандикап добавлен

* [MACRO DEF](./handicaps/macro-def.md)
    * [REGRESSION] Macro Def сохраняется при "мутации" главных зданий терранов и зергов.

## v2.35

* [ALIENS](./handicaps/aliens.md)
    * [BUGFIX] Кол-во создаваемых брудлингов для опций "1" - "10" соответствует выбранному значению для игрока потерявшего юнита, а не убившего его.
    
* [MOTHER CORE](./handicaps/mother-core.md)
    * [REGRESSION] Первый Mother Core появляется через 150 секунд от начала игры, а не 12.
    
## v2.34

* [FAIR MACRO](./handicaps/fair-macro.md)
    * [NEW] Гандикап добавлен

* [FAIR PLAY](./handicaps/fair-play.md)
    * [REFACTOR] Теперь аура Fair Cannon вообще не дает атаковать, а не просто обнуляет урон.

* [MACRO DEF](./handicaps/macro-def.md)
    * [FEATURE] Macro Def теперь не "однозарядная". Ее время востановления - 20+ минут. Оно индивидуально для каждого главного здания.
    * [FEATURE] Macro Def сохраняется при преобразовании Командного Центра в Станцию Наблюдения или Планетарную Крепость.
    * [FEATURE] Macro Def сохраняется при мутации Инкубатора в Логово и Логова в Улей.
    * [FEATURE] Ползучие споровики, Ползучие плеточники и Мины можно перекапывать сразу после их появления.
    * [FEATURE] Радарная вышка теперь появляется рядом с главным зданием, а не "внутри" него.

* [NO RUSH](./handicaps/no-rush.md)
    * [REFACTOR] Запрет на постройку теперь сделан через эффект, а не триггер.
    * [REFACTOR] Теперь аура No Attack вообще не дает атаковать, а не просто обнуляет урон.

* [TECH TREE RESTRICTIONS](./handicaps/tech-tree-restrictions.md)
    * [NEW] Гандикап добавлен

## v2.33

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Тактический Скачок Крейсера больше не создает второй Крейсер

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [BUGFIX] Отбрасывание взрывчаткой KD8 (головорез) не создает "душу"

## v2.32

* [ALL UPGRADES](./handicaps/all-upgrades.md)
    * [BUGFIX] Добавлены улучшения "Ускоритель магнитного поля" и "Усиленные волны"

* [DARKNESS](./handicaps/darkness.md)
    * [BUGFIX] Урезанный обзор юнитов теперь применяется согласно выбранных опций игры, а не для всех игроков.

## v2.31

* [GRAPPLE](./handicaps/grapple.md)
    * [BUGFIX] Кнопка способности Grapple снова видима у бейлингов.

## v2.30

* [APM KING](./handicaps/apm-king.md)
    * [FEATURE] Добавлена опция Max APM, которая указывает на максимально допустимый APM игрока. Если APM игрока окажется выше, то его выбранным юнитам также будет нанесен урон.

* [FAIR PLAY](./handicaps/fair-play.md)    
    * [BUGFIX] Теперь аура "Fair Cannons (Aura)" дается всем Нексусам после завершения их постройки.

## v2.29

* [AIR GROUND WEAPON](./handicaps/air-ground-weapon.md)
    * [BUGFIX] Колоссы теперь наносят урон по воздушным юнитам (ранее была только анимация атаки, но без урона)

* [APM KING](./handicaps/apm-king.md)
    * [NEW] Гандикап добавлен

* [BLINK WARS](./handicaps/blink-wars.md)
    * [BUGFIX] У Владык теперь есть Скачок

* [CHARGE WARS](./handicaps/charge-wars.md)
    * [NEW] Гандикап добавлен

* [FAIR PLAY](./handicaps/fair-play.md)
    * [NEW] Гандикап добавлен

* [FIGHT CLUB](./handicaps/fight-club.md)
    * [NEW] Гандикап добавлен

* [INSTANT PRODUCTION](./handicaps/instant-production.md)
    * [BUGFIX] Мутация строений зергов, постройка пристроек для зданий терранов и превращение Командного Центра в Орбитальную Станцию или Планетарную Крепость теперь тоже происходят за пару секунд.

* [QUEEN](./handicaps/queen.md)
    * [NEW] Гандикап добавлен

* [RIOT WORKERS](./handicaps/riot-workers.md)
    * [BUGFIX] Riot Workers 100% теперь выводит бунтовать 100% рабочих, а не 25%
    * [FEATURE] Теперь бунтующие КСМ останавливают строительство (здание можно продолжить строить любым рабочим как обычно)

## v2.28

* [AIR GROUND WEAPON](./handicaps/air-ground-weapon.md)
    * [FEATURE] Все, кроме Дестабилизаторов, наносят урон по земле и воздуху
    
* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Не создает копию тени адепта

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [BUGFIX] Тень адепта при исчезновении не создает "душу"
    * [BUGFIX] "Души" не появляются, если игрок добил своего юнита

* [WALKING DEAD](./handicaps/walking-dead.md)
    * [BUGFIX] Не создавать зомби от тени адепта
    * [FEATURE] Добавлена опция лобби, указывающая надо ли создавать зомби из уничтоженных зданий

## v2.27

* [ALL RACES](./handicaps/all-races.md)
    * [BUGFIX] Исправлена ошибка из-за которой в начале игры уничтожались все рабочие

* [ALL UPGRADES](./handicaps/all-upgrades.md)
    * [BUGFIX] У терранов убрано улучшение из кампании. Теперь вместимость Командных Центров 10, а не 15.

* [EXTRA GAS](./handicaps/extra-gas.md)
    * [BUGFIX] Теперь корректно работает и с богатыми гейзерами

* [FREE WORKERS](./handicaps/free-workers.md)
    * [BUGFIX] Исправлена игровая подсказка.

* [INSTANT PRODUCTION](./handicaps/instant-production.md)
    * [BUGFIX] Игровая подсказка выводится только один раз.

* [NO ARMY CONTROL](./handicaps/no-army-control.md)
    * [BUGFIX] Исправлена игровая подсказка.

* [TALANDAR](./handicaps/talandar.md)
    * [BUGFIX] В лобби игры теперь отображается краткое описание данного гандикапа.

## v2.26

* [MOTHER CORE](./handicaps/mother-core.md)
    * [FEATURE]	Пинг на миникарте, когда появляется новое Ядро Материнского Корабля.
    * [FEATURE]	Теперь после уничтожения Ядра Материнского Корабля выводится таймер с отсчетом до момента, когда игроку будет данновый МамаКор.

* [WALKING DEAD](./handicaps/walking-dead.md)
    * [NEW] Гандикап добавлен

## v2.23

* [INSTANT PRODUCTION](./handicaps/instant-production.md)
    * [NEW] Гандикап добавлен
    
* [TALANDAR](./handicaps/talandar.md)
    * [NEW] Гандикап добавлен

## v2.22

* [ALL RACES](./handicaps/all-races.md)
    * [NEW] Гандикап добавлен

## v2.21

* [NO ARMY CONTROL](./handicaps/no-army-control.md)
    * [NEW] Гандикап добавлен

## v2.20

* [FEATURE] Добавлена игровая подсказка с описанием выбранных настроек для всех включенных гандикапов. Выводится, если гандикап включен хотя бы для одного игрока.

## v2.19

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [BUGFIX] "Catched Soul" теперь называется "Caught Soul". 

## v2.18

* [AIR GROUND WEAPON](./handicaps/air-ground-weapon.md)
    * [BUGFIX] Высшие Тамплиеры теперь тоже атакуют по воздуху.

## v2.17

* [AIR GROUND WEAPON](./handicaps/air-ground-weapon.md)
    * [BUGFIX] Выключено по умолчанию.

## v2.16

* [AIR GROUND WEAPON](./handicaps/air-ground-weapon.md)
    * [NEW] Гандикап добавлен

## v2.14

* [ALL UPGRADES](./handicaps/all-upgrades.md)
    * [FEATURE] Улучшение "Anabolic Synthesis" ("Анаболитический Синтез") теперь тоже дается сразу.

## v2.11

* [SOULS CATCHER](./handicaps/souls-catcher.md)
     * [BUGFIX] Тактический Скачок Крейсера больше не создает еще один Крейсер

## v2.9

* [BOUNTY](./handicaps/bounty.md)
    * [BUGFIX] Общая таблица теперь снова корректно отображается для зрителей 

* [DECIMATIO](./handicaps/decimatio.md)
    * [BUGFIX] Общая таблица теперь снова корректно отображается для зрителей

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Общая таблица теперь снова корректно отображается для зрителей

* [MINES](./handicaps/mines.md)
    * [BUGFIX] Общая таблица теперь снова корректно отображается для зрителей

* [ORDER COSTS](./handicaps/order-costs.md)
    * [BUGFIX] Общая таблица теперь снова корректно отображается для зрителей

## v2.6

* [DECIMATIO](./handicaps/decimatio.md)
    * [BUGFIX]	Первая децимация снова на 3:30

## v2.4

* [CRITICAL MISS](./handicaps/critical-miss.md)
    * [FEATURE]	Критический промах теперь наносит урон атакующему (иногда не срабатывает). Урон "по себе" - это показатель атаки первого оружия без учета бонусов или штрафов. Например, для Безсмертного - это 20, а для Урагана - 30.

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [FEATURE]	Полученные юниты теперь размером 85% от оригинального юнита.

## v2.3

* [BERSERKER'S BLOOD](./handicaps/berserkers-blood.md)
    * [REFACTORING]	Вместо триггеров для добавления алгоритмов теперь используются валидаторы.
    * [FEATURE]	Обновлено описание для всплывающей подсказки Berserker's Blood.

* [CHAT](./handicaps/chat.md)
    * [BUGFIX]	Больше не выводится сообщение об отмене морфа архонов.
    
* [CRITICAL STRIKE](./handicaps/critical-strike.md)
    * [FEATURE]	Каждому игроку отдельно можно задать размер и вероятность критического урона.
    * [REFACTORING]	Вместо пяти алгоритмов теперь используется один.

* [DARKNESS](./handicaps/darkness.md)
    * [FEATURE]	Обновлено описание для всплывающей подсказки эффекта Darkness.

* [MOVE SPEED](./handicaps/move-speed.md)
    * [FEATURE]	Обновлено описание для всплывающей подсказки.

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [FEATURE]	Добавлено нормальное описание для всплывающей подсказки Catched Soul.

## v2.2

* [CHAT](./handicaps/chat.md)
    * [BUGFIX] Варп юнитов больше не выводится как сообщение о постройке.
    * [BUGFIX] Сообщения об улучшениях теперь не выводятся, если Chat не включен.

## v2.1

* [RIOT WORKERS](./handicaps/riot-workers.md)
    * [NEW] Гандикап добавлен

## v2.0

* [ALIENS](./handicaps/aliens.md)
    * [BUGFIX] Исправлена ошибка генерации брудлингов. Кол-во создаваемых брудлингов бралось не у нужного игрока.
    * [BUGFIX] Теперь брудлинги создаются и от Надзирателей и Владык.
    * [FEATURE] Можно указать, чтоб кол-во создаваемых брудлингов зависело от занимаемого лимита убитого юнита (но не меньше 1).
    * [FEATURE] Созданные брудлинги по умолчанию атакуют ту точку, откуда был нанесен смертельный урон.
    * [REFACTORING] Обработка и хранение опций лобби.

* [BOUNTY](./handicaps/bounty.md)
    * [NEW] Гандикап добавлен

* [CHAT](./handicaps/chat.md)
    * [NEW] Гандикап добавлен

* [CRITICAL STRIKE](./handicaps/critical-strike.md)
    * [REFACTORING] Уменьшено кол-во события для добавления алгоритма Critical Strike.
    
* [DARKNESS](./handicaps/darkness.md)
    * [REFACTORING] Уменьшено кол-во событий для добавления ограничения обзора юнитам.

* [DECIMATIO](./handicaps/decimatio.md)
    * [FEATURE] Добавлены опции 35, 40, 45, 50, 55 и 60 для времени задержки между децимациями.
    * [BUGFIX] Исправлена ошибка из-за которой Децимация срабатывала два раза.
    * [FEATURE] Выводит игроку общее кол-во потерянных на децимации ресурсов.
    * [FEATURE] Зрителям выводится таблица потерянных ресурсов.
    * [REFACTORING] Обработка и хранение опций лобби.

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Исправлена ошибка из-за которой не создавался второй Надзиратель.
    * [FEATURE] Созданный юнит получает такой же приказ, как и оригинальный.
    * [FEATURE] Игрок видит кол-во ресурсов, которые бы он потратил на юнитов, полученных "за просто так".
    * [FEATURE] Зрителям выводится таблица "не потраченных" ресурсов.
    * [REFACTORING] Обработка и хранение опций лобби.

* [ENERGY](./handicaps/energy.md)
    * [NEW] Гандикап добавлен

* [FREE WORKERS](./handicaps/free-workers.md)
    * [FEATURE] Кол-во рабочих теперь выводится в левом верхнем углу.
    * [REFACTORING] Обработка и хранение опций лобби.

* [LAST WILL](./handicaps/last-will.md)
    * [REFACTORING] Обработка и хранение опций лобби.

* [LIMITED WORKERS](./handicaps/limited-workers.md)
    * [NEW] Гандикап добавлен

* [MINES](./handicaps/mines.md)
    * [FEATURE] Для каждого игрока можно задать свой радиус без мин (50 по умолчанию).
    * [FEATURE] Добавлено две новых опции, с помощью которых можно указать частоту и кол-во новых мин, создаваемых на карте после 6:00.
    * [FEATURE] Выводит игроку общее кол-во ресурсов, потерянных на минах.
    * [FEATURE] Выводит зрителям таблицу с потерями на минах всех игроков.
    * [REFACTORING] Обработка и хранение опций лобби.

* [MOVE SPEED](./handicaps/move-speed.md)
    * [REFACTORING] Вместо пяти эффектов теперь один. 

* [NO FLY](./handicaps/no-fly.md)
    * [NEW] Гандикап добавлен

* [NO SUPPLY](./handicaps/no-supply.md)
    * [REFACTORING] Теперь работает через Data-editor, а не через триггеры.

* [NUKED](./handicaps/nuked.md)
    * [NEW] Гандикап добавлен

* [ORDER COSTS](./handicaps/order-costs.md)
    * [FEATURE] Добавлена опция "Charity". Ресурсы, забранные у игрока за приказы, будут отданы другому игроку (выбирается случайным образом, если игроков больше 2). Может дать ресурсы другому игроку, у которого тоже включен Order Costs.
    * [FEATURE] Выводит игроку общее кол-во ресурсов, потерянных на отдаче приказов.
    * [FEATURE] Зрителям выводится таблица с потерями ресурсов всеми игроками на отдаче приказов.
    * [REFACTORING] Обработка и хранение опций лобби.

* [SOULS CATCHER](./handicaps/souls-catcher.md)
    * [NEW] Гандикап добавлен

* [TEMPORAL FIELDS](./handicaps/temporal-fields.md)
    * [NEW] Гандикап добавлен

* [VAMPIRISM](./handicaps/vampirism.md)
    * [REFACTORING] Обработка и хранение опций лобби.

* [WALL](./handicaps/wall.md)
    * [BUGFIX] Исправлено оружие Планетарных Крепостей в стене. Теперь они стреляют с максимально доступного расстояния.

* [ZOMBIES](./handicaps/zombies.md)
    * [FEATURE] Добавлена опция, указывающая на каких волнах у зомби появляются улучшения (варианты - 7/14/21, 8/16/24, 9/18/27, 10/20/30).

* [ZOOM](./handicaps/zoom.md)
    * [NEW] Гандикап добавлен

## v1.37

* [DOUBLE](./handicaps/double.md)
    * [BUGFIX] Часовые больше не создают реально юнита вместе с иллюзией.

## v1.35

* [CONTAMINATION](./handicaps/contamination.md)
    * [BUGFIX] Не работает на Стазисные ловушки и туррели Воронов.
    
* [DECIMATIO](./handicaps/decimatio.md)
    * [FEATURE] Не считает личинки, обычных Надзирателей и Владык. Но все равно считает транспортных надзирателей.

* [FREE WORKERS](./handicaps/free-workers.md)
    * [NEW] Гандикап добавлен

* [MINES](./handicaps/mines.md)
    * [NEW] Гандикап добавлен

* [ORDER COSTS](./handicaps/order-costs.md)
    * [BUGFIX] Исправлен подсчет потерянных на приказах ресурсов.

* [ZOMBIES](./handicaps/zombies.md)
    * [BUGFIX] Зомби не появляются на Стазисных ловушках и туррелях Воронов.

## v1.34

* [CAMERA](./handicaps/camera.md)
    * [BUGFIX] Убрано "затухание" экрана перед поворотом камеры. Ранее экран "затухал" у всех игроков (даже у тех, для кого гандикап Camera не включен).

## v1.33

* [WALL](./handicaps/wall.md)
    * [BUGFIX] Диагональные стенки теперь создаются соответственно значению опции лобби "Wall Direction".
    
* [ZOMBIES](./handicaps/zombies.md)
    * [BUGFIX] Опция лобби "Zombies Start Delay" теперь скрыта пока не выбрана опция "Use Zombies".

## v1.32

* [CAMERA](./handicaps/camera.md)
    * [NEW] Гандикап добавлен

* [CRITICAL STRIKE](./handicaps/critical-strike.md)
    * [NEW] Гандикап добавлен

* [DECIMATIO](./handicaps/decimatio.md)
    * [FEATURE] Для умирающих юнитов добавлен визуальный эффект.
    * [FEATURE] Для каждой волны Децимации выводится таймер с обратным отсчетом.

* [NO LIMITS](./handicaps/no-limits.md)
    * [NEW] Гандикап добавлен
    
* [ZOMBIES](./handicaps/zombies.md)
    * [FEATURE] Добавлена опция лобби "Zombies Start Delay".
    * [FEATURE] Добавлена опция лобби "Zombies Waves Delay".
    * [FEATURE] Вместо голосового оповещения "3..2..1" выводится шкала обратного отсчета (по аналогии с миссией кооперативного режима Cradle of Death).

## v1.31

* [DECIMATIO](./handicaps/decimatio.md)
    * [NEW] Гандикап добавлен

* [GOLD RUSH](./handicaps/gold-rush.md)
    * [FEATURE] Теперь вместо обычных веспеновых гейзеров создает богатые.
    * [BUGFIX] Теперь корректно обрабатывает все типы минеральных кристаллов.

* [NO RUSH](./handicaps/no-rush.md)
    * [FEATURE] В зоне "безопасности" других игроков запрещено строить здания.

* [PURE MINERALS](./handicaps/pure-minerals.md)
    * [BUGFIX] Теперь корректно обрабатывает все типы минеральных кристаллов.

* [WALL](./handicaps/wall.md)
    * [FEATURE] Стена видима для всех игроков.
    * [FEATURE] Стена может быть крестовой ("+" или "х").