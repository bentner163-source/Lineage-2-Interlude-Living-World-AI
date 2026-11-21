# Living World 1.0.1

[Русский](#русский) · [English](#english)

## Русский

**Living World** — одиночная игра в Lineage II Interlude, в которой мир живёт и без других игроков. Вы создаёте свой мир на своём компьютере, выбираете скорость развития и количество жителей и играете в удобном темпе. Рядом с вами охотятся, торгуют, учатся, заводят друзей и кланы персонажи, которыми управляет компьютер. У каждого свой характер, привычки, друзья и цели. Мир и персонажи сохраняются между запусками.

Игровой клиент в комплект не входит: нужна ваша собственная копия Lineage II Interlude.

### Установка

1. Скачайте `LivingWorld-Setup.exe` из раздела [Releases](https://github.com/bentner163-source/Lineage-2-Interlude-Living-World-AI/releases/tag/stable-v1.0.1) и запустите его. Если Windows покажет предупреждение SmartScreen, нажмите «Подробнее» → «Выполнить в любом случае».
2. В окне установщика выберите папку (подойдёт предложенная), при желании оставьте галочку «Создать ярлыки» и нажмите «Установить». Установка занимает несколько минут.
3. Нажмите «Готово» — Living World запустится. Создайте или выберите мир.
4. При первом запуске укажите файл `system\L2.exe` из вашей копии Interlude и введите игровой логин и пароль в окне игры.

Чтобы рядом появились персонажи под управлением компьютера, задайте их количество в окне «Население ИИ…» при остановленном мире (ноль — мир без них). Закрывая игру, выйдите из неё и нажмите «Остановить» до закрытия лаунчера.

После установки версии 1.0.1 следующие обновления доступны через «Проверить обновления». Лаунчер скачивает только изменившиеся компоненты. Перед применением обновления остановите мир.

### Перед запуском мира

Внимательно изучите настройки, когда создаёте мир. Выберите его возраст, скорость развития, число ИИ-персонажей и доступные сервисы. Эти параметры определяют, каким будет мир при первом запуске.

ИИ-персонажами управляет игра. За ними нет живых игроков. Их поведение может быть непредсказуемым, а привычные игровые действия иногда выполняются с ошибками. Living World продолжает дорабатываться.

### Как это выглядит

Вы входите в мир, а он уже идёт своим чередом. У дороги стоят личные магазины, в городе кто-то ищет группу на охоту, а на поляне двое друзей охотятся вместе и пишут в чат, как прошёл день. Один из жителей давно копит на новое снаряжение и всем об этом рассказывает, другой устал и сел отдохнуть («брб»), третий зовёт в клан. Вы можете просто смотреть, можете вступить в группу, торговать, дружить, ссориться и воевать — мир реагирует на ваши поступки и помнит их.

### Лаунчер

Всё управление миром — в одном окне, без командной строки и настроек в файлах.

**Миры**
- список сохранённых миров; кнопки «ИГРАТЬ», «ОСТАНОВИТЬ», «НОВЫЙ МИР…», «НАСТРОЙКИ МИРА…», «Удалить мир…»;
- при создании мира задаются название, скорость развития и «возраст мира» — сколько игровых дней он уже прожил до вашего прихода;
- скорость развития (рейты опыта, адены, добычи и других наград) — от обычной до многократно ускоренной; меняется в настройках мира и применяется при следующем запуске;
- «Ускорить симуляцию…» — мгновенно «прожить» несколько игровых дней за всех персонажей при следующем запуске;
- удаление мира — с подтверждением; прерванное удаление можно завершить, а архивные миры — удалить окончательно.

**Живой мир**
- «Население ИИ…» — сколько персонажей под управлением компьютера находится в мире одновременно (от и до; ноль — мир без них), с постепенным приходом и уходом;
- там же переключатели поведения: группы и совместная охота, торговля между персонажами и личные магазины, приглашения живых игроков в группу, кланы, бои с другими игроками (только защита или с личными счётами), чат, обучение на собственном опыте;
- получение профессий: через квесты, а если персонаж застрял — выдача сервером через заданное число часов (можно выключить);
- «Симуляция возраста» — отдельные переключатели: сама выдаёт профессии и учит навыки накопленным опытом, «догон простоя» — за время, пока мир был выключен, персонажи получают часть заработанного;
- «Карта ИИ-персонажей…» — живая карта мира: где сейчас каждый персонаж (охота, в пути, отдых, погиб); приближение колесом, список персонажей; счётчик «ИИ онлайн» в главном окне.

**Сервисы мира**
- «Сервисы мира…» — включение, расстановка в городах и цены трёх помощников: баффер (наборы баффов), менеджер профессий (смена профессии, дворянство, саб-класс) и магазин предметов;
- автоизучение навыков при получении уровня, автоподбор добычи убийцей, собственная длительность баффов (1–1440 минут).

**Вы и клиент**
- «Выбрать / проверить клиент…» — укажите свою копию Lineage II Interlude, программа проверит её;
- «Учётная запись…» — логин и пароль к вашему локальному миру (пароль хранится в защищённом виде для вашего пользователя Windows); права владельца мира привязываются к этой записи;
- «Автовход» — вход в игру без ручного ввода (экспериментально);
- «Установка и обновление…» и «Проверить обновления» — установка комплекта из файла и проверка новых версий.

### Что реализовано

**Живые персонажи**
- охотятся по правилам игры: ищут подходящие места, подбирают добычу, пьют зелья, отдыхают, убегают от слишком сильных монстров и обходят места, где погибли;
- учатся на собственном опыте: что-то приносит добычу и опыт, где-то слишком опасно — со временем каждый выбирает своё;
- растут от первого уровня, покупают и меняют снаряжение, продают лишнее;
- получают профессии через квесты (первые и значительная часть вторых), а если застряли — сервер помогает по таймеру, который вы настраиваете;
- у каждого свой ник, приходят и уходят в разное время.

**Общение и дружба**
- отвечают вам в чате, когда вы обращаетесь по имени, пишете им лично или спрашиваете рядом;
- дают объявления, ищут группу и клан, делятся слухами и местами для охоты;
- запоминают, кто помог, а кто подвёл, и дружат или избегают друг друга;
- договариваются о встречах и держат слово — даже после перезапуска мира;
- собирают группы до четырёх человек с лекарем и защитником, приглашают и вас.

**Торговля и услуги**
- личные магазины в Dion, Giran и Aden; цены зависят от спроса, продавцы выставляют и забирают товар;
- ремесло: рецепты, материалы, изготовление на продажу;
- прямой обмен между персонажами;
- для вас: магазин предметов по типам и грейдам, баффер с готовыми наборами воина и мага, смена профессии.

**Кланы**
- основание клана, приглашение друзей, повышение уровня клана;
- клановая академия: молодые персонажи вступают, растут, а выпускники приносят клану репутацию;
- клановые навыки за репутацию;
- выход, исключение, смена лидера, роспуск клана;
- королевские стражи и рыцарские отряды;
- альянсы между кланами;
- аукцион клановых холлов, аренда и улучшения;
- войны кланов.

**Бои и риск**
- дуэли между персонажами;
- открытый PvP по правилам игры: флаг, карма и PK считает сама игра;
- персонажи защищаются от нападающих, преследуют преступников, убегают при низком здоровье;
- против живых игроков они только защищаются (можно изменить в настройках).

**Характер и «человечность»**
- у каждого свой характер: общительный или молчаливый, терпеливый, жадный, смелый, обидчивый;
- настроение и усталость: после смерти или неудачи осторожнее, после победы радостнее, устав — садятся отдохнуть;
- у сессий разная длина, у каждого свои любимые часы и места;
- цели на день: «хочу 20-й уровень», «коплю на снаряжение» — и они об этом говорят;
- живые реплики: поздравят друга с уровнем, посочувствуют, похвастаются добычей, поболтают в группе;
- стиль письма подстраивается под характер;
- не отбирают у вас монстра, которого вы уже бьёте.

**Типы серверов и взросление**
- у мира есть тип — классика (низкие рейты), крафт-сервер, ПвП-крафт или ПвП-сервер; он меняет поведение жителей: на классике они осторожнее и экономнее, на крафт-сервере больше мастерят и торгуют, на ПвП-серверах смелее точат снаряжение, чаще собираются на ПвП-местах (Goddard, Ketra, Varka, Hot Springs, Монастырь Тишины) и быстрее возвращаются в бой;
- третья профессия, саб-класс и дворянство через квесты, а если житель застрял — по таймеру, который вы задаёте в лаунчере; уровень теперь доходит до 80;
- заточка снаряжения: жители точат вещи, продают заточенное и ненужное в лавках, мастера делают заряды D–B;
- к баффу в городе ходят на любых рейтах, а на Олимпиаду идут все, кто может.

**Замки, Олимпиада и рейды**
- осады замков: регистрация, штурм и захват клановыми жителями, налоги, укрепление ворот и стен, казна замка; лорд ходит к камергеру и, если замок за воротами, входит через привратника;
- Олимпиада и герои: дворянство, запись, бои на арене, жетоны, героический статус у монумента;
- рейд-боссы и эпические боссы (Queen Ant, Orfen, Core, Zaken, Sailren) — включаются настройкой; паром Rune — Primeval Isle и квесты на Sailren;
- клан по просьбе: если написать клановому персонажу «возьмите в клан», придёт обычное окно приглашения — прямо от него или от лидера, которому он передаст просьбу.

**Живее общение и характеры**
- героический канал, крик, разговоры жителей между собой — из нескольких реплик, с темами по месту (рынок, замок, квесты);
- вечера торговли (пятница) и ПвП (суббота): жители чаще говорят и зовут друг друга;
- у каждого есть склонность — любит группы, одиночка, боец, торговец или лидер; она влияет на приглашения, места охоты, торговлю и основание кланов.

**Для администратора и лаунчера**
- игровая панель администратора: выдача профессии, предметов, навыков, адены, уровня, заточки, дворянства и героя, воскрешение, телепорт по городам, создание рейд-боссов, GM Shop, баффера и менеджера профессий, массовые действия над жителями рядом;
- в лаунчере: тип сервера, настройки заточки и её шансов, режим «Только адена» (с монстров падают только адена и квестовые предметы), часы выдачи профессии, саб-класса и дворянства; интерфейс и установщик на русском и английском.

### Частые вопросы

**Нужны ли другие игроки?** Нет. Мир живёт сам, вы выбираете, сколько в нём жителей.
**Нужен ли клиент игры?** Да, ваша собственная копия Lineage II Interlude. В комплект он не входит.
**Сохраняется ли прогресс?** Да, и миры, и персонажи сохраняются между запусками.
**Можно ли несколько миров?** Да, у каждого свои настройки и свои жители.
**Можно ли играть без компьютерных персонажей?** Да, задайте население «0».

### В планах

Эпические боссы Baium, Antharas и Valakas, осадные клан-холлы, кооперативный режим; дальнейшая проверка и доработка осад, Олимпиады, героев и рейдов.

## English

**Living World** is a single-player Lineage II Interlude game in which the world lives on without other players. You create your own world on your own computer, choose the pace of progress and the number of inhabitants, and play at your own speed. Computer-controlled characters hunt, trade, learn, make friends and clans around you. They behave like real players: each has its own temperament, habits, friends and goals. Your world and its characters persist between sessions.

The game client is not included: you need your own copy of Lineage II Interlude.

### Installation

1. Download `LivingWorld-Setup.exe` from [Releases](https://github.com/bentner163-source/Lineage-2-Interlude-Living-World-AI/releases/tag/stable-v1.0.1) and run it. If Windows shows a SmartScreen warning, click “More info” → “Run anyway”.
2. In the setup window choose a folder (the suggested one is fine), keep “Create shortcuts” if you like, and click “Install”. It takes a few minutes.
3. Click “Finish” — Living World starts. Create or select a world.
4. On first launch pick `system\L2.exe` from your copy of Interlude and enter your game login and password in the game window.

To have computer-controlled characters around you, set their number under “Население ИИ…” (AI Population) while the world is stopped (zero means a world without them). When you finish, exit the game and click “Остановить” (Stop) before closing the launcher.

After installing 1.0.1, use **Check for updates** for subsequent releases. The launcher downloads only changed components. Stop your world before applying an update.

### Before starting your world

Review the settings carefully when you create a world. Choose its age, progression rates, AI population, and available services. These settings shape your world from the moment it starts.

AI characters are controlled by the game. There are no human players behind them. Their behavior can be unpredictable, and they sometimes make mistakes. Living World is still in active development.

### What it looks like

You enter a world that is already going about its business. Private stores line the road, someone in town is looking for a hunting party, and on a clearing two friends hunt together and chat about how the day went. One inhabitant has been saving for new gear for hours and tells everyone about it, another is tired and sits down for a rest (“brb”), a third is recruiting for a clan. You can simply watch, or join a party, trade, make friends, quarrel and go to war — the world reacts to what you do and remembers it.

### Launcher

Everything about your world is managed in one window, with no command line and no settings files.

**Worlds**
- a list of saved worlds; buttons “PLAY”, “STOP”, “NEW WORLD…”, “WORLD SETTINGS…”, “Delete world…”;
- when creating a world you set its name, progression speed and “world age” — how many game days it has already lived before you arrive;
- progression speed (experience, adena, loot and other rewards) from normal to many times faster; changed in the world settings and applied on the next start;
- “Fast-forward the simulation…” — instantly “live through” several game days for all characters at the next start;
- deleting a world asks for confirmation; an interrupted deletion can be finished and archived worlds removed for good.

**A living world**
- “AI Population…” — how many computer-controlled characters are in the world at once (from–to; zero means a world without them), arriving and leaving gradually;
- switches for their behaviour: parties and hunting together, trade between characters and private stores, inviting live players to a party, clans, fights with other players (defence only, or with personal grudges), chat, learning from experience;
- professions: through quests, and if a character gets stuck the server grants one after a number of hours you set (can be switched off);
- “Age simulation” switches: it grants professions and teaches skills from accumulated experience by itself, and “catch-up” gives characters part of what they would have earned while the world was switched off;
- “AI character map…” — a live map of the world: where each character is (hunting, on the way, resting, dead); zoom with the wheel, a list of characters; an “AI online” counter in the main window.

**World services**
- “World services…” — switching on, placing in towns and prices for three helpers: a buffer (sets of buffs), a profession manager (profession change, nobility, subclass) and an item shop;
- automatic skill learning on level-up, automatic loot pick-up by the killer, your own buff duration (1–1440 minutes).

**You and the client**
- “Choose / check client…” — point to your own copy of Lineage II Interlude and the program checks it;
- “Account…” — the login and password for your local world (the password is stored protected for your Windows user); the world owner's rights are tied to this account;
- “Auto-login” — enter the game without typing (experimental);
- “Setup and update…” and “Check for updates” — installing a package from a file and checking for new versions.

### What is implemented

**Living characters**
- hunt by the rules of the game: look for suitable places, pick up loot, drink potions, rest, run from monsters that are too strong and avoid places where they died;
- learn from their own experience: some places bring loot and experience, others are too dangerous — over time each one chooses its own;
- grow from level one, buy and change gear, sell what they do not need;
- get professions through quests (the first ones and a large part of the second ones), and if they get stuck the server helps on a timer you configure;
- each has its own name and comes and goes at different times.

**Talk and friendship**
- answer you in chat when you address them by name, write to them privately or ask nearby;
- post announcements, look for a party and a clan, share rumours and hunting spots;
- remember who helped and who let them down, and befriend or avoid each other;
- arrange meetings and keep their word — even after the world restarts;
- form parties of up to four with a healer and a protector, and invite you too.

**Trade and services**
- private stores in Dion, Giran and Aden; prices follow demand, sellers stock and clear their goods;
- crafting: recipes, materials, making goods to sell;
- direct exchange between characters;
- for you: an item shop by type and grade, a buffer with ready warrior and mage sets, a profession change service.

**Clans**
- founding a clan, inviting friends, raising the clan level;
- clan academy: young characters join and grow, and graduates bring the clan reputation;
- clan skills bought with reputation;
- leaving, expelling, changing the leader, dissolving the clan;
- royal guards and knight orders;
- alliances between clans;
- clan hall auctions, rent and upgrades;
- clan wars.

**Combat and risk**
- duels between characters;
- open PvP by the rules of the game: the game itself handles the flag, karma and PK;
- characters defend themselves against attackers, chase outlaws and flee at low health;
- against live players they only defend themselves (can be changed in the settings).

**Character and “humanity”**
- each has its own temperament: sociable or quiet, patient, greedy, brave, touchy;
- mood and tiredness: more careful after a death or a setback, more cheerful after a win, sitting down to rest when tired;
- sessions of different lengths, each with favourite hours and places;
- goals for the day — “want level 20”, “saving for gear” — and they talk about them;
- lively remarks: they congratulate a friend on a level, sympathise, brag about loot and chat in a party;
- their writing style follows their temperament;
- they do not take a monster you are already fighting.

**Server types and growth**
- a world has a type — classic (low rates), craft server, PvP craft or PvP server; it changes how the inhabitants behave: on a classic server they are more careful and thrifty, on a craft server they craft and trade more, on PvP servers they enchant more boldly, gather at the PvP spots (Goddard, Ketra, Varka, Hot Springs, the Monastery of Silence) more often and return to the fight sooner;
- third profession, subclass and nobility through quests, and if an inhabitant gets stuck, on a timer you set in the launcher; the level now reaches 80;
- gear enchanting: inhabitants enchant their gear, sell enchanted and unneeded items in stalls, and craftsmen make D–B shots;
- they visit the buffer in town at any rates, and everyone who can goes to the Olympiad.

**Castles, Olympiad and raids**
- castle sieges: registration, assault and capture by clan inhabitants, taxes, strengthening the gates and walls, the castle treasury; a lord walks to the chamberlain and, if the castle is behind its gates, enters through the doorman;
- Olympiad and heroes: nobility, registration, arena fights, tokens, hero status at the monument;
- raid bosses and epic bosses (Queen Ant, Orfen, Core, Zaken, Sailren) — switched on in a setting; the Rune — Primeval Isle ferry and the quests for Sailren;
- a clan on request: if you write “take me into the clan” to a clan member, you get the ordinary invitation window — from them directly or from the leader they pass your request to.

**Livelier talk and character**
- a hero channel, shouts, conversations between inhabitants of several lines on topics fitting the place (market, castle, quests);
- market evenings (Friday) and PvP evenings (Saturday): inhabitants talk more and call each other;
- each one has a leaning — likes groups, a loner, a fighter, a merchant or a leader; it affects invitations, hunting places, trade and founding clans.

**For the administrator and the launcher**
- an in-game administrator panel: granting professions, items, skills, adena, levels, enchant, nobility and hero status, resurrection, teleport to towns, spawning raid bosses, the GM Shop, the buffer and the profession manager, mass actions on nearby inhabitants;
- in the launcher: server type, enchant settings and chances, “Only adena” mode (monsters drop only adena and quest items), hours for profession, subclass and nobility; the interface and the installer in Russian and English.

### FAQ

**Do I need other players?** No. The world lives on its own; you choose how many inhabitants it has.
**Do I need the game client?** Yes, your own copy of Lineage II Interlude. It is not included.
**Is progress saved?** Yes, both worlds and characters persist between sessions.
**Can I have several worlds?** Yes, each with its own settings and inhabitants.
**Can I play without computer-controlled characters?** Yes, set the population to “0”.

### Planned

The epic bosses Baium, Antharas and Valakas, siege clan halls, cooperative mode; further testing and polish of sieges, Olympiad, heroes and raids.
