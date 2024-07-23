# git-config

  git config --global user.name "Kate"
  git config --global user.email "catevi@mail.ru"

  git config --list # посмотреть  настройки, чтобы выйти нужно нажать "Q"

  git config --global core.autocrlf true
  git config --global core.quotepath off
  git config --global core.safecrlf warn
  git config --global init.defaultBranch main

  git init # инициализация репозитория
  git add . # добавить все файлы в track
  git commit -m 'описание' #сделать коммит

  git status -
  git diff -
  git diff --color-words