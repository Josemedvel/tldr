# journalctl

> Запити до журналу systemd.
> Більше інформації: <https://manned.org/journalctl>.

- Показати всі повідомлення з рівнем пріоритету 3 (помилки) від цього завантаження:

`journalctl {{[-b|--boot]}} {{[-p|--priority]}} 3`

- Видалити записи журналу, які старіші за 2 дні:

`journalctl --vacuum-time 2d`

- Слідкувати за новими повідомленнями (як `tail -f` для традиційного syslog):

`journalctl {{[-f|--follow]}}`

- Показати всі повідомлення за конкретним блоком:

`journalctl {{[-u|--unit]}} {{блок}}`

- Фільтрувати повідомлення в межах діапазону часу (мітка часу або покажчики місця заповнення, як-от «вчора»):

`journalctl {{[-S|--since]}} {{now|today|yesterday|tomorrow}} {{[-U|--until]}} "{{YYYY-MM-DD HH:MM:SS}}"`

- Показати всі повідомлення за певним процесом:

`journalctl _PID={{pid}}`

- Показати всі повідомлення за певним виконуваним файлом:

`journalctl {{шлях/до/виконуваного_файлу}}`
