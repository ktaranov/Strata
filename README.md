##### Strata — раскладка клавиатуры для тех, кто любит Markdown и пишет по-русски

[<img src="https://habrastorage.org/files/95c/796/f17/95c796f1789f485cb719d55c21a63519.jpg"/>](https://habrastorage.org/files/95c/796/f17/95c796f1789f485cb719d55c21a63519.jpg)

Я сделал эту раскладку для того, чтобы исключить постоянную смену языков во время набора русских текстов использующих разметку [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Теперь символы вроде **#, < >, [ ]** всегда на кончиках пальцев.

Подсвеченные в шпаргалке символы вводятся с зажатой клавишей AltGr (т.н. "Правый Альт"). Для ввода символов из верхней строки вместе с AltGr нужно зажать ещё и Shift. Например **AltGr+3** дадут **#**, а **AltGr+Shift+3** дадут **⅓** — всё просто. Для поддержания консистентности в архиве две раскладки — для русского и английского языков.

[Скачать дистрибутив для Windows →](https://github.com/Atarity/Strata/releases/download/v0.1/Strata.Markdown.Layout.Installer.v01.zip)

### FAQ
**При попытке ввести кое-какие символы через AltGr некоторые приложения ведут себя странно. Почему?**

>На самом деле AltGr это не какая-то особенная кнопка и фактически в Windows является просто сочетанием клавиш Alt+Ctrl. Поэтому, если вы, например, пытаетесь вводить знак § в приложении, которые использует сочетание Alt+Ctrl+G для быстрого доступа к каким-то собственным функциям, то, скорее всего, это сочетание будет интерпретировано дважды: как горячая клавиша и как §. Если для вас это огромная проблема, существует [совсем замороченное решение](http://superuser.com/questions/592970/can-i-make-ctrlalt-not-act-like-altgr-on-windows).

**Как ставить ударение?**

>Кнопка с ударением неспроста имеет особый вид в шпаргалке. Она относится к так называемым [мёртвым клавишам](https://ru.wikipedia.org/wiki/%D0%9C%D1%91%D1%80%D1%82%D0%B2%D1%8B%D0%B5_%D0%BA%D0%BB%D0%B0%D0%B2%D0%B8%D1%88%D0%B8) и работает особенным образом позволяя вносить модификацию почти в любой печатаемый символ. Использовать её проще всего так: введите символ над которым хотите увидеть ударе́ние и затем дважды нажмите AltGr+Shift+/ .

**Мне крайне нобходима буква Ѣ и ∫ и обязательно 💩. Что делать?**

>Репозиторий состоит всего из двух файлов с расширением .klc — это конфиги для утилиты [Microsoft Keyboard Layout Creator](http://www.microsoft.com/en-us/download/details.aspx?id=22339). С её помощью вы можете самостоятельно изменить раскладку для Windows. Шлите пул-реквесты и оставляйте тикеты, если вам кажется, что вы сделали что-то важное.

*Эта раскладка основана на [Типографской Раскладке Ильи Бирмана](http://ilyabirman.ru/projects/typography-layout/). Правда "типографского" в ней почти ничего не осталось.)*

