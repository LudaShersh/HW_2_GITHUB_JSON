# JSON
#### 1. Создать внешний репозиторий c названием JSON:
 * https://github.com/LudaShersh
 * new
 * repositoru
* name:json
* add a readme file
* create repository. 
#### 2. Клонировать репозиторий JSON на локальный компьютер. 
* https://github.com/LudaShersh/JSON
*  code
* https
* copy
* open gitbash
* write: git clone https://github.com/LudaShersh/JSON.git
#### 3. Внутри локального JSON создать файл “new.json”. 
* cd json
* cat > new.json
#### 4. Добавить файл под гит.  
* git add new.json
#### 5. Закоммитить файл. 
* git commit -m "add 1 file json"
#### 6. Отправить файл на внешний GitHub репозиторий.
* git push
#### 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
* vim new.json
```json
{
        "full name":"Shershneva Ludmila Mikhailovna",
        "age":25,
        "number of pets":1,
        "future desired job":"QA"

}
```
### 8. Отправить изменения на внешний репозиторий. 
* git commit -am "change json file" 
* git push
#### 9. Создать файл preferences.json
* vim preferences.json
#### 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```json
{
        "favorite movie": "The Pursuit of Happyness",
        "favorite TV series":"Sherlock",
        "favorite food":"pasta",
        "favorite season":"summer",
        "country I would like to visite":"Georgia"

}
```
#### 11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
```json
{
        "1":{"Базовая теория":["Что такое тестирование", "багрепорты", "документация", "виды", "методы", "направления тестирования", "SDLC", "STLC"]},
        "2":"Что такое клиент-серверная архитектура",
        "3":"HTTP Методы запросов на сервер",
        "4":"Коды ответов HTTP сервера",
        "5":"Структуры HTTP запросов и ответов",
        "6":["Что такое JSON","ее структура", "что такое XML","ее структура"],
        "7":["Тестирование API через Postman", "JS", "автотесты API"],
        "8":" Снятие и чтение логов c внешнего сервера",
        "9":"Снифинг http web трафика через Charles и Fiddler",
        "10":{"Dev Tools веб браузеров": ["Google Chrome", "FireFox"]},
        "11":{"VPN":["Как работает", "зачем нужен", "как использовать", "варианты инструментов"]},
        "12":"Мобильное тестирование",
        "13":"Особенность iOS, Android, гайдлайны",
        "14":"Сборка iOS приложений на XCode",
        "15":"Сборка Android приложений на Android Studio",
        "16":"ADB (управление андройд девайсами)",
        "17":"Настройка прокси и vpn на iOS и Android",
        "18":"Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android",
        "19":{"Командная строка (terminal) Linux":["копирование", "создание", "просмотр", "перемещение файлов на серверах без графического интерфейса"]},
        "20":"Основы bash скриптинг, автоматизация рутинных задач на сервере",
        "21":"Доступ к удалённым серверам",
        "22":{"Основы SQL":["Create", "Delete", "Drop", "Insert Into", "Select", "From", "Where", "Join"]},
        "23":{"База данных Postgres":["установка", "настройка", "использование"]},
        "24":{"Нереляционная база данных Redis":["установка", "настройка", "использование"]},
        "25":"Нагрузочное тестирование в Jmeter",
        "26":"Методология разработки Scrum",
        "27":{"Python":["Изучение основ", "cоздание клиент серверного приложения"]}

}
```
#### 12. Отправить сразу 2 файла на внешний репозиторий. 
* git add .  
* git commit -m "add preferences and skills files json" 
* git push
#### 13. На веб интерфейсе создать файл bug_report.json.
* add file
* create new file
#### 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
* commit change
#### 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
```json
{
  "1":"Summary",
  "2":"Description",
  "3":"Step to reproduce",
  "4":"Severity",
  "5":"Priority",
  "6":"Envirenmen"
}
```
#### 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
* commit change
#### 17. Синхронизировать внешний и локальный репозиторий JSON
* git pull

https://github.com/LudaShersh/JSON