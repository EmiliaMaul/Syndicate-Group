# Syndicate-Group
Скрипты, которые используются для предобработки файлов, предназначенных для объединения в итоговый отчет

Ежедневный отчет о промежуточных результатах залива трафика содержит информацию, которую необходимо собирать из разных источников, где она хранится в разном формате.
Чтобы привести все к единому виду, объединить и создать сводку с основными показателями, используется эксель, который хорошо справляется с этой задачей, однако для ускорения процесса, можно использовать код. Это сильно экономит время, не теряя в качестве.

activity_table - из файла Activity Table, требуется добыть информацию о количестве конверсий по каждому байеру, чтобы установить соответствие с количеством конверсий в отчете из другого источника.

daily_report_cost_currency - с помощью кода данные о цене и валюте оплачиваемых конверсий подтягиваются из одной таблицы в другую - в таблицу для создания ежедневного отчета.
