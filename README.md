# OLX Phishing Kits (POC)
Фішинговий кіт - це зловмисний електронний ресурс, який містить шкідливий код, що дозволяє автоматизувати проведення незаконних операцій та афер в інтернеті з використанням технік соціальної інженерії та фішингу. <br><br>
Нижче представлені зразки шкідливого коду, які публікуються в рамках кіберрозслідування командою KR. LABORATORIES шахрайських схем на платформі OLX.UA:
- Копія фішингового кіту 1 (``olx_phishing_mirror_sample1.html``) була знята 06.11.2024 з оригінального джерела, виявленого 05.11.2024 за URL-адресою https://hegpo.pages.dev/link_card/af29d8bc (Вебархів - https://web.archive.org/web/20241106065434/https://hegpo.pages.dev/link_card/af29d8bc).
- Копія фішингового кіту 2 (``olx_phishing_mirror_sample2.html``) була знята 06.11.2024 з оригінального джерела, виявленого 05.11.2024 за URL-адресою https://guardelly-poluchenyeuah.pages.dev/248319426 (Вебархів - https://web.archive.org/web/20241106073955/https://guardelly-poluchenyeuah.pages.dev/248319426).

Метою зловмисників є заволодіти коштами користувачів платформи OLX.UA. Шахраї з фейкових акаунтів масово надсилають користувачам OLX у месенджер Viber фішингові повідомлення з посиланнями нібито на OLX-доставку, яку вони оформили. Користувач переходить, думаючи що це легітимний сайт, де йому пропонується ввести дані своєї банківської картки для отримання вже нібито оплаченого товару, який у нього замовили в рамках послуги "OLX Доставка". Платіжні дані після цього через API потрапляють до злочинців. Далі зловмисники просто зламують банкінг і виводять кошти на свої рахунки. Атаки проводяться з територій рф, а також окупованих ордло. Мільйони українців були пограбовані за час існування цієї схеми. 

### Дисклеймер:
- Публікується як факт інтернет-злочину, від якого постраждали і страждають громадяни України.
- Публікується з метою ведення незалежного слідства, зібрання доказової бази та деанонімізації авторів зловмисного коду, приведення їх до відповідальності.
- Публікується з метою привернення уваги усіх компетентних осіб, служб безпеки інтернет-провайдерів України та хмарних постачальників, чиї сервіси і технології були використані у шахрайським схемах: Cloudflare, OLX, Crisp Chat, Viber, Google тощо.
- Публікується виключно в ознайомлювальних цілях з метою дослідження експертами кібербезпеки і цифрової форензики, передачі фактів командам CERT та Incident Response, внесенням інтернет-провайдерами та хмарними постачальниками у всі можливі бази і чорні списки, а також для компрометації та унеможливлення подальшого використання цього шкідливого коду проти народу України.
- Публікується з метою розроблення методик і механізмів протидії зловмисним електронним ресурсам. Проєктування кібер-пошукових та Анти-fraud систем.
- Публікується в рамках волонтерського проєкту "За вільний та безпечний УАРНЕТ!". Наша основна мета у цьому кейсі - покласти край шахрайству, яке процвітає вже більше 10 років на майданчику електронної комерції OLX.UA.
### Зняття відповідальності:
- Наголошуємо, що законами України та міжнародним правом забороняється використовувати цей шкідливий код у будь-яких протиправних цілях, окрім ознайомлення, навчання, демонстрації шахрайських схем, розслідування.
- Власники даного репозиторію жодним чином не підтримують, не сприяють і не заохочують будь-яку незаконну діяльність, включаючи фішинг та інші форми кіберзлочинності.
- Використання матеріалів проекту здійснюється на власний ризик. Ми не несемо відповідальності за будь-які дії, що були вчинені третіми особами з використанням інформації, наданої в рамках цього проекту.
- Перед використанням будь-якої інформації з цього проекту для дослідницьких або навчальних цілей, переконайтеся, що ваші дії відповідають місцевим законам, нормативно-правовим актам та регуляціям.
### Контакти
Якщо у вас є питання або пропозиції, ви можете зв'язатися з нами за електронною адресою: security@kr-labs.com.ua
