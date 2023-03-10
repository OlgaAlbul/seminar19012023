# Инструкция по работе с Git и удаленными репозиториями

## Что такое Git?
***Git*** - это одна из реализаций распределенной системы контроля версий, поддерживающие как локальные, так и удаленные репозитории. Самая популярная реализация Git - это [GitHub](https://github.com)
## Подготовка репозитория
Для создания репозитория используется команда *git init*. Для этого необходимо открыть в терминале папку с будущим репозиторием и там написать *git init*

## Создание коммитов

### Выполнение коммита
Для того,чтобы выполнить коммит используется команда *git commit*. Для этого в терминале с папкой-репозиторием необходимо написать *git commit -m <сообщение к коммиту>*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО!!!***.

### Добавление файла к коммиту
Для добавления файла к коммиту используется команда *git add .*. Для этого в терминале с папкой-репозиторием необходимо написать *git add . <название файла>*.

## Журнал изменений
Для просмотра журнала изменений используется команда *git log*. Для этого  в терминале с папкой-репозиторем пишем *git log*. В показанном журнале будут:
* Хэш(номер) коммита
* Дата и время коммита
* Автор коммита
* Текст сообщения к коммиту

## Перемещение между коммитами
Для перемещения между коммитами используется команда *git checkout*. Для этого в терминале с папкой-репозиторием необходимо написать *git checkout<хэш коммита>*. Хэш коммита можно взять из истории коммитов, про которую было рассказано в предыдущем пункте.


## Ветки в Git

### Создание веток
Для создания новой ветки используется комманда *git branch*. Для этого в терминале с папкой-репозиторием необходимо написать *git branch <название ветки>.

### Перемещение между ветками
Для перемещения между ветками используется описанная выше комманда *git checkout*. С той разницей что после команды пишется не хэш коммита, а название ветки. Для этого в терминале с папкой-репозиторием необходимо написать *git checkout <название ветки>*.

## Слияние веток и разрешение конфликтов

Для слияния веток используется комманда *git merge*. Перед слиянием веток необходимо убедиться что всме изменения в ветке сохранены. После этого необходимо переместиться в ветку, в которую будет происходить слияние. после этого в терминале с папкой-репозиторием необходимо написать *git merge <название ветки>*. Процесс слияния далеко не всегда проходит гладко. Если в двух ветках, которые вы собираетесь слить, вы внесли разные изменения в один и тот же файл, Git не сможет просто взять и объединить их. В таком случае необходимо решит конфликт вручную, после чего ***ОБЯЗАТЕЛЬНО*** сохранить изменения.

## Удаление веток

Для удаления ветки используется комманда *git branch -d*. Для этого в терминале с папкой-репозиторием необходимо написать *git branch -d <название ветки>*. 

### создание веток
Для создания новой ветки используется команда git branch. Для этого в терминале с папкой-репозиторием необходимо написать git branch <название ветки>. Название ветки должно быть уникально.

### Просмотр списка веток
Для просмотра списка веток используется команда git branch. Для этого в терминале с папкой-репозиторием необходимо написать git branch и вы увидите список всех существующих веток. Зеленым цветом символом звездочка

### Перемещение между ветками
Для перемещения между ветками команда

