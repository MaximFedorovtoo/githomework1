maxim@maxim-RedmiBook-14-II:~/Рабочий стол/githomework$ git init
подсказка: Using 'master' as the name for the initial branch. This default branch name

подсказка: is subject to change. To configure the initial branch name to use in all

подсказка: of your new repositories, which will suppress this warning, call:

подсказка: 

подсказка:      git config --global init.defaultBranch <name>

подсказка: 

подсказка: Names commonly chosen instead of 'master' are 'main', 

'trunk' and



подсказка: 'development'. The just-created branch can be renamed via this command:
подсказка: 
подсказка:      git branch -m <name>
Инициализирован пустой репозиторий Git в /home/maxim/Рабочий стол/githomework/.git/
maxim@maxim-RedmiBook-14-II:~/Рабочий стол/githomework$ git add .
maxim@maxim-RedmiBook-14-II:~/Рабочий стол/githomework$ git status 
Текущая ветка: master

Еще нет коммитов

Изменения, которые будут включены в коммит:
  (используйте «git rm --cached <файл>...», чтобы убрать из индекса)
        новый файл:    program_1/Program.cs
        новый файл:    program_1/program_1.csproj
        новый файл:    program_2/Program.cs
        новый файл:    program_2/program_2.csproj


maxim@maxim-RedmiBook-14-II:~/Рабочий стол/githomework$ git remote add origin https://github.com/MaximFedorovtoo/githomework1.git
maxim@maxim-RedmiBook-14-II:~/Рабочий стол/githomework$ git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Распаковка объектов: 100% (3/3), 602 байта | 602.00 КиБ/с, готово.
Из https://github.com/MaximFedorovtoo/githomework1
 * [новая ветка]     main       -> origin/main
У текущей ветки нет информации об отслеживании.
Пожалуйста, укажите с какой веткой вы хотите слить изменения.
Для дополнительной информации, смотрите git-pull(1).

    git pull <внешний-репозиторий> <ветка>

Если вы хотите указать информацию о отслеживаемой ветке, выполните:

    git branch --set-upstream-to=origin/<ветка> master

maxim@maxim-RedmiBook-14-II:~/Рабочий стол/githomework$ git checkout main
A       program_1/Program.cs
A       program_1/program_1.csproj
A       program_2/Program.cs
A       program_2/program_2.csproj
Ветка «main» отслеживает внешнюю ветку «main» из «origin».
Переключились на новую ветку «main»
Book-14-II:~/Рабочий стол/githomework$ git commit -am 'All done'
[main 0a436cf] All done
 4 files changed, 95 insertions(+)
 create mode 100644 program_1/Program.cs
 create mode 100644 program_1/program_1.csproj
 create mode 100644 program_2/Program.cs
 create mode 100644 program_2/program_2.csproj
maxim@maxim-RedmiBook-14-II:~/Рабочий стол/githomework$ git push -u origin main
Перечисление объектов: 8, готово.
Подсчет объектов: 100% (8/8), готово.
При сжатии изменений используется до 8 потоков
Сжатие объектов: 100% (7/7), готово.
Запись объектов: 100% (7/7), 1.70 КиБ | 872.00 КиБ/с, готово.
Всего 7 (изменений 0), повторно использовано 0 (изменений 0), повторно использовано пакетов 0
To https://github.com/MaximFedorovtoo/githomework1.git

   9b95ee4..0a436cf  main -> main

Ветка «main» отслеживает внешнюю ветку «main» из «origin».
maxim@maxim-RedmiBook-14-II:~/Рабочий стол/githomework$ 
