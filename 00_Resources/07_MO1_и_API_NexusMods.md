# MO1 и API NexusMods

9 мая 2018 NexusMods изменил API, с которым связаны логин, скачивание и проверка обновлений модов ([ссылка на новость](https://www.nexusmods.com/site/news/13481)). Данный короткий гайд поможет вернуть Mod Organizer версии 1.3.11 в рабочее состояние.

+ **Опционально**:
    + Открой командную строку Windows: Win+R ➔ cmd ➔ Enter.
    + Проведи пинг нового API: `ping legacy-api.nexusmods.com`.
    + Получи новый IP (на момент написания - 77.72.3.39).
+ Открой файл HOSTS, который находится по адресу "C:\Windows\System32\drivers\etc". Сделай это от имени администратора; убедись, что файл доступен для записи.
+ Внеси в конец файла запись `77.72.3.39 nmm.nexusmods.com # legacy-api.nexusmods.com`.
+ Таким образом, твой ПК будет перенаправлять запросы к nmm.nexusmods.com на 77.72.3.39, где находится legacy-api.nexusmods.com.
+ Если IP изменится, то выполни действия из пункта **Опционально**.

[Источник на Reddit](https://www.reddit.com/r/skyrimmods/comments/8ibbu4/classic_login_fix_for_mo1nmm_no_update_needed/).

------

|[*Назад к основному порядку действий*](../01_Minimum/03_Основной_порядок_действий.md)|
|:---:|
