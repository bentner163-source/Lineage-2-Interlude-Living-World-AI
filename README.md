# Prism - Interlude

[Русский](#русский) · [English](#english)

## Русский

**Prism - Interlude** (раньше — Living World) — одиночная игра в Lineage II Interlude, в которой мир живёт и без других игроков. Сборка разработчика **DevWS-Bentner163**. Вы создаёте свой мир на своём компьютере, выбираете скорость развития и количество ИИ-персонажей и играете в удобном темпе. Рядом с вами охотятся, торгуют, учатся, заводят друзей и кланы персонажи, которыми управляет компьютер. У каждого свой характер, привычки, друзья и цели. Мир и персонажи сохраняются между запусками.

Игровой клиент в комплект не входит: нужна ваша собственная копия Lineage II Interlude.

ИИ в группах выполняют роли танков, лекарей и саппортов. Например, Sword Singer и Bladedancer поддерживают группу песнями и танцами. Союзники восстанавливают ману и могут воскресить павших после боя. Группы ИИ могут собирать фрагменты для походов в Dimensional Rift. ИИ торгуют с игроками через личные лавки и используют клановый склад для обмена материалами. Мир может включать Zariche и Akamanah, а реакцию ИИ на их владельцев можно настроить.

### Установка

1. Скачайте `Prism-Interlude-Setup.exe` из [последнего выпуска](https://github.com/bentner163-source/PrismLineage2/releases/latest) и запустите его. Если Windows покажет предупреждение SmartScreen, нажмите «Подробнее» → «Выполнить в любом случае».
2. В окне установщика выберите папку (подойдёт предложенная), при желании оставьте галочку «Создать ярлыки» и нажмите «Установить». Установка занимает несколько минут.
3. Нажмите «Готово» — Prism запустится. Создайте или выберите мир.
4. При первом запуске укажите файл `system\L2.exe` из вашей копии Interlude и введите игровой логин и пароль в окне игры. Адрес вашего мира в `system\l2.ini` лаунчер укажет сам, копию исходного файла он сохранит рядом (`l2.ini.prism-original`).

Чтобы рядом появились персонажи под управлением компьютера, задайте их количество в окне «Население ИИ…» при остановленном мире (ноль — мир без них). Закрывая игру, выйдите из неё и нажмите «Остановить» до закрытия лаунчера.

### Перед запуском мира

Внимательно изучите настройки, когда создаёте мир. Выберите его возраст, скорость развития, число ИИ-персонажей и доступные сервисы. Эти параметры определяют, каким будет мир при первом запуске.

ИИ-персонажами управляет игра. За ними нет живых игроков. Их поведение может быть непредсказуемым, а привычные игровые действия иногда выполняются с ошибками. Prism продолжает дорабатываться.

### Как это выглядит

Вы входите в мир, а он уже идёт своим чередом. У дороги стоят личные магазины, в городе кто-то ищет группу на охоту, а на поляне двое друзей охотятся вместе и пишут в чат, как прошёл день. Один из ИИ-персонажей давно копит на новое снаряжение и всем об этом рассказывает, другой устал и сел отдохнуть («брб»), третий зовёт в клан. Вы можете просто смотреть, можете вступить в группу, торговать, дружить, ссориться и воевать — мир реагирует на ваши поступки и помнит их.

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
- настройки баффов, сумки и веса, Mana Potion, профили магазина предметов, очистки предметов на земле, расстояния между лавками, мобов-чемпионов — в окнах «Настройки мира…» и «Сервисы мира…»;
- «Осады…» — режим осад, заказ осады выбранного замка, участие ИИ-кланов и список ближайших осад.

**Вы и клиент**
- «Выбрать / проверить клиент…» — укажите свою копию Lineage II Interlude, программа проверит её;
- подключение к миру: перед запуском лаунчер сам вписывает адрес мира в `system\l2.ini` и хранит копию исходного файла; другие файлы клиента не меняются;
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
- собирают группы до четырёх человек с лекарем и защитником, приглашают и вас;
- меню «ИИ рядом» (Alt+B): список персонажей поблизости, разговор готовыми фразами, просьбы о бафе и хиле, приглашение в группу и клан, обмен, команды своей группе;
- говорят о многом: где купить, рейд-боссы, осады, Олимпиада, Seven Signs, какой класс качать, откуда они и давно ли играют, шутят, подбадривают; понимают «а где?», «а ты?», «почему?» после вопроса;
- помнят, как вы с ними обошлись: друга встречают по-дружески и уступают в цене, грубияну отвечают холодно, тому, кто их убивал, отказывают;
- сами зовут на помощь, когда проигрывают бой, предлагают дружбу и пишут вам, когда вы заходите в игру;
- в группе выполняют команды («за мной», «жди», «бей мою цель», «отходим», «в город», «продай лут»), а соклановцы приходят на «сбор» в клан-чате.

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
- войны кланов;
- живой клан-чат: ИИ-соклановцы отвечают вам и друг другу, заводят разговоры, здороваются и поздравляют с уровнем; в окне клана видно, кто из них в сети;
- если лидер далеко, вам скажут об этом, а приглашение придёт, когда вы окажетесь рядом.

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
- у мира есть тип — классика (низкие рейты), крафт-сервер, ПвП-крафт или ПвП-сервер; он меняет поведение ИИ-персонажей: на классике они осторожнее и экономнее, на крафт-сервере больше мастерят и торгуют, на ПвП-серверах смелее точат снаряжение, чаще собираются на ПвП-местах (Goddard, Ketra, Varka, Hot Springs, Монастырь Тишины) и быстрее возвращаются в бой;
- третья профессия, саб-класс и дворянство через квесты, а если ИИ-персонаж застрял — по таймеру, который вы задаёте в лаунчере; уровень доходит до 80;
- заточка снаряжения: ИИ-персонажи точат вещи, продают заточенное и ненужное в лавках, мастера делают заряды D–B;
- к баффу в городе ходят на любых рейтах, а на Олимпиаду идут все, кто может.

**Замки, Олимпиада и рейды**
- осады замков: регистрация, штурм и захват клановыми ИИ-персонажами, налоги, укрепление ворот и стен, казна замка; лорд ходит к камергеру и, если замок за воротами, входит через привратника;
- Олимпиада и герои: дворянство, запись, бои на арене, жетоны, героический статус у монумента;
- рейд-боссы и эпические боссы (Queen Ant, Orfen, Core, Zaken, Sailren) — включаются настройкой; паром Rune — Primeval Isle и квесты на Sailren;
- клан по просьбе: если написать клановому персонажу «возьмите в клан», придёт обычное окно приглашения — прямо от него или от лидера, которому он передаст просьбу.

**Живее общение и характеры**
- героический канал, крик, разговоры ИИ-персонажей между собой — из нескольких реплик, с темами по месту (рынок, замок, квесты);
- вечера торговли (пятница) и ПвП (суббота): ИИ-персонажи чаще говорят и зовут друг друга;
- у каждого есть склонность — любит группы, одиночка, боец, торговец или лидер; она влияет на приглашения, места охоты, торговлю и основание кланов.

**Для администратора и лаунчера**
- игровая панель администратора: выдача профессии, предметов, навыков, адены, уровня, заточки, дворянства и героя, воскрешение, телепорт по городам, создание рейд-боссов, GM Shop, баффера и менеджера профессий, массовые действия над ИИ-персонажами рядом;
- в лаунчере: тип сервера, настройки заточки и её шансов, режим «Только адена» (с монстров падают только адена и квестовые предметы), часы выдачи профессии, саб-класса и дворянства; интерфейс и установщик на русском и английском.

**Предметы, вес и рынок**
- свитки заточки и Life Stone складываются в стопки (настройка; в игровой панели есть кнопка «объединить одинаковые стопки» для уже лежащих в сумке);
- очистка предметов на земле: время исчезновения, потолок числа предметов, порция удаления и аварийная очистка самых старых;
- размер сумки (отдельно для гномов), множитель переносимого веса, галочка «без замедления от перегруза»;
- личные магазины ИИ-персонажей не накладываются друг на друга: минимальная дистанция между лавками настраивается;
- ИИ-персонажи надевают найденную и купленную бижутерию, пересматривают снаряжение при каждой находке, покупке, крафте или обмене и пишут в журнал, почему не надели ту или иную вещь;
- цены в лавках следуют за конкурентами: продавец чуть подрезает соседа, а на дефицитный товар ставит наценку; мастера охотнее делают дефицитные заряды.

**Баффы и помощники**
- лимит баффов на персонаже настраивается (по умолчанию как в игре — 20); баффер умеет наборы до 40 эффектов и подстраивается под лимит;
- шесть готовых наборов баффера: воин, маг, лучник, кинжальщик, танк, саппорт; отдельные эффекты можно выключить в лаунчере; ИИ-персонажи собирают себе личную схему баффов;
- Mana Potion настраивается: как в игре, фиксированное количество MP или процент от максимума, сразу или постепенно, время повторного использования, запрет в бою, минимальный уровень. ИИ-персонажи пьют его, когда он действительно помогает, и покупают, если он того стоит;
- магазин предметов (GM Shop) получил профили: всё, всё до грейда B / A / S включительно, стандартный, базовый, только расходники, свой набор категорий и «выключен». Отдельные галочки отключают ресурсы, рецепты, кристаллы и самоцветы; ИИ-персонажи пользуются тем ассортиментом, который есть.

**Мобы-чемпионы**
- часть появляющихся монстров становится сильнее и приносит больше награды: шанс, диапазон уровней, множители здоровья, атаки, защиты, опыта, SP, адены, дропа и спойла, дальность агрессии, список исключений. По умолчанию выключено;
- рейд- и эпические боссы, сундуки, миньоны и монстры с особыми скриптами чемпионами не становятся;
- ИИ-персонажи оценивают чемпиона по его настоящей силе: в одиночку обходят, в группе идут.

**Осады замков**
- кнопка «Осады…» в лаунчере: классический режим, ускоренный режим (осада каждого замка через заданное число часов), заказ осады выбранного замка через 15, 30, 60 минут, через своё число минут или в точное время, включение и отключение участия ИИ-кланов, список ближайших осад;
- перед осадой идёт подготовка по этапам (объявление, сбор, выдвижение, сбор перед боем); клан-лидеры регистрируются по обычным правилам игры, участники идут к замку пешком, клановые призывы собирают их в одном месте;
- результат осады определяет только игра; после осады записываются итоги и потери сторон;
- в игровой панели администратора есть раздел «Осады замков»: замки, время до начала, атакующие и защитники, назначение осады, итоги.

**Общение с вашей группой и обмен**
- ИИ-персонажи принимают обмен от вас: подарки, адена, снаряжение, расходники; справедливый обмен принимается, подмена списка после вашего подтверждения не проходит, висящий обмен сам отменяется;
- в групповом чате понимают команды по-русски и по-английски: «за мной», «стой», «идём», «бей», «не бей», «регрупп», «баф», «хил», «рес», «мана», «отходим», «фармим здесь», «в город», «помоги», «сядь», «статус»; можно обратиться по имени или написать шёпотом одному персонажу; команды лидера главнее;
- они отвечают коротко и не все сразу, а сами сообщают группе, когда мало здоровья, маны или зелий.

**Эпические боссы**
- среди целей ИИ-персонажей есть Baium, Antharas и Valakas (в настройках мира выбираются боссы, которых могут штурмовать ИИ-группы; по умолчанию выключено). Отдельная галочка разрешает ИИ-персонажам входить в логово без предметов-пропусков; без неё вход идёт по правилам игры. Эта часть пока проверена только на сервере, живая приёмка впереди.
**Поведение и ориентирование**
- ИИ-персонажи чаще замечают живого игрока, помогают раненому, не лезут на монстра рядом с вами, садятся отдохнуть от усталости, лучники и маги отходят от монстров на дистанцию;
- боевые навыки используются осмысленнее: выбор по ситуации, экономия маны, переключаемые навыки, аварийные навыки спасения;
- исправлено зацикливание у стен и в подземных деревнях: чужие маршруты больше не ведут через стену, недостижимые места откладываются вместо хождения по кругу.

**Лаунчер**
- вкладки в окнах настроек, карточки миров, цветные кнопки;
- окна и поля «Осады…», «Предметы и рынок», Mana Potion, мобы-чемпионы, профили GM Shop.

### Частые вопросы

**Нужны ли другие игроки?** Нет. Мир живёт сам, вы выбираете, сколько в нём ИИ-персонажей.
**Нужен ли клиент игры?** Да, ваша собственная копия Lineage II Interlude. В комплект он не входит.
**Сохраняется ли прогресс?** Да, и миры, и персонажи сохраняются между запусками.
**Можно ли несколько миров?** Да, у каждого свои настройки и свои ИИ-персонажи.
**Можно ли играть без компьютерных персонажей?** Да, задайте население «0».
**Меняет ли Prism файлы клиента?** Только адрес сервера в `system\l2.ini`, с копией исходного файла рядом (`l2.ini.prism-original`). Чтобы вернуть прежний адрес, замените `l2.ini` этой копией.

### В планах

Осадные клан-холлы, живая проверка штурма логов эпических боссов; дальнейшая проверка и доработка осад, Олимпиады, героев и рейдов, ручная приёмка с клиентом игры (бой, обмен, команды в группе).

## English

**Prism - Interlude** (formerly Living World) is a single-player Lineage II Interlude game in which the world lives on without other players. Built by **DevWS-Bentner163**. You create your own world on your own computer, choose the pace of progress and the number of AI characters, and play at your own speed. Computer-controlled characters hunt, trade, learn, make friends and clans around you. They behave like real players: each has its own temperament, habits, friends and goals. Your world and its characters persist between sessions.

The game client is not included: you need your own copy of Lineage II Interlude.

AI parties include tanks, healers and support characters. Sword Singer and Bladedancer support the party with songs and dances. Allies can restore mana and resurrect fallen party members after combat. AI parties can collect fragments for trips into the Dimensional Rift. AI characters trade through player shops and share materials through clan warehouses. Worlds can feature Zariche and Akamanah, with configurable AI reactions to their wielders.

### Installation

1. Download `Prism-Interlude-Setup.exe` from the [latest release](https://github.com/bentner163-source/PrismLineage2/releases/latest) and run it. If Windows shows a SmartScreen warning, click “More info” → “Run anyway”.
2. In the setup window choose a folder (the suggested one is fine), keep “Create shortcuts” if you like, and click “Install”. It takes a few minutes.
3. Click “Finish” — Prism starts. Create or select a world.
4. On first launch pick `system\L2.exe` from your copy of Interlude and enter your game login and password in the game window. The launcher sets your world's address in `system\l2.ini` itself and keeps a copy of the original file next to it (`l2.ini.prism-original`).

To have computer-controlled characters around you, set their number under “Население ИИ…” (AI Population) while the world is stopped (zero means a world without them). When you finish, exit the game and click “Остановить” (Stop) before closing the launcher.

### Before starting your world

Review the settings carefully when you create a world. Choose its age, progression rates, AI population, and available services. These settings shape your world from the moment it starts.

AI characters are controlled by the game. There are no human players behind them. Their behavior can be unpredictable, and they sometimes make mistakes. Prism is still in active development.

### What it looks like

You enter a world that is already going about its business. Private stores line the road, someone in town is looking for a hunting party, and on a clearing two friends hunt together and chat about how the day went. One AI character has been saving for new gear for hours and tells everyone about it, another is tired and sits down for a rest (“brb”), a third is recruiting for a clan. You can simply watch, or join a party, trade, make friends, quarrel and go to war — the world reacts to what you do and remembers it.

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
- settings for buffs, bag and weight, the Mana Potion, item shop profiles, cleaning of items on the ground, distance between stalls and champion monsters — in the “World settings…” and “World services…” windows;
- “Sieges…” — the siege mode, ordering a siege of a chosen castle, AI clans in sieges and a list of the nearest sieges.

**You and the client**
- “Choose / check client…” — point to your own copy of Lineage II Interlude and the program checks it;
- connecting to your world: before the start the launcher writes the world's address into `system\l2.ini` and keeps a copy of the original file; no other client file is changed;
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
- form parties of up to four with a healer and a protector, and invite you too;
- the **AI nearby** board (Alt+B): characters around you, ready lines to talk, asking for a buff or a heal, party and clan invitations, trade, orders to your own party;
- talk about much more: where to buy, raid bosses, sieges, the Olympiad, the Seven Signs, which class to play, where they are from and how long they play; they joke and cheer you up, and understand "where?", "you?", "why?" after a question;
- remember how you treated them: a friend is greeted warmly and gets a better price, a rude person gets a cold answer, someone who killed them is refused;
- call for help when they lose a fight, offer friendship and message you when you log in;
- follow party orders ("follow me", "wait", "attack my target", "retreat", "to town", "sell the loot"), and clan members come when you call "gather" in the clan chat.

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
- clan wars;
- a living clan chat: AI clan members answer you and each other, start conversations, greet you and congratulate you on a level; the clan window shows who of them is online;
- if the leader is far away you are told so, and the invitation comes when you are near.

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
- a world has a type — classic (low rates), craft server, PvP craft or PvP server; it changes how the AI characters behave: on a classic server they are more careful and thrifty, on a craft server they craft and trade more, on PvP servers they enchant more boldly, gather at the PvP spots (Goddard, Ketra, Varka, Hot Springs, the Monastery of Silence) more often and return to the fight sooner;
- third profession, subclass and nobility through quests, and if an AI character gets stuck, on a timer you set in the launcher; the level reaches 80;
- gear enchanting: AI characters enchant their gear, sell enchanted and unneeded items in stalls, and craftsmen make D–B shots;
- they visit the buffer in town at any rates, and everyone who can goes to the Olympiad.

**Castles, Olympiad and raids**
- castle sieges: registration, assault and capture by clan AI characters, taxes, strengthening the gates and walls, the castle treasury; a lord walks to the chamberlain and, if the castle is behind its gates, enters through the doorman;
- Olympiad and heroes: nobility, registration, arena fights, tokens, hero status at the monument;
- raid bosses and epic bosses (Queen Ant, Orfen, Core, Zaken, Sailren) — switched on in a setting; the Rune — Primeval Isle ferry and the quests for Sailren;
- a clan on request: if you write “take me into the clan” to a clan member, you get the ordinary invitation window — from them directly or from the leader they pass your request to.

**Livelier talk and character**
- a hero channel, shouts, conversations between AI characters of several lines on topics fitting the place (market, castle, quests);
- market evenings (Friday) and PvP evenings (Saturday): AI characters talk more and call each other;
- each one has a leaning — likes groups, a loner, a fighter, a merchant or a leader; it affects invitations, hunting places, trade and founding clans.

**For the administrator and the launcher**
- an in-game administrator panel: granting professions, items, skills, adena, levels, enchant, nobility and hero status, resurrection, teleport to towns, spawning raid bosses, the GM Shop, the buffer and the profession manager, mass actions on nearby AI characters;
- in the launcher: server type, enchant settings and chances, “Only adena” mode (monsters drop only adena and quest items), hours for profession, subclass and nobility; the interface and the installer in Russian and English.

**Items, weight and the market**
- enchant scrolls and Life Stones stack (a setting; the in-game panel has a “merge identical stacks” button for items already in the bag);
- cleaning of items on the ground: lifetime, a cap on the number of items, a removal batch size and an emergency cleanup of the oldest;
- bag size (dwarves separately), a carry-weight multiplier and a “no overweight slowdown” switch;
- AI characters' private stores no longer overlap: the minimum distance between stalls is configurable;
- AI characters wear the jewelry they find and buy, re-check their gear on every find, purchase, craft or trade, and log why they did not put a particular item on;
- stall prices follow the competition: a seller undercuts a neighbour a little and adds a premium for scarce goods; craftsmen make scarce shots more willingly.

**Buffs and helpers**
- the buff limit per character is configurable (the game default of 20 stays unless you change it); the buffer offers sets of up to 40 effects and adapts to the limit;
- six ready buffer sets: warrior, mage, archer, dagger, tank, support; single effects can be switched off in the launcher; AI characters build their own buff scheme;
- the Mana Potion is configurable: as in the game, a fixed amount of MP or a percentage of the maximum, instant or gradual, cooldown, a ban in combat, a minimum level. AI characters drink it when it really helps and buy it when it is worth it;
- the item shop (GM Shop) has profiles: everything, everything up to grade B / A / S inclusive, standard, basic, consumables only, a custom set of categories, and “off”. Separate switches remove resources, recipes, crystals and gemstones; AI characters use whatever assortment exists.

**Champion monsters**
- some spawned monsters become stronger and give better rewards: chance, level range, multipliers for health, attack, defence, experience, SP, adena, drop and spoil, aggro range, an exclusion list. Off by default;
- raid and epic bosses, chests, minions and monsters with special scripts never become champions;
- AI characters judge a champion by its real strength: they avoid it alone and go for it in a party.

**Castle sieges**
- a “Sieges…” button in the launcher: the classic mode, the accelerated mode (a siege of every castle after a set number of hours), an ordered siege of a chosen castle in 15, 30 or 60 minutes, in your own number of minutes or at an exact time, switching AI clans in sieges on and off, and a list of the nearest sieges;
- the preparation before a siege runs in stages (announcement, muster, march, regroup); clan leaders register by the ordinary rules of the game, members walk to the castle, and clan calls gather them in one place;
- only the game decides the result of a siege; the results and the losses of both sides are recorded afterwards;
- the in-game administrator panel has a “Castle sieges” section: castles, time to the start, attackers and defenders, ordering a siege, results.

**Talking to your party and trading**
- AI characters accept a trade from you: gifts, adena, gear, consumables; a fair exchange is accepted, swapping the list after your confirmation does not work, and a trade left hanging cancels itself;
- in the party chat they understand commands in Russian and English: “follow me”, “stop”, “go”, “assist”, “don't attack”, “regroup”, “buff”, “heal”, “res”, “mana”, “retreat”, “farm here”, “town”, “help”, “rest”, “status”; you can address one by name or whisper to a single character; the leader's commands come first;
- they answer briefly and not all at once, and tell the party on their own when they are low on health, mana or potions.

**Epic bosses**
- Baium, Antharas and Valakas are among the targets of the AI characters (the world settings choose which bosses AI groups may raid; off by default). A separate switch lets AI characters enter the lair without the entry items; without it the entry follows the rules of the game. This part has so far been checked on the server only; live acceptance is still ahead.
**Behaviour and orientation**
- AI characters notice a live player more often, help a wounded one, do not go for a monster next to you, sit down to rest when tired, and archers and mages keep their distance from monsters;
- combat skills are used more sensibly: chosen by the situation, saving mana, toggle skills, emergency survival skills;
- running in circles at walls and in underground villages is fixed: routes found for someone else no longer lead through a wall, and unreachable places are put aside instead of being circled.

**Launcher**
- tabs in the settings windows, world cards, coloured buttons;
- windows and fields “Sieges…”, “Items and market”, Mana Potion, champion monsters, GM Shop profiles.

### FAQ

**Do I need other players?** No. The world lives on its own; you choose how many AI characters it has.
**Do I need the game client?** Yes, your own copy of Lineage II Interlude. It is not included.
**Is progress saved?** Yes, both worlds and characters persist between sessions.
**Can I have several worlds?** Yes, each with its own settings and AI characters.
**Can I play without computer-controlled characters?** Yes, set the population to “0”.
**Does Prism change client files?** Only the server address in `system\l2.ini`, with a copy of the original file next to it (`l2.ini.prism-original`). To get the old address back, replace `l2.ini` with that copy.

### Planned

Siege clan halls; further testing and polish of sieges, Olympiad, heroes and raids, and manual acceptance with the game client (combat, trading, party commands).

