***This is first commit***
commit from github!

# [Основные команды Git](https://habr.com/ru/company/ruvds/blog/599929/)

+ **git init** - создание репозитория
+ **git add** - добавление файлов
    + . - добавление всех файлов
    + name.md - добавление файла с именем name.md
   
+ **git status** -  показывает состояния файлов в рабочем каталоге и индексе
+ **git branch** - просмотр веток
    + name - создание ветки name
    + -d name - удаление ветки name

![](снимок.jpg)

+ **git commit** - коммит
    +  -m"Какой-то текст" - с помощью этой команды можно добавить ваш комментарий к коммиту

+ **git log** - просмотр изменений, внесённых в репозиторий

    + **+ --graphgraph** - просмотр истории коммитов в виде графика для текущей ветки

+ **git checkout name** - переход на ветку name

+ **git merge name** - команда для объединения текущей ветки с веткой name

+ **git clone "url"** - команда для копирования удаленного репозитория

+ **git push origin main** - команда для отправки изменений в удалённый репозиторий

+ **git pull** - команда для получения изменений из удалённого репозитория

+ **git push -u origin new_branch** - отправка новой ветки в удалённый репозиторий

+ **git push --delete origin existing_branch** - удаление удалённой ветки
