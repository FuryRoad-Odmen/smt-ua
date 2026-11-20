![SMT UA](smt-banner.jpg)

# SMT UA

SMT UA is a region map for EVE Online. It shows where you are, where the danger is, and what has cleared. You do not need to have used SMT before.

The first launch is in English. 43 languages are included. Choose one in File, Settings.

What changed in each version is on the [releases](https://github.com/FuryRoad-Odmen/smt-ua/releases) page.

The program is free. The author spends tips on [Buy Me a Coffee](https://buymeacoffee.com/odmenrustb) helping Ukraine fight the aggressor, at his own discretion.

## What you get

**Map.** One region, or the whole universe. Your route, jump bridges, and system security are on the map. The pilot comes from ESI, so the dot follows the client. Filters above the map color systems and circles: kills, jumps, ADM.

**Overlay.** The same map over the game: the same colors, lines, and filter. Clicks pass through. Drag the corner to resize. The system tip is dark, like the client, and sits on the system under the cursor. Background, content, and lines each have their own opacity. To move the overlay, turn off click-through: View, Toggle overlay click-through, or `Shift+Ctrl+Alt+T`. File, Overlay opens it again if you closed it.

**Intel.** SMT reads the channel log from `Documents\EVE\logs`. A line that names a system draws an orange disk on the map and on the overlay. A follow-up from the same writer does not add a second disk or play the sound again. Three sounds by distance: close, farther, and local. Your own D-Scan can stay silent. Other scans still sound. Channel names and clear words such as `clr` are in File, Settings, Intel.

**D-Scan.** DS by your character, or DS on the button row, takes a copied directional scan and the system you are in. Ships go to dscan.info. The clipboard gets a line with the system and a link. Paste that line into Intel. The map shows a disk, the feed shows the ship count. A short notice says the link is ready.

**Local.** LT takes a copied local list and puts a line with the system and a report link on the clipboard. DL on the same row sends those names to D-Scan.

**zKill.** A fresh kill is a dark red disk on that system. It fades while the kill is still on the board. Pilot kills for the hour are a purple ring.

**Vision aid.** Off until you turn it on. Put a clear field over the small colored marks in the client. While a listed color is in the field, a sound plays and a circle lights on your current system, on the map and on the overlay. The circle is 10% to 100% of an intel alert. The visibility slider fades only the frame. The field stays clear, so the mark is still read. M on the button row mutes the sound until the color leaves, and only while this aid is on. A blink does not drop the alarm on a dark frame. Settings are on their own tab, after Overlay. OK writes them immediately. Under the second object, Reset object sizes and colors puts back the built-in sizes and colors and leaves the rest of your settings.

**Updates.** When a newer version has already downloaded, a question stays open until you choose. Restart installs it and starts SMT again. Later opens the map.

## Getting started

1. Install the [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0) if it is not there yet.
2. Download the archive from [releases](https://github.com/FuryRoad-Odmen/smt-ua/releases) and unpack it into its own folder.
3. Run `SMT.exe`. There is no installer. On the next launch SMT picks up a newer release once the archive has downloaded. Settings in `%APPDATA%\SMT` stay where they are.

Character: log the pilot into the client, then in SMT open File, Characters, Add character, and sign in in the browser. Pick that pilot as active at the top. If the pilot does not move on the map, turn on ESI positions under File, Settings, General, and sign the character in again.

Logs: SMT reads `Documents\EVE\logs`, with `Chatlogs` and `Gamelogs` inside. The Intel channel has to be open in the client. Another log folder is set under File, Settings, General. Restart SMT after that.

## Українською

SMT UA це карта регіону для EVE Online. На ній видно, де ти, де небезпека, і що вже очистилось. Користуватись SMT раніше не потрібно.

Перший запуск англійською. Мов 43. Іншу обирають у Файл, Налаштування.

Що змінилось у кожній версії, написано на сторінці [релізів](https://github.com/FuryRoad-Odmen/smt-ua/releases).

Програма безкоштовна. Чайові на [Buy Me a Coffee](https://buymeacoffee.com/odmenrustb) автор витрачає на допомогу Україні в боротьбі проти агресора на свій розсуд.

### Що тут є

**Карта.** Один регіон або весь всесвіт. Маршрут, мости і безпека систем на карті. Пілот береться з ESI, тож крапка йде за клієнтом. Фільтри над картою фарбують системи і кружки: вбивства, стрибки, ADM.

**Оверлей.** Та сама карта поверх гри: ті самі кольори, лінії і фільтр. Кліки проходять у гру. Розмір тягнеться за кут. Підказка системи темна, як у клієнті, і стоїть біля тієї системи, де курсор. Прозорість фону, вмісту і ліній окрема. Щоб зсунути оверлей, вимкни пропуск кліків: Вигляд, Перемкнути кліки наскрізь для оверлея, або `Shift+Ctrl+Alt+T`. Якщо оверлей закрили, його знову відкриває Файл, Оверлей.

**Intel.** SMT читає журнал каналу з `Документи\EVE\logs`. Рядок із системою малює помаранчевий диск на карті й на оверлеї. Продовження того самого автора не ставить другий диск і не грає звук знову. Три звуки за відстанню: близько, далі і локал. Свій D-Scan можна лишити без звуку, чужі звучать. Назви каналів і слова очищення на кшталт `clr` задають у Файл, Налаштування, Інтел.

**D-Scan.** DS біля персонажа або DS на рядку кнопок бере скопійований спрямований скан і систему, де стоїш. Кораблі йдуть на dscan.info. У буфері лишається рядок із системою і посиланням, його вставляють в Intel. На карті диск, у стрічці число кораблів. Коротке сповіщення каже, що посилання готове.

**Local.** LT бере скопійований список локала і кладе в буфер рядок із системою і посиланням на звіт. DL на тому ж рядку надсилає ті самі імена на D-Scan.

**zKill.** Свіжий кіл це темно-червоний диск на системі. Він тане, поки кіл є на дошці. Коло вбивств пілотів за годину фіолетове.

**Помічник зору.** Вимкнений, поки його не увімкнути. Прозоре поле ставлять на дрібні кольорові значки в клієнті. Поки колір зі списку в полі, грає звук, а на поточній системі на карті й на оверлеї світиться кружок. Розмір кружка від 10% до 100% диска оповіщення. Повзунок видимості гасить тільки рамку, саме поле лишається прозорим. M на рядку кнопок глушить звук, поки колір не зникне, і лише поки помічник зору увімкнений. Якщо значок моргає, сигнал не скидається на темному кадрі. Налаштування на окремій вкладці після «Оверлей». Кнопка «Гаразд» записує їх одразу. Під другим об'єктом «Скинути розміри і кольори об'єктів» повертає вбудовані розміри й кольори і не чіпає решту налаштувань.

**Оновлення.** Коли новіша версія вже скачана, питання стоїть, поки не буде вибору. Перезапуск ставить її і запускає SMT знову. «Пізніше» відкриває карту.

### Як почати

1. Постав [.NET 8 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/8.0), якщо його ще немає.
2. Завантаж архів зі сторінки [релізів](https://github.com/FuryRoad-Odmen/smt-ua/releases) і розпакуй у окрему теку.
3. Запусти `SMT.exe`. Інсталятора немає. Наступний реліз програма підхоплює сама під час запуску, якщо архів встиг скачатися. Налаштування в `%APPDATA%\SMT` не чіпаються.

Персонаж: у клієнті увійди пілотом, у SMT відкрий Файл, Персонажі, Додати персонажа, увійди в браузері. Зверху обери його як активного. Якщо пілот не рухається по карті, у Файл, Налаштування, Загальні увімкни використання ESI для позицій і зайди персонажем ще раз.

Журнали: SMT читає `Документи\EVE\logs`, підтеки `Chatlogs` і `Gamelogs`. Канал Intel має бути відкритий у клієнті. Іншу теку журналів задають у Файл, Налаштування, Загальні, після цього SMT перезапускають.

## Credit

SMT UA uses the [SMT](https://github.com/Slazanger/SMT) frame by Slazanger. The interface and the tools were rebuilt, and bugs in that frame were fixed. MIT license. Copyright (c) 2023 Slazanger.
