### Задача №3 - Слияние изменений

#### Ссылка на задание: [перейти](https://github.com/netology-ds-team/git-homeworks/tree/main/2_introduction)

#### Ссылки на созданные репозитории:
* [git-homeworks-neuro-merge](https://github.com/SYalisheva/git-homeworks-neuro-merge)

### Выполнение задания:

1. Выполнить команду для клонирования репозитория по заданной ссылке:
   
`git clone https://github.com/netology-code/git-homeworks-neuro-merge`

2. Выполнить команду для перехода в каталог локального репозитория:

`cd git-homeworks-neuro-merge`

3. Выполнить команду для создания локальной ветки на основе удаленной и последующего переключения на нее:

`git checkout -b feature/earlyorder origin/feature/earlyorder`

На основе удаленной ветки `origin/feature/earlyorder` была создана локальная ветка `feature/earlyorder`

4. Выполнить команду для перехода в локальную ветку main:

`git checkout main`

5. Выполнить команду для просмотра списка локальных веток:

`git branch`

Отображаются две ветки: `feature/earlyorder` и `main` (текущая)

6. Выполнить команду для слияния двух локальных веток:

`git merge feature/earlyorder`

Отображается конфликт: `CONFLICT (content): Merge conflict in index.html`

7. Разрешить конфликт, отредактировав файл. Исправить синтаксическую ошибку для незакрытого тэга div.

`git merge feature/earlyorder`

8. Выполнить команду:

`git add .`

9. Выполнить команду:

`git commit -m "Fix conflict"`

10. Выполнить команду для отвязки локального репозитория от исходного удаленного репозитория:

`git remote remove origin`

11. Создать пустой репозиторий через интерфейс GitHub.

12. Выполнить команду для привязки локального репозитория к созданному репозиторию:

`git remote add origin https://github.com/SYalisheva/git-homeworks-neuro-merge.git`

13. Выполнить команду для отправки изменений из локального в удаленный репозиторий:

`git push -u origin main`








