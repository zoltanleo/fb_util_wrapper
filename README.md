# Leybasoft_base_br



Софтина является GUI-шным wrapper’ом над утилитами СУБД Firebird из его стандартной поставки. Создана для автоматизации рутинных операций по обслуживанию файлов БД.

Список изменений:

v.0.0.10

- добавлено сохранение части настроек в/из xml-файла: по умолчанию сохраняется в локальной папке c:\Users\<User>\AppData\Local\\<project_name>\settings.xml(для Windows) или /home/<user>/.config/<project_name>\settings.xml (для nix)
- добавлены сборки для win x32/x64, linux i386/x86_64, Darwin (x86_64)

v.0.0.2.64

- добавлены statusbar и MainMenu

v.0.0.2.104

- реализован backup

v.0.0.9.249

* полностью реализован backup
* полностью реализован restore
* в sedtRestoreCachSize MinValue выставлено в 1000

v.0.0.9.253

* UTF8StringReplace для смены расширения заменена на ChangeFileExt