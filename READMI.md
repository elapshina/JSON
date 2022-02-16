# JSON
 #### Создать внешний репозиторий c названием JSON
 - зайти на https://github.com
 - войти в свой аккаунт
 - нажать кнопку `New repository`
 - на открывшейся странице ввести имя репозитория (Repository name)
 - нажать кнопку `Create repository`

 ####  Клонировать репозиторий JSON на локальный компьютер
 - нажать кнопку `Code`
 - скопировать ссылку на репозиторий
 - в терминале зайти в папку в которой будет локальный репозиторий
 - `git clone https://github.com/elapshina/JSON.git`
 
####  Внутри локального JSON создать файл “new.json”
-  `cd JSON`
-  `touch new.json`

 ####  Добавить файл под гит
 - `git add new.json`
 
 ####  Закоммитить файл
 - `git commit -m "add new.json`

####  Отправить файл на внешний GitHub репозиторий
- `git push`

 ####  Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON
 - nano `new.json`

 ```
 {
        "full_name":"Ekaterina Lapshina",
        "age":32,
        "number of pets":0,
        "future desired salary":1000$
 }
 ```

####  Отправить изменения на внешний репозиторий
- `git add new.json`
- `git commit -m "modified new.json"`
- `git push`

####  Создать файл preferences.json
-  `nano preferences.json`


####  В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON
```
{
	"favorite_movie":"World War Z",
	"favorite_series":"Squid Game",
	"favorite_food":"Pasta",
	"favorite_season":"Summer",
	"country_you_would_like_to_visit":"Portugal"
}
```

#### Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
- `nano sklls.json`
```
{
"skills":[
	"Basic theory",
	"Client-server architecture",
	"HTTP Methods of requests to the server",
	"HTTP server response codes",
	"Structures of HTTP requests and responses",
	"What is JSON, XML. Their structure",
	"API testing via Postman",
	"Removing and reading logs from an external 
    server",   
	"Sniffing http web traffic via Charles and 
    Fiddler",
	"Dev Tools of web browsers",
	"VPN.ow it works, why you need it, how to use
    it, tool options",
	"Mobile testing",
	"Feature of iOS, Android, guidelines",
	"Building iOS applications on XCode",
	"Building Android applications on Android
    Studio",
	"ADB (android device management)",
	"Setting up proxy and vpn on iOS and Android",
	"Interception of mobile traffic via Charles and
    Fiddler on iOS and Android",
	"Command line terminal Linux",
	"Basics of bash scripting, automation of
    routine tasks on the server",
	"Access to remote servers",
	"SQL basics",
	"Postgres database",
	"Non-relational database Redis",
	"Load testing in Jmeter",
	"Scrum development methodology",
	"Python. Learning the basics. Creating a
    client-server application"
	]
}
```

 #### Отправить сразу 2 файла на внешний репозиторий
 
 16. На веб интерфейсе создать файл bug_report.json.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 20. Синхронизировать внешний и локальный репозиторий JSON


XML
 21. Создать внешний репозиторий c названием XML.
 22. Клонировать репозиторий XML на локальный компьютер.
 23. Внутри локального XML создать файл “new.xml”.
 24. Добавить файл под гит.
 25. Закоммитить файл.
 26. Отправить файл на внешний GitHub репозиторий.
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
 28. Отправить изменения на внешний репозиторий.
 29. Создать файл preferences.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 32. Сделать коммит в одну строку.
 33. Отправить сразу 2 файла на внешний репозиторий.
 34. На веб интерфейсе создать файл bug_report.xml.
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 38. Синхронизировать внешний и локальный репозиторий XML
