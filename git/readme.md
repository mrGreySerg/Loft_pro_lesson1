#git learning

###first steps
1. npm init -y (don't ask you to fill profile).
2. git init.
3. git commit -am "" - if we don't create new documents.
4. access in terminal by https(use login) and ssh(without login).
    1. ssh-keygen - generate keygen(without login).
    2. cat ~/.ssh/id_rsa.pub - look throw file id_rsa.pub.
    3. and add to git hub your keygen. (settings/ssh).
    4. If you want to change https to ssh in existing project
        git remote set-url origin email....
    5. Был косяк с идентификацией, на вопром ответ полностью "yes".
5. git clone email.... [folder].
6. git config --list - settings.  
7. git config --list --show-origin - settings with url.
8. in project >git config user-name "..." / user-email "..." - change email and name local for our exist project (global name and email difference). local settings are main.
9. Delete from add . (green) убираем отсеживание.
    1. git rm --cached index.html.
    2. git reset --hard (удаляет все из add и откатывает на состояние последнего commit) very hard.
    3. git reset HEAD index.html в консоли пишется.
10. git push -u origin master (-u ключ, показывающий куда по умолчанию push и в следующий раз не надо писать origin master).
11. git remote rm origin - deleted remote repository.
12. Octotree - plugin for github.