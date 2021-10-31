# devops-netology Сергей Леонов

## Задание 1 (Задание №1 – Знакомимся с gitlab и bitbucket)

Зарегестрировал и подключил gitlab и bitbucket.<br/>
- [Gitlab](https://gitlab.com/androidsmike/)
- [Bitbucket](https://bitbucket.org/androidsmike/)

В ходе этого задания использовал: 
- `git remote add [link]` - подключение удаленного репозитория;
- `git remote -v` - вывод подключенных репозиториев;
- `git push -u [link] [name branch]` - обновление удаленных репозиториев с локальными данными. 

## Задание 2 (Теги)
Создал теги и добавил их на все три удаленных репозитория.<br/>
В ходе этого задания использовал: 
- `git tag [name tag]` - создание "легкого тега";
- `git tag -a [name tag] -m [annotation]` - добавление тега с аннотацией;
- `git push [name remote rep] [name tag]` - пуш тега в удаленные репозитории;
вместо [name tag] можно использовать `--tags`, чтобы пропушить все теги.

## Задание 3 (Ветки)
Переключился на коммит [prepare to delete and move](https://github.com/AndroidSmike/devops-netology/commit/751957ce710e1a35cba5982a48f49e64fdb7dfef) и создал ветку [fix](https://github.com/AndroidSmike/devops-netology/tree/fix).
Внес изменения в файл README.md и отправил изменения в репозиторий.<br/>В ходе этого задания использовал:
- `git log` - вывод лога по комитам;
- `git checkout` - переключение на нужный коммит;
- `git switch -c [name branch]` - создание и переключение на новую ветку;

## Задание 4 (Упрощаем себе жизнь)
Задание 4 выполнил в PyCharm и запушил в ветку main github.

