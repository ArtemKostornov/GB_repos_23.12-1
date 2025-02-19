Привет, GitHub и мир

# Инструкция для работы с Git #

* ## Таблица ##

<code> __COMAND__ |_DESCRIPTION_
:-------- | ---------:
__git help__ | _отображение возможных команд git_
__git init__  | _инициализация локального репозитория_
__git status__ | _информацию от гит о его текущем состоянии_   
__git add info.md__ |  _добавляет отслеживания файла info.md_  
__git add .__  | _добавляет отслеживания всех файлов в директории_
__git commit -m "комментарий"__ | _добавляет фиксацию состояния изменений_
__git log__ | _вывод на экран истории всех коммитов_
__git checkout__ | _переход от одного коммитак другому_
__git checkout master__ | _возврат к текущему состоянию_
__git diff__ | _разница между актуальным файлом и последним коммитом_
__git merge__ | _соединение веток версий в одну_
__git branch -d__ | _удаление ненужной ветки_
__git log --author="имя_автора"__ | _выводит комммиты который делал определённый автор_
__git reset --hard номер_коммита__ | _удаляет все коммиты до указанного_
__git log -n число__ | _Ограничивает число коммитов до указанного параметра_
__git clone url-адрес__ | _создаёт копию удалённого репозитория_
</code>

* ## Изображение ##
__Как работают ветки в git:__
![Наглядный пример работы веток](branch.png)

* ## Цитата ##
>___Команда для создание новой ветки, а также перехода на неё:___
>>_git branch <название_ветки>_
>>>_git checkout <название_ветки>_

* ## Ссылка ##
[__Больше информации о git__](https://habr.com/ru/post/541258/ "ССЫЛКА НА Хабр")
