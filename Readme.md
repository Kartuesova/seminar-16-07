# Инструкция по работе с Git

## Что такое Git
Git - одна из реализаций распеределенных си`стем контроля версий что позволяет иметь версионность как в локальном репозитории,так и в удаленном (в общем для всех).Git являетсяна данный момент самой популярнойсистемой контроля версий. 

## Подготовка репозитория
 Для создания репозитория используется команда *git init*. В терминале в папке с будущим репозиторием достаточно написать *git init*, и эта папка станет репозиторием. 

## Создание коммита

 ### Добавление файла в коммит
 Для добавления файла в текуций коммит используется команда *git add*. Для этого достаточно в терминале с папкой текущего репозитория написать *git add <название файла>*.

### Сохранение коммита
Ддя сохранения коммита используется команда *git commit*. Для этого в терминалес папкой репозитория необходимо написать команду *git commit -m "<сообщение к коммиту>"*.Сообщение к коммиту писать *** ОБЯЗАТЕЛЬНО***.

## Перемещение между "сохранениями"

## Журнал изменений
Для того чтобы перемещатся между комммитами необходимо использовать команду *git chegkout*. Для этого в терминале с папкой репозиториянеобходимо написать *git checkout <номер коммита>*. Номер коммита  берется изистории изменений. После такого "перемещения" мы попадаем в состояние **Detached head**. Для возвращение в обычное состояние используется команда *git checkout master*.

## Перемещение между "сохранениями"

## Ветки в Git

## Слияние веток и решение конфликтов

## Удаление веток