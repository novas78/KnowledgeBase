---
title: Обзор функций
sidebar_position: 1
---

AdGuard для Mac, как один из наших флагманских продуктов, заслуживает полноценного практического руководства. Оно не только поможет новым пользователям разобраться в программе, но и осветит некоторые неочевидные моменты, которые даже давние поклонники AdGuard для Mac могли упустить.

AdGuard для Mac — это независимый блокировщик рекламы для macOS. В отличие от браузерного расширения AdGuard для Safari [с ограниченной Safari Content Blocking функциональностью](https://adguard.com/ru/blog/youtube-ads-in-safari-explained.html), десктопная программа полноценная и может предложить пользователям больше. Давайте посмотрим, какие функции в ней есть.

## Главный экран

![Главный экран](https://cdn.adguard.com/content/kb/ad_blocker/mac/Mainscreen.png)

Первое, что вы увидите после запуска, — это экран с переключателем вкл/выкл. На нём выводится статистика (количество заблокированной рекламы и трекеров, сэкономленного трафика), считая с момента установки или последнего сброса статистики.

Чтобы настроить AdGuard для Mac, нажмите на шестерёнку в верхнем правом углу и выберите «Настройки».

## Общие настройки

![Основные](https://cdn.adguard.com/content/kb/ad_blocker/mac/General.jpg)

Описания опций на скриншоте могут показаться достаточными, но давайте всё же кратко рассмотрим их ниже.

**Автоматически включать подходящие языковые фильтры** Если эта опция выбрана, вам не придётся вручную искать и включать языковые фильтры при посещении сайта на иностранном языке. AdGuard сделает это сам, сэкономив вам немного времени.

**Запускать AdGuard при старте системы** Простая и удобная функция, с которой вам не нужно думать о том, включили ли вы блокировщик, и просто быть уверенными, что реклама всегда блокируется.

**Не блокировать поисковую рекламу и саморекламу сайтов** Эта возможность будет полезна тем, кто делает покупки онлайн: вы можете [разблокировать поисковую рекламу и саморекламу любимых сайтов](/general/ad-filtering/search-ads). AdGuard автоматически распознает её и оставит, а всё остальное, похожее на рекламу, удалит.

**Скрыть иконку меню** Если по какой-то причине вы захотите убрать иконку из панели меню, это можно сделать. Но не волнуйтесь: даже если её спрятать, AdGuard продолжит работать в фоновом режиме.

Из окна Общих настроек вы можете получить доступ к белому списку и добавить в него сайты, которые AdGuard не будет фильтровать. Просто нажмите на соответствующую кнопку, расположенную внизу окна.

## Фильтры

![Фильтры](https://cdn.adguard.com/content/kb/ad_blocker/mac/Filters.jpg)

Фильтры — основная движущая сила модуля блокировки. Чтобы понять, как работает фильтрация, ознакомьтесь [с этой исчерпывающей статьёй](https://adguard.com/ru/blog/how-ad-blocking-is-done.html). Но если коротко, фильтры — это наборы правил, написанных на специальном языке. Блокировщик рекламы интерпретирует эти правила, а затем реализует их. В результате вы перестаёте видеть рекламу на веб-страницах, и жизнь становится намного лучше.

Некоторые фильтры (Базовый фильтр AdGuard, Фильтр раздражителей, EasyList и т. д.) предустановлены, а другие можно добавить дополнительно.

Помимо более общих и универсально применимых фильтров (таких как Базовый фильтр), у AdGuard в арсенале огромное количество фильтров для любого случая:
* фильтры, направленные исключительно на борьбу с отслеживанием (например, фильтр счётчиков и систем аналитики),
* языковые рекламные фильтры, блокирующие контент на выбранном языке,
* фильтры социальных сетей, убирающие кнопки «Мне нравится» и «Поделиться»,
* Annoyances filter for cookie warnings, in-page popups and others of the same ilk,
* и даже фильтр, который разблокирует некоторые объявления, а не блокирует их — фильтр для поисковой рекламы и саморекламы.

Фильтры AdGuard обновляются автоматически. Наши разработчики создают и дополняют их на основе полученных отзывов пользователей. Вы всегда можете помочь другим пользователям AdGuard и в конечном счёте себе тоже, отправив отчёт прямо из приложения Помощника (это очень удобно, позже мы расскажем о нём подробнее) или [с сайта](https://agrd.io/report). Если вы хотите разобраться в фильтрах AdGuard, вот [основная информация](https://kb.adguard.com/ru/general/adguard-ad-filters), которую мы рекомендуем изучить.

## Пользовательские правила

![Пользовательские правила](https://cdn.adguard.com/content/kb/ad_blocker/mac/Filters.jpg)

Ещё одна жизненно важная часть модуля блокировки рекламы — пользовательские правила. Если вы хотите создать свои собственные правила, которые бы лучше соответствовали вашим потребностям, чем стандартные фильтры, можете попробовать в этом свои силы. AdGuard использует для своих правил фильтрации синтаксис, похожий на синтаксис другого блокировщика рекламы, но с дополнениями, существенно расширяющими его возможности. Весь процесс написания правил можно найти в подробных инструкциях, поэтому, если вы хотите освоить синтаксис и научиться создавать свои правила, начните [с этой статьи](https://kb.adguard.com/ru/general/how-to-create-your-own-ad-filters).

## DNS

![DNS](https://cdn.adguard.com/content/kb/ad_blocker/mac/DNS.jpg)

DNS-фильтрация — одна из самых полезных функций, благодаря которой весь ваш DNS-трафик шифруется. Но если вы используете DNS-сервер, предоставленный по умолчанию интернет-провайдером, ваш DNS-трафик, скорее всего, не зашифрован и уязвим для отслеживания и перехвата.

Во вкладке DNS вы можете выбрать DNS-серверы от известных DNS-провайдеров или даже добавить собственные DNS-серверы. Также вы можете добавлять домены в чёрный или белый список DNS и добавлять сложные правила, используя синтаксис правил DNS. Наконец, вы можете [добавить любые DNS-фильтры](https://filterlists.com).

## Антитрекинг

![Антитрекинг](https://cdn.adguard.com/content/kb/ad_blocker/mac/StealthMode.jpg)

Этот модуль — очень полезный инструмент. Он поможет вам сохранить конфиденциальность на сайтах, которые пытаются получить ваши данные: IP-адрес, параметры компьютера, настройки браузера и даже страницу, с которой вы были перенаправлены, не говоря о содержимом корзины в интернет-магазинах. Если этот внушительный перечень информации, которой потенциально могут поделиться с третьими лицами, не заставляет вас подумать дважды, добавим, что многие также узнают о вас такую сугубо личную информацию, как ваш возраст, годовой доход, история болезни, фактический адрес и имена детей. Довольно личные вещи, не правда ли? Устранение нежелательных файлов cookies или тайно добавленных в ваш браузер параметров отслеживания — вот, что Антитрекинг умеет лучше всего.

Благодаря широкому набору опций Антитрекинг гибко настраивается. Они разделены на несколько категорий и для неподготовленного пользователя покажутся запутанными и, возможно, даже сложными. Мы снабдили каждую опцию подсказкой — под каждой из них вы найдёте небольшое описание серым цветом. Если вы хотите узнать больше об Антитрекинге, рекомендуем почитать о нём [в отдельной статье](https://kb.adguard.com/ru/general/stealth-mode).

## Антифишинг

![Безопасность](https://cdn.adguard.com/content/kb/ad_blocker/mac/BrowsingSecurity.jpg)

Следующей идёт вкладка «Безопасность». Здесь можно включить защиту от фишинга и вредоносных программ.

> Но имейте в виду, что AdGuard — это не антивирус, а совершенно другая программа. Он предупредит вас, если вы попадёте на заражённый домен, но не остановит вас от скачивания чего-то подозрительного и не поможет избавиться от уже существующего вируса. Фишинг — это очень распространённый вид веб-мошенничества, направленный на кражу персональных данных (паролей, реквизитов банковских счетов и т. д.). В нём используются поддельные веб-страницы, имитирующие популярные сайты или сервисы, такие как интернет-магазины или социальные сети. У многих фишинговых сайтов есть URL-адреса, которые отличаются от реальных всего несколькими символами, чтобы сбить вас с толку. Если пользователь введёт свои данные на таком сайте, они окажутся в чужих руках.

Модуль безопасности защитит вас от таких инцидентов. При этом персональная информация никуда не передаётся и серверы AdGuard не знают, какие сайты посещает пользователь, поскольку проверка безопасности осуществляется не через открытый веб-адрес (URL), а через префиксы хешей (хеш — это определённая структура данных, которая проверяет каждый добавленный в базу адрес).

Некоторые страницы сами по себе не несут вред, но могут содержать элементы, встроенные в их структуру другими сайтами. В отличие от плагинов браузера, модуль безопасности проверяет каждый объект, встроенный в страницу, обеспечивая максимальную защиту.

Если вы хотите помочь нам в совершенствовании этого модуля, можете поставить галочку рядом с фразой «Помогите нам в развитии фильтров антифишинга». Тогда с вашего компьютера будет отправляться информация о мошеннических сайтах, на которые вы можете наткнуться в интернете, и наши разработчики удостоверятся, что они окажутся заблокированными.

## Браузерный помощник

![Помощник](https://cdn.adguard.com/content/kb/ad_blocker/mac/BrowserAssistant.jpg)

Основная функция Браузерного Помощника — это управление фильтрацией прямо из браузера. Раньше он был обычным пользовательским скриптом, встроенным в AdGuard for Mac, а потом превратился в полноценное браузерное расширение. Узнайте больше о [его преимуществах](https://kb.adguard.com/ru/macos/overview/browser-assistant).

![Всплывающее меню Помощника](https://cdn.adguard.com/content/kb/ad_blocker/mac/safari_assistant_pop-up_menu.jpg)

При первой установке AdGuard вам предложат установить Браузерный помощник для браузера по умолчанию. Если вы пропустили этот шаг, можно [скачать его для любого браузера](https://adguard.com/ru/adguard-assistant/overview.html) в любое время.

## Расширения

![Расширения](https://cdn.adguard.com/content/kb/ad_blocker/mac/Extensions.jpg)

Расширения — это небольшие программы, которые делают именно то, что подразумевает их название: расширяют функциональность. AdGuard использует несколько собственных расширений, также называемых пользовательскими скриптами, чтобы расширить диапазон своих функций:

**1. 1. Помощник AdGuard** (старая версия) Мы дали расширению такое название намеренно: оно помогает пользователю изменить базовые настройки AdGuard внутри браузера без необходимости открывать приложение. Помощник AdGuard работает со всеми браузерами, совместимыми с macOS. Благодаря этому маленькому инструменту вы можете делать в браузере много вещей: добавлять веб-страницу в белый список, убирать раздражающие элементы на страницах, отправлять жалобы на сайт, например, в случае пропущенной рекламы.

> Обратите внимание, что это устаревшая версия Помощника и нет смысла использовать её на новых системах, потому что её давно заменил Браузерный помощник. Но старый Помощник может пригодиться, если для вашего браузера нет расширения Браузерного помощника.

**2. 2. AdGuard Extra** Это расширение используется, чтобы решать более сложные случаи блокировки рекламы, с которыми вы могли столкнуться. Мы рекомендуем всегда держать его включенным, если у вас нет серьёзной причины не делать этого.

**3. Блокировщик всплывающей рекламы AdGuard** Не даёт раздражающим всплывающим окнам маячить у вас перед глазами, когда вы открываете веб-страницы. Блокирует всплывающую рекламу на страницах.

Одна из важных особенностей AdGuard для Mac — приложение может работать как менеджер пользовательских скриптов для различных браузеров. Вы можете легко добавлять любые скрипты и управлять существующими без необходимости каждый раз переключать браузер.

## Сеть

![Сеть](https://cdn.adguard.com/content/kb/ad_blocker/mac/NetworkFiltering.jpg)

Фильтрации сети посвящена последняя вкладка, на ней вы найдёте расширенные функции. Рекомендуем держать включенными первые две опции: «Автоматически фильтровать трафик приложений» и «Фильтровать HTTPS-протокол» — по сути это основная защита для вашего интернета. Это важная дополнительная мера предосторожности для лучшей фильтрации веб-пространства. HTTP — это основной протокол для передачи информации через интернет. Через него передаётся большинство данных, включая рекламу, но у него есть один недостаток — соединение не шифруется. Благодаря функции HTTPS-фильтрации, AdGuard фильтрует не только HTTP-, но и HTTPS-трафик (S означает «безопасный»).

Также есть опции «Не фильтровать сайты с EV-сертификатами» и «Использовать AdGuard в качестве HTTP-прокси». EV-сертификаты (от англ. Extended Validation — «расширенная валидация») дают более надёжную гарантию; владельцы таких сайтов должны пройти подробный и всемирно стандартизированный процесс проверки личности, определённый руководящими принципами EV. Именно поэтому некоторые пользователи доверяют сайтам с такими сертификатами и предпочитают не фильтровать их.

Что касается второго варианта — да, фактически вы можете использовать AdGuard в качестве обычного прокси-сервера. Весь трафик, проходящий через него, будет отфильтрован. Этот прокси-сервер также будет доступен в локальной сети, поэтому вы можете использовать его для фильтрации трафика на других устройствах, которые могут напрямую связаться с прокси-сервером. Для фильтрации трафика на другом устройстве, подключённом к прокси, вам потребуется установить корневой сертификат AdGuard. После настройки прокси откройте браузер и перейдите на [эту страницу](http://local.adguard.org/cert).

## Другое

У AdGuard есть другие полезные функции, которые не могут остаться незамеченными, поскольку благодаря им пользоваться программой значительно удобнее.

### Лицензия

First, there's the License tab that you can open from the dropdown main menu (the one that opens once you click the gear icon on the upper right of the main window). Здесь вы можете увидеть, какой тип лицензии используете, проверить её статус и срок действия.

![Лицензия](https://cdn.adguard.com/content/kb/ad_blocker/mac/License.jpg)

В этой же вкладке вы можете обновить статус лицензии, её саму или сбросить лицензионный ключ.

### Поддержка

Нажмите на шестерёнку в правом верхнем углу, выберите «Поддержка», и вы сможете отправить нашей команде техподдержки отчёт об ошибке или запрос на добавление функции. Не забудьте добавить ваш действующий адрес электронной почты, потому что без него сообщение не будет отправлено.

![Поддержка](https://cdn.adguard.com/content/kb/ad_blocker/mac/Support.jpg)

Чтобы сообщить о пропущенной рекламе или сломанном сайте, перейдите по ссылке над окном сообщения — мы используем отдельный инструмент отчётности для этой категории вопросов.

Если возможно, прикрепите к сообщению отчёт о результатах диагностики. Для этого нужно поставить галочку в нижней части вкладки.

### Проверка обновлений

И последнее, но не менее важное. Вы можете проверить обновления фильтров и самой программы, просто нажав на соответствующие пункты в выпадающем меню (кликните на иконку шестерёнки, и вы их увидите).