В файле skyrim.ini Имеется секция [Papyrus], и сейчас я коротко расскажу, какие в ней стоит трогать, а какие - нет. Советую прочесть [1](https://www.reddit.com/r/skyrimmods/comments/2gwvwl/guide_papyrus_ini_settings_and_why_you_shouldnt/), [2](http://forums.bethsoft.com/topic/1487930-getting-a-lot-of-script-lag-going-over-10000-ms-sometimes/?p=23340131) и [3](http://wiki.step-project.com/Guide:Skyrim_INI/Papyrus), дабы наиболее полно понять тему.


Пояснение по принципу именования параметров: префикс (первая буква) означает его тип, т.е. b - bool, f - float, i - integer и т.д.

> bEnableLogging 
bEnableProfiling
bEnableTrace 
bLoadDebugInformation

Нужны для записи отладочной информации в логи Папируса. Если ты не тестируешь свой скрипт и не подозреваешь, что у тебя переполняется стек, держи эти параметры выключенными. Логи Папируса **не являются** логами краша игры, а вот операция записи в файл забирает ресурсы.
