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

<<<<<<< HEAD
Показать все коммиты
$ git log
 
Показать все коммиты в сокращенном виде
$ git log --oneline

Узнать статус файлов в репо
$ dit status

=======
Изменить последний коммит
$ git commit --amend --no-edit
$ git commit --amend -m "Новое сообщение"

Откатить изменения (коммит)
$ git restore --staged <file>

Вызов git restore --staged example.txt перевёл example.txt из staged обратно в untracked.

$ git restore --staged .   сбросит всю текущую папку (.).

«Откатить» коммит — $ git reset --hard <commit hash>

«Откатить» изменения, которые не попали ни в staging, ни в коммит, — git restore <file>
>>>>>>> 788413dba5aa3a0d06d74b4eae74c0337c91323f

Статусы файла
stage, tracked, untracked, modified

$ git diff сравнит последнюю закоммиченную версию файла с той, что находится в состоянии modified.

$ git diff --staged покажет изменения в staged-файлах относительно последних закоммиченных версий.

Строка @@ -1,2 +1,2 @@ сообщает, какие строки файла попали в сравнение.  Если бы было, например, написано +15,7, это значило бы, что в сравнении участвуют 
7 строк, начиная с 15-й.

## Дописываем строку в файл

echo  выводит в консоль то, что ей передали в качестве параметра.

$ echo "Вторая строка файла" >> file.txt   -  >> добавить строки
$ echo "Новая строка" > file.txt     -     > перед добавлением стереть содержимое файла

Finish of the scripting
