ВАЖНОЕ:
включаем ssh агента: eval "$(ssh-agent -s)"
вводим приавтный ключ: ssh-add ~/.ssh/название
ОБЩЕЕ:
для создания ssh ключа: ssh-keygen -t ed25519 -C "имя.фамилия@phystech.edu"
для первого входа вводим следующее:
git config --global user.name "Имя Фамилия"
git config --global user.email "имя.фамилия@phystech.edu"
git config --global core.editor nano 
для создания репозитория:
mkdir наззвание (создаем ппапку)
cd название (захоим в нее)
git init (создаем)
выйти из любой папки на ша назад: cd ..
полезные команды:
ls (показывает файлы)
git status (показывает стсатус репозитория)
git log (показывает лог репозитория)
Добавлнеи фала в репозиторий:
git add файл (--all) (добавляет файли или все) (показывает гиту как бы)
git commit -m 'что то, например поянения' (добавлет изменнения)
git commit (в nano если его ввели) (тоже самое)
