# ManualDZ
Работа с github
РУКОВОДСТВО ПОЛЬЗОВАТЕЛЯ GID
## 1. Локальный репозиторий
* git init инициализация репозитория
* git status показать состояние репозитория
* git diff сравнить рабочую директорию и индекс
* git add fail добавление файла
* git commit -m "" сохранение репозитория и сообщения
* git commit -am "" объединяет две команды add и commit
* git log журнал изменений
* git checkout возможность перемещения через версию
* git checkout master возвращает на главную ветку (версию)
## 2. Работа с ветками
* git branch "Name" добавление ветки
* git merge "Name" слияние веток
* git branch -d naem удалить ветку (используется, если её изменения уже влиты
 в главную ветку)
* git checkout -b "name" создание и переход по веткам
* git branch список веток
* git log --graph графический журнал изменений
## 3. Работа с удаленным репозиторием
## Для создание удаленного репозитория
* echo ***название репозитория на github*** README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin -***ссылка на репозиторий из github***
* git push -u origin main
## Для переноса готового репозитория на github 
* git remote add origin -***ссылка на удаленный репозиторий***
* git branch -M main
* git push -u origin main
### Для переноса репозитория из github 
* git pull переносит из удаленного репозитория
* git clone -***ссылка на репозиторий который хотим с клонировать***
### как делать форк руководителю
Заходим на github делаем forc интересующего репозитория клонируем 
его себе с помощью команды
