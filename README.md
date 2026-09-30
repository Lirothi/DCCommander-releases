# DCCommander

Двухпанельный файловый менеджер для Windows 10/11 (x64). Здесь только готовые сборки:
программа сама берёт отсюда обновления.

## Установка

1. Скачайте [DCCommander.zip](https://github.com/Lirothi/DCCommander-releases/releases/latest/download/DCCommander.zip) — это всегда последняя версия.
2. Распакуйте в отдельную папку, например `%LOCALAPPDATA%\Programs\DCCommander`
   (не в `Program Files`: туда без прав администратора обновление не запишется).
3. Запустите `DCCommander.exe`. Файл не подписан, поэтому при первом запуске Windows SmartScreen
   может предупредить: «Подробнее» → «Выполнить в любом случае».

При старте программа просит права администратора, чтобы читать любые папки. Это
отключается в Настройках: «Запускать от имени администратора».

## Обновления

Программа сама проверяет этот репозиторий. Когда выходит новая версия, в заголовке окна
появляется кнопка с её номером: обновление скачивается, проверяется (SHA-256), программа
перезапускается, вкладки и настройки остаются. Предыдущая версия сохраняется, её можно
вернуть в Настройках → Обновления.

---

# DCCommander (English)

A dual-pane file manager for Windows 10/11 (x64). This repository holds the builds only;
the program updates itself from here.

1. Download [DCCommander.zip](https://github.com/Lirothi/DCCommander-releases/releases/latest/download/DCCommander.zip) (always the latest version).
2. Unpack it into a folder of its own, e.g. `%LOCALAPPDATA%\Programs\DCCommander`
   (not `Program Files`: an update could not be written there without administrator rights).
3. Run `DCCommander.exe`. It is not signed, so Windows SmartScreen may warn on the first
   start: "More info" → "Run anyway".

It asks for administrator rights at start, to read any folder; Settings: "Run as
administrator" turns that off. New versions show up as a button in the title bar; the
update restarts the program and keeps the tabs and settings, and the previous version
can be brought back in Settings → Updates.
