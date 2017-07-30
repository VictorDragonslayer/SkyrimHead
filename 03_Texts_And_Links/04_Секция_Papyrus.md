# Секция [Papyrus] в файле Skyrim.ini

Для лучшего понимания темы рекомендуется сначала прочитать эти материалы:
+ [Гайд на Реддите](https://www.reddit.com/r/skyrimmods/comments/2gwvwl/guide_papyrus_ini_settings_and_why_you_shouldnt/)
+ [Пост на BethSoft](http://forums.bethsoft.com/topic/1487930-getting-a-lot-of-script-lag-going-over-10000-ms-sometimes/?p=23340131)
+ [Раздел на STEP'е](http://wiki.step-project.com/Guide:Skyrim_INI/Papyrus)
+ [Статья на сайте CK](http://www.creationkit.com/index.php?title=INI_Settings_(Papyrus))

Небольшое пояснение по принципу именования параметров: первая буква обозначает тип, т.е. b - Bool, f - Float, i - Integer и т.д. Если параметр в файле конфигурации не написан, то используется значение по умолчанию.

------

> bEnableLogging  
> bEnableProfiling  
> bEnableTrace  
> bLoadDebugInformation  
> uTraceStatusOfQuest

Эти параметры нужны для записи отладочной информации в логи Папируса. Если ты не тестируешь свой мод и уверен, что у тебя не переполняется стек, держи эти параметры выключенными. И знай, что **логи Папируса не являются логами краша игры**, а вот операция записи в файл забирает ресурсы.

------

