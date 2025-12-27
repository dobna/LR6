# Лабораторная работа №6
# Цель лабораторной работы
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

# Ход работы
Сначала необходимо было сделать форк репозитория на ноутбук:

![](screenshots/fork.jpg)
![](screenshots/fork2.jpg)
![](screenshots/fork_res.jpg)

Сделали копию и настроили клиент git:

![](screenshots/git_clone.jpg)

Создали файл через интерфейс github и пдгрузили изменения в локальный репозиторий:

![](screenshots/add_file.jpg)
![](screenshots/git_pull.jpg)

Посмотрели историю операций и последние изменения:

![](screenshots/git_log.jpg)
![](screenshots/git_show.jpg)

Создали ветку и изменили файл в ней и в мастере, чтобы создать конфликт:

![](screenshots/create_mergefile1.jpg)
![](screenshots/create_mergefile.jpg)

Попытка слияния веток для вызова конфликта:

![](screenshots/try_merge_conf.jpg)
![](screenshots/conflict.jpg)

Открываем файл в текстовом редакторе и меняем его:

![](screenshots/test_conf.jpg)

Пробуем слить ветки теперь:

![](screenshots/resolve_conf.jpg)

Удаляем побочную ветку:

![](screenshots/revert_branch.jpg)

Делаем дополнительные изменения и сохраняем их:

![](screenshots/git_log_11.jpg)

