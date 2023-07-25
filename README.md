JSON

4. Создать внешний репозиторий c названием JSON. 
```
GitHub - Repositories - NEW - JSON - like [Add a README file] - Create repository
```
5. Клонировать репозиторий JSON на локальный компьютер.
```
git clone https://github.com/Ta2703/JSON.git
```
 6. Внутри локального JSON создать файл “new.json”.
```
 cd JSON / touch new.json
```
 7. Добавить файл под гит.
```
 git add new.json
```
 8. Закоммитить файл.
```
 git commit -m "created the new.json"
```
 9. Отправить файл на внешний GitHub репозиторий.
```
git push origin main
```
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  -
 <code>
 vim new.json 
  [i] - режим редактирования 
{
"name":"Tamara",
"age": 28,
"animal": 1,
"salary": "500$"
}
</code>

```
[esc] :wq
```
выходим из редактора и сохраняем изменения 

 11. Отправить изменения на внешний репозиторий.
```
git commit -a -m "edited the new.json" / git push origin main
```
12. Создать файл preferences.json
```
touch preferences.json
```
13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```
vim preferences.json
[i]
```
<code>
{
"favorite film": "Titanic",
"favorite series": "Black mirror",
"favorite food": "Bananas",
"favorite time of the year": "spring",
"a side that would like to visit": "Spain"
}
</code>

```
[esc] :wq
```

 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

```
 touch skills.json 
vim skills.json
[i]
```
<code>
    {
        "Hard skills: ": "Basic theory (What is testing, bug reports, documentation, types, methods, testing areas, etc.) SDLC, STLC."
    },
    {
        "Hard skills: ": "What is a client-server architecture."
    },
    {
        "Hard skills: ": "HTTP Methods of requests to the server."
    },
    {
        "Hard skills: ": "HTTP server response codes."
    },
    {
        "Hard skills: ": "Structures of HTTP requests and responses."
    },
    {
        "Hard skills: ": "What is JSON, XML. Their structure."
    },
    {
        "Hard skills: ": "API testing via Postman (JS, API autotests)."
    },
    {
        "Hard skills: ": "Removing and reading logs from an external server."
    },
    {
        "Hard skills: ": "Sniffing http web traffic via Charles and Fiddler."
    },
    {
        "Hard skills: ": "Dev Tools of web browsers (Google Chrome, FireFox)."
    },
    {
        "Hard skills: ": "VPN. (How it works, why you need it, how to use it, tool options)"
    },
    {
        "Hard skills: ": "Mobile testing."
    },
    {
        "Hard skills: ": "Feature iOS, Android, guidelines."
    },
    {
        "Hard skills: ": "Building iOS applications on XCode. (Those who do not have a Mac computer, just look)"
    },
    {
        "Hard skills: ": "Building Android applications on Android Studio."
    },
    {
        "Hard skills: ": "ADB (android device management)."
    },
    {
        "Hard skills: ": "Setting up proxy and vpn on iOS and Android."
    },
    {
        "Hard skills: ": "Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android."
    },
    {
        "Hard skills: ": "Command line (terminal) Linux (copying, creating, viewing, moving files on servers without a graphical interface)"
    },
    {
        "Hard skills: ": "Basics of bash scripting, automation of routine tasks on the server."
    },
    {
        "Hard skills: ": "Access to remote servers."
    },
    {
        "Hard skills: ": "SQL basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)."
    },
    {
        "Hard skills: ": "Postgres database (installation, configuration and use)."
    },
    {
        "Hard skills: ": "Non-relational database Redis (installation, configuration and use)."
    },
    {
        "Hard skills: ": "Load testing in Jmeter."
    },
    {
        "Hard skills: ": "Scrum development methodology."
    },
    {
        "Hard skills: ": "Test Design Techniques (Equivalence Classes, Boundary Values, Combinatorial Techniques (Pairwise, Orthogonal, Basic Choice, Every Choice), States and Transitions)"
    },
    {
        "Hard skills: ": "Python. (Learning the basics. Creating a client-server application)"
    }
</code>

```
[esc] :wq
```

 15. Отправить сразу 2 файла на внешний репозиторий.
```
git status - смотрим статус наших файлов 
git add .  - берем в работу все наши новые файлы 
git commit -m "created the preferences.json and skills.json"
git push origin main
```

 16. На веб интерфейсе создать файл bug_report.json.
```
 add file / create new file
```

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
«bug_report.json» / Commit changes
```

 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
```
«bug_report.json» / Edit this file
```
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
20. Синхронизировать внешний и локальный репозиторий JSON
```
git pull origin main
```
