# Мой путь изучения

## 09.10.2025

1. Создала локальный и удалённый репозитории
2. Соединили их между собой

## 10.10.2025

1. Создала новую ветку readme-edits, где и прописываю данный шаг. 
2. Успешно объединила ветки
3. Подредактировала профиль: добавила аватарку, описание и readme.md в профиле

## 12.10.2025

1. Прояснила отличия между скачиванием, клонированием и форком репозитория. Установила octocat/Spoon-Knife репозиторий.
2. Добавила полезные ссылки
3. Перенесла изменнения с удалённого репозитория на локальный
4. Испробовала команду `git blame README.md` в текущей папке: <img width="896" height="185" alt="image" src="https://github.com/user-attachments/assets/37641a0f-d4ed-4e49-872d-8a67aa69f652" />
5. Определила новые разделы: Команды, проблемы, темы для изучения
6. Добавила gitignore c файлами и папками на локальном репо

## 13.10.2025
1. Перешла на курс степика "Git и GitHub" и добавила ссылки на официальные сайты Revision Control System и SubVersion, прошла первую тему VCS
2. Разобрала базовые команды типа git config, значение префикса --global

## 14.10.25
1. Разобрала работу коммитов и индексов



# Используемые команды 

- `git blame <файл>` Предоставляет подробную историю файла с указанием автора и коммита, в котором была изменена последняя строка файла
- `git pull origin main` Перенос изменений с удалённого репозитория на локальный
- `git push -u origin main` Перенос изменений с локального репозитория на удалённый
- `npm <start>` команда, которая запускает скрипт «start» в файле package.json проекта на Node.js.
- `git config --global user.name` Показывает имя пользователя для подписания коммитов
- `git config --global user.name "<имя>"` Устанавливает новое имя для пользователя для одного репозитория
- `git config --global user.email "<имя>"` Устанавливает новую почту  
- `git config --list` Выводит список всех установленных настроек конфигурации
- `git config <название настройки>` Выводит определенную установленную настройку конфигурации
- `git config --global color.ui <true/false/auto>` Устанавливает цветной вывод информации (true)
- `git remote add origin <ссылка на репо>` Добавляет удалённый репозиторий (origin) в локальный репозиторий
- `git clone <URL репозитория> [<название локальной папки>]` Создаёт локальную копию удалённого репозитория
- `git fetch <адрес удалённого репозитория>` Загружает актуальные данные из удалённого репозитория в локальное хранилище без изменения файлов в рабочей директории
- `git remote -v` Выводит список удалённых репозиториев, связанных с локальным репозиторием, и соответствующие им URL-адреса.
- `git remote rm <имя удалённого репозитория>` Удаляет ссылку на удалённый репозиторий.
- `touch .gitignore` Создать файл gitignore для своей папки
- `git rm --cached FILENAME` Снять файл с отслеживания
- `git init` Создать Git-репозиторий в текущей папке
- `` 
- `` 
- `` 


# Проблемы

- Не получается воспользоваться Copilot в Visual Studio Code. Ошибка: "An error occured while signing up for the GitHub Copiliot Free plan. Would you luke to try again? (403)"


# Темы для изучения

- Токены
- Copilot
- Устанавливать и настраивать Git на своём компьютере 
- ~~Создавать локальные репозитории и инициализировать проекты~~
- ~~Делать осмысленные коммиты с понятными сообщениями~~
- Работать с индексом (staging area)
- Откатывать изменения и управлять историей
- Управлять файлами: удалять, переименовывать, перемещать
- ~~Просматривать и анализировать историю коммитов~~
- Исправлять историю (если нужно)
- ~~Настраивать .gitignore~~
- ~~Работать с удалёнными репозиториями на GitHub~~
- ~~Клонировать репозитории~~
- Настраивать SSH-ключи для безопасного подключения 
- Форкать чужие репозитории
- Использовать GitHub Copilot (по желанию)
- ~~Сравнивать версии файлов~~
- ~~Синхронизировать локальные и удалённые репозитории~~


# Полезные ссылки

- https://docs.github.com/ru/get-started GitHub: Начало работы
- https://learngitbranching.js.org/?locale=ru_RU Интерактивное визуальное обучение
- https://stepik.org/course/252829/promo Структурированный курс с заданиями и теорией.
- https://monsterlessons.com/project/series/git-dlya-nachinayushih Видеоуроки
- https://docs.github.com/en/get-started/getting-started-with-git Основы Git
- https://docs.github.com/en/get-started/using-git Использование Git
- https://git-scm.com/ Официальный сайт проекта Git
- http://git-scm.com/book Книга ProGit
- https://git-scm.com/book/ru/v2 Книга ProGit второго издания на русском
- http://git-scm.com/book Список команд Git
- https://github.com/cyberspacedk/Git-commands Шпаргалка комманд Git
- http://learngitbranching.js.org/ Изучение и отработка концепций Git
- https://www.pluralsight.com/courses/code-school-git-real Интерактивный онлайн курс по Git
- https://services.github.com/#upcoming-events Онлайн тренинги с практическим подходом, основанным на проектах
- https://github.com/orgs/community/discussions/ Поддержка сообщества GitHub
- https://www.gnu.org/software/rcs/rcs.html Официальный сайт Revision Control System
- https://subversion.apache.org/ Официальный сайт Subversion
- https://git-scm.com/downloads/win Страница загрузки Git для Windows
- https://git-scm.com/downloads/mac Инструкции по установке Git для MacOS
- https://git-scm.com/downloads/linux Инструкции по установке Git для Unix/Linux
