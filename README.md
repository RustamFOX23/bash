# bash 1

### Задание Bash

Открыть домашнюю директорию
/c/Users/Azerty/Desktop/дз тесты/bash_training/bash
Определить имя папки, в которой вы находитесь
$ `pwd`
/c/Users/Azerty/Desktop/дз тесты/bash_training/bash

Создать внутри этой папки каталог  с именем test1
$ `mkdir test1`

Перейти в папку test1

$ `cd test1`

Создать файл 1,2 и 3 внутри каталога test1
 
$ `touch {1,2,3}.txt`

Проверить содержимое каталога test1

$ `ls`
1.txt  2.txt  3.txt

Перейти в домашнюю директорию

$ `cd ..`

Создать папку test2 внутри домашней директории

$ `mkdir test2`

Удалить папку test2

$ `rmdir test2`

Удалить файл 2 из папки test1

$ `rm 2.txt ./test1`

Создать папку в домашней директории test3 и добавить в нее два файла

$ `mkdir test3`

$ `cd test3`

$ `touch {3,4}.txt`

Удалить папку test3

$ `rm -rf test3`

Создать папку test4 в домашней директории


$ `mkdir test4`

Переместить файлы 1 и 3 из папки test1 в папку test4

$ `mv test1/{1,3}.txt test4/`

Добавить в файл 1 три строки со словами line

$ `cd test4`

$ `echo "line line line"> 1.txt`

Посмотреть содержимое файла 1

$ `cat 1.txt`
line line line

Добавьте в файл 3 три строки со словами line

$ `echo "line line line"> 3.txt`

Просмотрите содержимое двух файлов (1 и 3) сразу

$ `cat 1.txt 3.txt`
line line line

Используя один из редакторов замените все строки в файле 1

$ `nano 1.txt`
