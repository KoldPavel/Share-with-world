# Share with world
## Tricks
*learn git, it is usefull tool*

change direcroy
cd  C:\Users\koldunov\Desktop\Koldunov\Revit\GitRepo\Share-with-world

create clone
$ git clone https://github.com/KoldPavel/Share-with-world.git

Связать локальный и удаленный репозитории
$ git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git

Убедиться, что репозитории связаны, — git remote -v
$ git remote -v

Закинуть на ГитХаб из лок. репо
$ git push -u origin main # -u для первого раза 

Изменить последний коммит
$ git commit --amend --no-edit
$ git commit --amend -m "Новое сообщение"

Откатить изменения (коммит)
$ git restore --staged <file>

Вызов git restore --staged example.txt перевёл example.txt из staged обратно в untracked.

$ git restore --staged .   сбросит всю текущую папку (.).

«Откатить» коммит — $ git reset --hard <commit hash>

«Откатить» изменения, которые не попали ни в staging, ни в коммит, — git restore <file>



Finish of the scripting
