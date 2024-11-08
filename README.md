# Обучение по программе "Основы работы с Git".
## Шпаргалка команд.

```
cd ~ #Переход в домашнюю директорию
touch NAME.txt  #Создание файла NAME.txt в текущей папке
mkdir my-project #Создание папки с именем my-project в текущей папке
git add #Подготовить файлы к сохранению
git commit #Выполнить коммит
git log #Просмотреть историю коммитов
git remote add #Привязать удалённый репозиторий к локальному
git remote -v #Убедиться, что репозитории связаны
git push #Отправить изменения на удалённый репозиторий
```
## Хеш — идентификатор коммита.
Xеш → информация о коммите/
Они находятся в скрытой папке .git в репозитории проекта.
 ```
 git log #Выводит список коммитов.
 git log --oneline #Получить сокращённый лог.
```
 Клавиша q выход из просмотра логов.
 
##  HEAD — всему голов.
Файл HEAD — один из служебных файлов папки .git. Он указывает на коммит, который сделан последним.
```
cat HEAD #Посмотрtnm содержимое файла HEAD.
```
Внутри HEAD — ссылка на служебный файл: refs/heads/master
