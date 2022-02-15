TXT
 1. Создать внешний репозиторий c названием TXT:
     + зайти на GitHub и в разделе репозиторий создала новый с названием TXT
 2. Клонировать репозиторий TXT на локальный компьютер:
     + В GitHub нажала кнопку Code в репозиторие и скопировала ссылку. Далее на локальном компьютере создала папку repozitoryiTXT нажала кнопку GitBash here. git clone https://github.com/DaryaShramko/TXT.git  / ls -la чтобы убедиться в наличии копии в директории
 3. Внутри локального TXT создать файл “new.txt”:
    + cd TXT ;  cat > new.txt  1   ctrl + c 
 4. Добавить файл под гит:
    + git status ;  git add new.txt ; git status 
 5. Закоммитить файл:
    + git commit -m "I know how do it" 
 6. Отправить файл на внешний GitHub репозиторий:
    + git push 
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT:
     + cat > new.txt
     ````
      My name is Darya Shramko, I am 25 yers old. I have been begining to study on Vadim's Kzendzov course since January 2022. I always develope myself and I like do it, that's why I enjoy on course every lesson. I want to tell a bit about myself. I love the animals, so I have a few at home. I have a dog which call Roki, the two rats and fish that called Eduard. I dream of a remotely job. Afrer course will finish, I wish I earned 500 dollars for the start. 
       Ctrl + c.
       ````  
 8. Отправить изменения на внешний репозиторий:
     + git status;  git add new.txt; git status; git commit -m "change1" git push
 9. Создать файл preferences.txt:
      + cat > preferences.txt
    
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT:
   ````
      I absolutely love every season of the year, so I glad that live in Belarus. I feel sorry for people who live in Dubai ) I  like all kind of music.  I listen to pop-music, deep-house, electronic, rock, death-core, hard-core, rap-core.  
      Usually I watch all kind of movie, but I can't stand horror movie. Once I went into cinema there horror movie was shown. In the beginning of movie suddenly something disgusting appeared on screen. I started to cry and got away to home. Despite my preferences of movie, sometime I like reading horror book. 
      I dream of visit Czech, Spain, Georgia. I think, if I will have a journey to Georgia I will gain weight, due to there a lot of tasty food. I lose my self-control when I see something delicious.   

     Ctrl + c

  ````
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT:
     + cat > sklls.txt >
     ````
     On Vadim's Ksendzov course I will study a lot of new information, e.g. about Jmeter GitBash script, terminal line, Postman, Fidler, Charlie, SQL, Xcode, VPN, Dev Tools Google Chrome and Firefox, peculiarities of Android and iOS, simple bush cript, automation of routibe tasks on the server, Python and access to remote servers.   
     Ctrl + c
     ````
 12. Сделать коммит в одну строку:
     + git status ; git add . && git status && git commit -m "there is some information about myself"
 13. Отправить сразу 2 файла на внешний репозиторий:
     + git push
 14. На веб интерфейсе создать файл bug_report.txt:
     + GitHub > Repositories > add > bug_report.txt
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
     + Commit changes
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT:
     + GitHub > repozitory> нажать на bug_report.txt > edit file 
````
Summary: 	
Descriprion:		
PHP error appears in window after input SQL request in lield of login	"If enter SQL request in lield of login and press [Поехали] button PHP error appears in 
Actual result: Warning: mysqli_num_rows() expects parameter 1 to be mysqli_result, boolean given in C:\OpenServer\domains\megatask\index.php on line 15
Expected result:  Window with text Error appears
Requirement ID:
Reproduced on: Chrome
Reproducibility: always
Workaround: no
Steps to reproduce:
1. Open page via URL http://megatask/ 
2. Enter  DB request (SELECT * FROM users WHERE u_ul LIKE ‘a%’) in field ""Логин""
3. Enter  correct password (b) in field ""Пароль""
4. Press [Поехали] button"	
Severity: minor
Priority: -
```` 
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе:
     + commit changes
 18. Синхронизировать внешний и локальный репозиторий TXT:
     + в терминале ввести git pull

