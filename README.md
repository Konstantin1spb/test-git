1. git status
2. git add [files] . - все файлы -- добавляет файлы в stage
3. git commit -m "comment" -- запись
4. git log -- логи (git log --oneline - короткая версия)
5. git push [rep_link] [branch_name] -- отправка изменений на удаленный репозиторий (вместо rep_link можно написать origin (ссылка на репозиторий))
6. git branch -- информация о ветке
7. git reset [filename] -- убирает файл из stage
8. git diff [filename] -- отображает изменения в файле
9. git reset --hard -- убирает все изменения из файлов (до коммита) и очищает status