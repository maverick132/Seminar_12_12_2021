# Инструкция по работе с Git и удаленными репозиториями.

## Что такое Git?

Git - одна из реализаций систем контроля версий, имеющая как локальную версионность, так и версионность на сервере. Git является самой популярной системой контроля версий на сегодняшний день.

## Подготовка репозистория

Для того, чтобы создать репозиторий в указанной папке, используется команда *git init*. Для этого достаточно написать команду *git init* в папке с будущем репозиторием.

## Создание фиксаций

### Просмотр информации об изменениях

Для того, чтобы посмотреть информацию об изменениях сделанных в текущей ветке, необходимо использовать команду *git status*. Для этого достаточно использовать команду *git status* в папке с репозиторием.

### Добавление файла к коммиту

Для того, чтобы добавить файл к новому коммиту ("сохранению") необходимо использовать *git add*. Используется она следующим образом: в папке с репозиторием пишем команду *git add <имя файла>*.

### Создание коммитов

Для создания новой фиксации, необходимо использовать команду *git commit*. Используется она следующем образом: в папке с репозиторием пишется команда *git commit -m "<сообщение к коммиут>"*. Все файлы должны быть предварительно добавлены с помощью команды *git add*. Сообщение к комиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями

Для перемещения между коммитами, необходимо использовать команду *git checkout*. Используется она следующем образом в папке с репозиторием: *git checkout <номер коммита>*.

## Журнал изменений

Для просмотра журнала изменений, необходимо использовать команду *git log*. Для этого нужно в папке с репозиторием напистаь *git log*.

## Ветки в Git

### Просмотр списка веток

Для того, чтобы просмотреть список веток, необходимо использовать команду *git branch*. Для этогов папке с репозиторием надо набрать *git branch*.

### Создание веток в Git

Для того, чтобы создать новую ветку, необходимо использовать команду *git branch*. Используется она следующим образом в папке с репозиторием: *git branch <название ветки>*.

### Переход между ветками

Для того, чтобы перейти на другую ветку, необходимо использовать команду *git checkout*. Используется она следующим образом в папке с репозиторием: *git checkout <название ветки>*.

## Слияние веток и разрешение конфликтов

### Слияние веток

Для слияния веток, необходимо использовать команду *git merge*. Используется она сдедующим образом: для начала ***ОБЯЗАТЕЛЬНО*** перейти на ветку, куда мы сливаем изменения, после чего надо воспользоваться командой *git merge <название сливаемой ветки>*. Слияние может произойти автоматически, а может возникнуть конфликт. Про разрешение конфликтов смотри дальше.

## Удаление веток
