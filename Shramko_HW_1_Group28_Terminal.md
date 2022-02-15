### GitBash, Terminal - first homework

#### Задание 
1. Посмотреть где я: 
   + pwd
2. Создать папку: 
   + mkdir lesson
3. Зайти в папку: 
   + cd lesson
4. Создать 3 папки:
   + mkdir qa course VadimKsendzov
5. Зайти в любоую папку:
   + cd qa
6. Создать 5 файлов (3 txt, 2 json) 
   + touch one.txt two.txt three.txt; touch one.json two.json
7. Создать 3 папки: 
   + mkdir project1 project2 project3
8. Вывести список содержимого папки:
   + ls -la
9.  Открыть любой txt файл:
    + vim one.txt
10.  написать туда что-нибудь, любой текст:
`
    + -i {"name":"Darya",
   "age": 25
    } 
`
11. сохранить и выйти:
    + esc :wq Darya.txt; 
12. Выйти из папки на уровень выше:
    + cd ..

13. переместить любые 2 файла, которые вы создали, в любую другую папку:
    + mv one.txt project1; mv one.json project1 
    + or two.txt two.json project1/
14. скопировать любые 2 файла, которые вы создали, в любую другую папку:
    + cp two.txt project2; cp two.json project2
15. Найти файл по имени:
    + find Darya.txt 
16. просмотреть содержимое в реальном времени (команда grep) изучите как она работает:
    + tail -f three.txt, grep в данном случае не подходит, испульзуем: tail -f three.txt
    + я изучила, что команду grep можно использовать с tail следующим образом: tail -f name.txt | grep (time:time) вывести информацию в терминал за определенный период времени; затем можно эту информацию сохранить в другой файл с помощью tail -f name.txt | grep - - line - buffered - (time:time) >> в какой файл сохранить 
17. вывести несколько первых строк из текстового файла:
    + head -n3 three.txt; 
18. вывести несколько последних строк из текстового файла:
    + tail -3 three.txt
19. просмотреть содержимое длинного файла (команда less) изучите как она работает:
    + less three.txt
    + then Q for exit
20. вывести дату и время:
    + date 


#### Задание *
1. Отправить http запрос на сервер http://162.55.220.72:5005/terminal-hw-request:
     1. curl ` "http://162.55.220.72:5005/terminal-hw-request" ` ; 
     2. curl ` "http://162.55.220.72:5005/get_method?name=(Darya)&age=(25)" `

2. Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13:
    1. создала новую папку, в которой есть папка p1
    2. Git Bash here
    3. touch myscript1
    4. vim myscript1
    5. i

````
#! /bin/bash

#comment

cd p1

mkdir q1 q2 q3

cd q1

touch 1.txt 2.txt 3.txt 1.json 2.json

mkdir w1 w2 w3

ls -la

mv 1.txt 2.txt w1/
````  
+ esc :wq

+ chmod +x ./myscript1
+ ./myscript


