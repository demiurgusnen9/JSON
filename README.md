# JSON

### Создать внешний репозиторий c названием JSON.

`https://github.com/demiurgusnen9/JSON.git`

### Клонировать репозиторий JSON на локальный компьютер.
```
$ git clone https://github.com/demiurgusnen9/JSON.git
 
 Cloning into 'JSON'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
```
### Внутри локального JSON создать файл “new.json”.
```
$ cd JSON
$ touch new.json
```
### Добавить файл под гит.
`
$ git add new.json
`
### Закоммитить файл.
```
$ git commit -m "add new.json"
 
[main 023c0a5] add new.json
1 file changed, 0 insertions(+), 0 deletions(-)
create mode 100644 new.json
``` 
### Отправить файл на внешний GitHub репозиторий.
`
$ git push
`
### Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```
$ vim new.json
 {
        "ФИО": "Masalskaya Alena Viktorovna",
        "Возраст": 30,
        "Количество домашних животных": 1,
        "Будущая желаемая зарплата": "500$"
 }
 ``` 
### Отправить изменения на внешний репозиторий.
```
$ git commit -am "add info new.json"
 
warning: LF will be replaced by CRLF in new.json.
The file will have its original line endings in your working directory
[main 6078f2a] add info new.json
1 file changed, 6 insertions(+)
``` 
```$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 447 bytes | 447.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/demiurgusnen9/JSON.git
023c0a5..6078f2a  main -> main
```
### Создать файл preferences.json
`
$ touch preferences.json
`
### В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате JSON.
```
$ vim preferences.json
 {
        "Любимый фильм": "Трудности перевода",
        "Любимый сериал": "Клиника",
        "Любимая еда": "Кукурузные_палочки",
        "Любимое время года": "Зима",
        "Страна которую хотели бы посетить": "Исландия"
 }
```
### Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
```
$ vim skills.json
 {
        "1":"Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC",
	"2":"Что такое клиент-серверная архитектура",
	"3":"HTTP Методы запросов на сервер",
	"4":"Коды ответов HTTP сервера",
	"5":"Структуры HTTP запросов и ответов",
	"6":"Что такое JSON, XML. Их структура",
	"7":"Тестирование API через Postman (JS, автотесты API)",
	"8":"Снятие и чтение логов c внешнего сервера",
	"9":"Снифинг http web трафика через Charles и Fiddler",
	"10":"Dev Tools веб браузеров (Google Chrome, FireFox)",
	"11":"VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)",
	"12":"Мобильное тестирование",
	"13":"Особенность iOS, Android, гайдлайны",
	"14":"Сборка iOS приложений на XCode",
	"15":"Сборка Android приложений на Android Studio",
	"16":"ADB (управление андройд девайсами)",
	"17":"Настройка прокси и vpn на iOS и Android",
	"18":"Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android",
	"19":"Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
	"20":"Основы bash скриптинг, автоматизация рутинных задач на сервере",
	"21":"Доступ к удалённым серверам",
	"22":"Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
	"23":"База данных Postgres (установка, настройка и использование)",
	"24":"Нереляционная база данных Redis (установка, настройка и использование)",
	"25":"Нагрузочное тестирование в Jmeter",
	"26":"Методология разработки Scrum",
	"27":"Python. (Изучение основ. Создание клиент серверного приложения)"
 }
 ```
### Отправить сразу 2 файла на внешний репозиторий.
```
$ git add .
$ git commit -m "add preferences.json and skills.json with info"
 
 [main d7940c9] add preferences.json and skills.json with info
 2 files changed, 36 insertions(+)
 create mode 100644 preferences.json
 create mode 100644 skills.json
 
$ git push
 
 Enumerating objects: 5, done.
 Counting objects: 100% (5/5), done.
 Delta compression using up to 2 threads
 Compressing objects: 100% (4/4), done.
 Writing objects: 100% (4/4), 1.63 KiB | 1.63 MiB/s, done.
 Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
 To https://github.com/demiurgusnen9/JSON.git
 6078f2a..d7940c9  main -> main
```
### На веб интерфейсе создать файл bug_report.json.
`
done
`
### Сделать Commit changes (сохранить) изменения на веб интерфейсе.
`
done
`
### На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
```
{
"ID":"ID",
"Summary":"Короткое описание",
"Steps to Reproduce":"Шаги воспроизведения",
"Expected Result":"Ожидаемый результат",
"Actual Result":"Фактический результат",
"Severity":"Серьезность"
}
```
### Сделать Commit changes (сохранить) изменения на веб интерфейсе.
`
done
`
### Синхронизировать внешний и локальный репозиторий JSON
```
$ git pull

Updating d7940c9..f5dd38b
Fast-forward
bug_report.json | 8 ++++++++
1 file changed, 8 insertions(+)
create mode 100644 bug_report.json
```
