# Фикс багов «Pathfinder: Wrath of the Righteous»

Данный OMM-мод (Owlcat Modifications Manager) исправляет известные баги игры [Pathfinder: Wrath of the Righteous](https://store.steampowered.com/app/1184370/Pathfinder_Wrath_of_the_Righteous__Enhanced_Edition/).

Данные мод не исправляет баги мифических заклинаний. Для этого существуют другие моды:
- мод, исправляющий баги мифических заклинаний — https://github.com/Nieroo/WotRMythicSpellsFix
- мод, добавляющий крафт мифических заклинаний — https://github.com/Nieroo/WotRMythicSpellsCraft

На данный момент мод поддерживает полностью русскую локализации игры и частично английскую.

Мод вносит зависимость в сейв-файл и если при наличии данного мода создан сейв, то загрузить его без данного мода не получится.

## Установка (для Windows)

1. Со страницы [релизов](https://github.com/Nieroo/WotRYogurtFixes/releases) скачайте архив с последней версией мода.
2. Перейдите в папку `%localappdata%low\Owlcat Games\Pathfinder Wrath Of The Righteous` (далее — папка игры).
3. Распакуйте из архива папку `Modifications` в папку игры.
4. Если в папке игры нет файла `OwlcatModificationManagerSettings.json`, то извлеките его в папку игры из архива.
5. Если в папке игры уже есть файл `OwlcatModificationManagerSettings.json`, то отредактируйте его: найдите массив `EnabledModifications` (или создайте на верхнем уровне, если его нет) и добавьте в него значение `YogurtFixes`.
6. Если мод установлен правильно, то в игре при нажатии `Ctrl+M` в окне OMM можно увидеть название мода

## Список изменений

Ознакомиться со списком внесённых изменений можно в файле [CHANGELOG.md](https://github.com/Nieroo/WotRYogurtFixes/blob/main/CHANGELOG.md).
