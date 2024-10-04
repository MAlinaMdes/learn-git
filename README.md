# git-config
git config --global user.name “имя”
git config --global user.email “почта”

git config --global core.safecrlf warn
git config --global core.quotepath off
git config --global init.defaultBranch main # Ветка по умолчанию

git init # инициализация репозитория
git add . #добавить все файлы в track
git commit -m "описание" #сделать коммит
git status
git diff
git diff --color-words