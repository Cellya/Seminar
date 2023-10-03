# First Seminar
* git init - инициализация локального репозитория
* git ststus - получение информации о тек. состоянии
* git add - добавление файла
* git commit -m "message" - создание коммита
* git log - вывод истории коммитов
* git checkout _num_commit_ - переход к коммиту по его номеру _num_commit_(мин 4 символа)
* git checkout master - возвращение к актуальной версии
* git diff - вывести разницу м/д тек. файлом и закоммиченым


# Second seminar
22.09.2023
## Создание веток
* git branch _branch_name_ - создать новую ветку
## Слияние веток
* git merge _branch_name_ - слияние активной ветки с веткой _branch_name_
## Конфликты при слияниях
* Конфликты когда возникают, когда затронуто общее рабочее пространство!!!
## Удаление веток
* git branch -d _branch_name_ - удаление ветки _branch_name_, только если она слита
* git branch -D _branch_name_ - удаление ветки _branch_name_
## Log с показанными ветками
* git log --graph - выводит лог и показывает ветки