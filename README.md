1. Создать репозиторий;
2. В папке куда хочешь создать репазиторий  в консоль вводишь git init
3. Создал файл touch README.md
4. git add README.md
5. git commit -m "First commit"
6. git push -u origin main

-------------------------------

* Предварительно создать SSH ключ для репозитория

 - ssh-keygen -t rsa -b 4096 -C "Yedige7@gmail.com"
 - в Репазитории копируем открытую часть 
 - Добавить ключи в агент
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
 - ssh -T git@github.com
 - Проверяем убедиться, что репозитории связаны  git remote -v
