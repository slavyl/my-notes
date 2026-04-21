Скачать утилиту Git
 2. git config --global user.email "twistem33@ya.ru"
 3. git config --global user.name "slavyl"
 4. Создать новый репозиторий (не работать в домашней папке) - mkdir ....
 5. Перейти в этот репозиторий (cd ...)
 6. Инициализировать репозиторий (git init)
 7. $ echo "<p>Hello Git!<p>" > index.html - создать файл index.html и написать туда <p>Hello Git!<p>
 8. Прооверить наличие файла в репозитории (ls)
 9.  cat index.html
 10.  git add index.html
 11. git commit -m "first commit"
 12. Создать репозитории с любым именем на GitHub (не ставить галочку при добавлении папки readme)
 13. git remote add origin https://github.com/slavyl/my-first-project.git - remote делаем один раз на проект (remote = “куда отправлять проект”) и далее просто после коммита идет git push
 14. git push -u origin *main* (название ветки имеет значение) - в первый раз полностью прописать -u origin *ветка*, дальше просто *git push* (git push -u origin master — тоже НЕ каждый раз -u (upstream) нужен только при первом push)
 Если ошибка после git push error: failed to push some refs to 'https://github.com/slavyl/my-notes.git':
 1. проверить на какой ветке находишься git.branch
 2. git push -u origin *название ветки*


КАК ЗАПИСЫВАТЬ КОНСПЕКТЫ
1. Создал на гитхабе репозиторий my-notes 'https://github.com/slavyl/my-notes.git'
2. создать в папке новый файл .md
3. cat (файл)
4. git add (файл)
5. git commit -m "комментарий"
6. git push

ПРИ ИЗМЕНЕНИИ ФАЙЛА
1. CTRL + S
2. git status
3. git add (название файла) или git add . (попробовать с .)
4. git commit -m "комментарий"
5. git push
edit → save → add → commit → push

Когда НУЖЕН снова remote add
Только если:
1. ты создал новую папку проекта
2. сделал git init заново
3. или новый репозиторий