### Задача №1 - Импорт существующего проекта

#### Ссылка на задание: [перейти](https://github.com/netology-ds-team/git-homeworks/tree/main/2_introduction)

#### Ссылки на созданные репозитории:
* [.2.-Site-For-Import](https://github.com/SYalisheva/1.2.-Site-For-Import)
* [.2.-Site-For-Import_2](https://github.com/SYalisheva/1.2.-Site-For-Import_2)

### Выполнение задания:

1. Создать пустой репозиторий через интерфейс GitHub
2. Сохранить содержимое архива в локальный каталог
3. Создать файл `.gitignore`
4. Добавить в файл следующие строки:
```
/tmp
*.*_old
*.*_backup
Thumbs.db
*.DS_Store
```
 5. Выполнить команду:

 `git init`

6. Выполнить команду:

`git status`

Убедиться, что нужные файлы проигнорированы

7. Выполнить команду:

`git add .`

8. Выполнить команду:

`git commit -m "first commit"`

9. Выполнить команду:

`git remote add origin https://github.com/SYalisheva/1.2.-Site-For-Import.git`

В результате этой команды создается псевдоним origin для первого репозитория.

10. Выполнить команду:

`git push -u origin master`

В результате этой команды залиты на удаленный репозиторий все файлы из исходного архива - за исключением тех, которые были отфильтрованы по заданной маске в .gitignore

11. Создать второй пустой репозиторий через интерфейс GitHub

12. Выполнить команду:

`git remote rename origin old_origin`

В результате этой команды псевдоним для первого репозитория переименован в old_origin

13. Выполнить команду:

`git remote add origin https://github.com/SYalisheva/1.2.-Site-For-Import_2.git`

В результате этой команды создается псевдоним origin для второго репозитория

14. Выполнить команду:

`git push -u origin master`

В результате этой команды залиты на удаленный второй репозиторий все файлы из локального репозитория
