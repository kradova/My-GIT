# My-GIT
Study GIT


git clone <repository url> . //скопировать удаленный репозиторий 
git status 
git log //просмотр истории комитов
gitk //открыть графический интерфейс git
git remote -v //просмотреть привязанные репозитории !удаленные (-v подробно)
git add . // добавить изменения в stage (. - все измененные файлы ) 
git commit -m "comments" // сохранить текущее состояние проекта, находящееся в stage
git push //отправить commits на удаленный репозиторий
git pull //получает из репозитория обновления
git checkout <file name> //сбросить несохраненные изменения до состояния предыдущего комита



…or create a new repository on the command line
echo "# Study-Java" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kradova/Study-Java.git
git push -u origin main


…or push an existing repository from the command line
git remote add origin https://github.com/kradova/Study-Java.git
git branch -M main
git push -u origin main



