Задачи к семинарам ВК - МФТИ, по Алгоритмам и структурам данных.

Как выполнить и отправить задание.
----
0. Заполните личные данные в git.
$ git config --global user.name "Ivan Ivanov"
$ git config --global user.email "ivanov.ivan@example.com"

1. Создаёте ветку с именем last_name.first_name, например ivanon.ivan.
$ git checkout -b ivanov.ivan

2. В этой ветке создаёте директории для задач с аналогичным именем и в ней уже ваше решение, например seminar_1/task_1/ivanov.ivan/main.cpp
$ mkdir seminar_1/task_1/ivanov.ivan/
$ # создаёте и наполняете файл seminar_1/task_1/ivanov_ivan/main.cpp в вашем редакторе
$ git add seminar_1/task_1/ivanov.ivan/main.cpp
$ git commit -m "Решил первую задачу"

3. Выполнив таким образом все задачи, которые получилось решить отправляете на сервер.
$ git push origin ivanov.ivan

4. Убедившись что всё верно оформляете pull request. Инструкция как это сделать будет в выводе команды git push.