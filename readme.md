# Инструкция по работе с Git

## Что такое Git?
***Git*** это наиболее популярная реализация распределённой системы контроля версий. Самая популярная реализация ***Git*** - это [Githab](https://github.com/). 

## Подготовка репозитория
Для создания репозитория необходимо в терминале перейти в пустую папку, где в будущем будет репозиторий. Затем в терминиале с папкой написать команду *git init* 

## Создание коммитов
### Добавление файлов к коммиту
Для добавления файла к будущему коммиту используется команда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add <название файла>*

## Создание коммита
Для создания коммита используется команда "git commit"

## Перемещение между коммитами
Для перемещения на предыдущие коммиты  используется команда *git checkout*. Для этого неоюходимо в журнале изменений, как показано в предыдущем части, найти коммит и его номер. После чего в терминале с папкой-репозиторием написать команду *git checkout <номер коммита>*. После применения этой команды вы попадёте в состояние **Detached head**, в котором никакие изменения фиксироватся не будут. Для возврата в обычное состояние необходимо написать команду *git checkout master*. 

## Журнал изменений
Для просмотра журанала изменений используется команда "git log". Для этого в терминале с папкой-репозиторием необходимо написать "git log"

## Ветки в Git
По сути ветки в Git представляют собой указатель на снимок изменений. Если нужно добавить новую возможность или исправить ошибку (незначительную или серьезную), вы создаете новую ветку, в которой будут размещаться эти изменения. Для создания ветки необходимо в терминале перейти в нужную ветку, от которой будет происходить разветвление. Затем в терминиале с папкой написать команду *git breanch <Название ветки>*

## Слияние веток и разрешение конфликтов
Для слияния журанала изменений используется команда "git merge". Для этого в терминале в ветке к которой необходимо соединить другую пишем "git merge <Назавание веткие которую присоединяем>"


## Удаление веток
Для удаления ветки используется команда "git branch -d". Для этого в терминале с папкой-репозиторием необходимо написать "git branch -d <название ветки>"

## Полезные команды для работы с функционалом
Для просмотра веток используется команда "git log --graph". Для этого в терминале с папкой-репозиторием необходимо написать "git log --graph"

## Семинар 3 придумать что написать
