#BankReportAnalyzer

## <img src="http://upload.wikimedia.org/wikipedia/en/thumb/f/f3/Flag_of_Russia.svg/320px-Flag_of_Russia.svg.png" align="left" height="36" width="72">&nbsp;РУС

Консольное приложение для базового анализа финансовой стабильности банка.

###Использование:

1. Запустить исполняемый файл `./banalyzer`
2. Указать номер лицензии банка (обычно это число из 4 или меньше символов)

Данные берутся с сайта <a href="http://www.cbr.ru">www.cbr.ru</a>, необходимо активное интернет соединение.

###Пример отчёта:

<img src="https://leto14d.storage.yandex.net/rdisk/40699830ca3571178706a886e7bb0450/mpfs/u2KSpr4-EO-GaVdktNsBo-fn2ABf3htANjzQofRfSbkMmI91BnqgsEzkc2OJBy10HyRl2Ic5DQslm68ooCTw0w==?uid=0&filename=2014-12-22%2012-13-22%20Finance%20%E2%80%94%20Python%20%E2%80%94%20167%C3%9742.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&rtoken=949390bd3a691731882e84e07b18c59b&rtimestamp=5497e104&force_default=no">

*	Н1 – норматив достаточности капитала. Отношение  собственных  средств  банка  к  суммарному  объему  активов,  взвешенных  с  учетом  риска. >10%
*	Н2 – мгновенная ликвидность. Доля собственных обязательств, которые банк сможет исполнить за день, продав активы. >15%
*	Н3 – текущая ликвидность. Доля собственных обязательств, которые банк сможет исполнить за 30 дней, продав активы. >50%
*	Н4 – норматив долгосрочной ликвидности. Отношение долгосрочных активов банка к сумме к сумме собственного капитала и краткосрочных обязательств. <120%
*	Н7 – максимальные крупные кредитные риски. Отношение крупных кредитных рисков (>5% капитала банка). <800%
*	Н9.1 – кредитные гарантии акционерам. Отношение суммы кредитных гарантий банка, выданных акционерам к капиталу. <50%
*	Н10.1 – совокупный риск по инсайдерам банка. Отношение кредитных требований к инсайдерам банка к капиталу. <3%
*	Н12 – использование капитала для приобретения акций. <25%

В столбце `отчётность` показана оценка состояния финансовых нормативов за отчётный период. `[ok]` - нормы ЦБ соблюдаются. `[danger]` - нормы ЦБ не соблюдены.

## <img src="http://upload.wikimedia.org/wikipedia/en/thumb/a/ae/Flag_of_the_United_Kingdom.svg/320px-Flag_of_the_United_Kingdom.svg.png" align="left" height="36" width="72">&nbsp;ENG

Console utility to check financial stability of russian banks.

###Usage:

1. run `./banalyzer`
2. enter bank registration number (usually consists of 4 or less numeric characters)
