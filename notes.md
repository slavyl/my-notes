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
 13. git remote add origin https://github.com/slavyl/my-first-project.git - remote делает один раз и далее просто после коммита идет git push


КАК ЗАПИСЫВАТЬ КОНСПЕКТЫ
1. Создал на гитхабе репозиторий my-notes
2. echo "# Конспект по Git" > git-notes.md
3. ## Создал/изменил файл git-notes.md
4. ## Проверил изменения git status
5. ## Добавил git add .
6. Коммит git commit -m "add git notes"
7. ## Пуш 🚀 git push