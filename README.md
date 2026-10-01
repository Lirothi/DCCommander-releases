# DCCommander

Двухпанельный файловый менеджер для Windows 10/11 (x64). Здесь только готовые сборки:
программа сама берёт отсюда обновления.

## Установка

1. Скачайте [DCCommander.exe](https://github.com/Lirothi/DCCommander-releases/releases/latest/download/DCCommander.exe) — это всегда последняя версия, один файл.
2. Запустите его. Файл не подписан, поэтому Windows SmartScreen может предупредить:
   «Подробнее» → «Выполнить в любом случае».
3. Программа предложит установиться: в `%LOCALAPPDATA%\Programs\DCCommander`, с ярлыком в
   меню «Пуск». После этого скачанный файл можно удалить. Если нажать «Запускать отсюда»,
   программа останется там, где лежит, и обновляться будет там же (только не в `Program
   Files`: туда без прав администратора обновление не запишется).

Права администратора не нужны. Если хочется читать любые папки (в том числе чужие и
системные), включите в Настройках «Запускать от имени администратора»: тогда Windows
будет спрашивать при каждом старте.

## Обновления

Программа сама проверяет этот репозиторий. Когда выходит новая версия, в заголовке окна
появляется кнопка с её номером: обновление скачивается, проверяется (SHA-256), программа
перезапускается, вкладки и настройки остаются. Предыдущая версия сохраняется, её можно
вернуть в Настройках → Обновления.

---

# DCCommander (English)

A dual-pane file manager for Windows 10/11 (x64). This repository holds the builds only;
the program updates itself from here.

1. Download [DCCommander.exe](https://github.com/Lirothi/DCCommander-releases/releases/latest/download/DCCommander.exe) (always the latest version, one file).
2. Run it. It is not signed, so Windows SmartScreen may warn: "More info" → "Run anyway".
3. It offers to install itself into `%LOCALAPPDATA%\Programs\DCCommander` with a Start menu
   shortcut; the downloaded file can go afterwards. "Run from here" keeps it where it is,
   and it updates there (not in `Program Files`: an update could not be written there
   without administrator rights).

It needs no administrator rights; Settings: "Run as administrator" makes it read any
folder (Windows then asks at every start). New versions show up as a button in the title
bar; the update restarts the program and keeps the tabs and settings, and the previous
version can be brought back in Settings → Updates.
