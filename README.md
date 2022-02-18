# TXT

1. Создать внешний репозиторий c названием TXT.
+ Открыть https://github.com/, залогиниться 
+ Зайти во вкладку `Repositories`
+ Нажеть `New`
+ Ввести название репозитория, сделать его общедоступным
+ Нажать `create repository`
2. Клонировать репозиторий TXT на локальный компьютер.
+ открыть GitBash в папке, где будет храниться репозиторий
+ в командную стороку ввести команду `git clone + ссылка на репозиторий, который хотим клонировать`
3. Внутри локального TXT создать файл “new.txt”.
+ `cd TXT` - перейти в локальный репозиторий
+ `cat > new.txt`
+ `ctrl + c` - выйти из редактирования
4. Добавить файл под гит.
+ `git add new.txt` - для добавления определенного файла
+ `git add .` - для добавления всех файлов
5. Закоммитить файл.
+ `git commit -m "new file"`
6. Отправить файл на внешний GitHub репозиторий.
+ `git push`
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
+ `cat > new.txt`
+ ввести текст
```
	Full name: Alona Kot
	age: 25
	Pets: 1
	Disired Salary: 600$
``` 
+ `ctrl + c` - выйти из редактирования
8. Отправить изменения на внешний репозиторий.
+ `git add new.txt` - добавить измененный файл под гит
+ `git commit -am "edit file"` - закомитить изменения
+ `git push` - отправить измененный файл на внешний реозиторий 
9. Создать файл preferences.txt
`cat > preferences.txt`
10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
+ввести текст
```
	Favorite movie: "Indiana Jones"
	Favorite serias: "Scrubs"
	Favorite food: Burgers
	Country you would like to visit: Switzerland
```
+ `ctrl + c` - выйти из редактирования
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
+ `cat > sklls.txt`
+ ввести текст
``` 
	* Basic theory
	* Client-server architecture
	* HTTP Server request methods
	* HTTP Server responses codes
	* Structures of requests and responses
	* JSON, XML. Their structure
	* API testing
	* Removing and reading logs
	* POSTMAN, FIDLER
	* VPN
	* Dev Tools for web browsers
	* Mobile testing
	* Feature iOS, Android, guidelines
	* Building iOS Apps with Xcode
	* Building Android Applications with Android Studio
	* Interception of mobile traffic (sniffing) via CHARLES
	* Proxy settings on iOS and Android
	* Terminal Linux Ubuntu. Copying, creating, viewing, moving files on servers without a graphical interface
	* Simple bash scripting, automation of routine tasks on the server
	* Access to remote servers
	* SQL fundamentals (Create, Delete, Drop, Insert Into, Select, From, Where, Join
	* GIT
	* JMETER
	* Scrum Development Methodology
	* Python. Creation of own client-server application
```
+ `ctrl + c` - выйти из редактирования
12. Сделать коммит в одну строку.
+ `git add . ; git commit -m "new files"`
13. Отправить сразу 2 файла на внешний репозиторий.
+ `git push`
14. На веб интерфейсе создать файл bug_report.txt.
+ В репозитории TXT нажать `add file`
+ Выбрать `Create new file`
+ Вести название файла
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
+ Нажать кнопку `Commit new file`
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
+ Открыть файл bug_report.txt Выбрать редактирование. Ввести текст
```
Summary: Displaying a characteristic associated with a deleted group
Priority: Major
Severity: Midle
Status: To do
Environment: Desktop, Windows10 x64, Chrome97
Descriprion:
  Precondition:
      1. Authorization in your personal account,
      2. Switch the mode to store management (store_url/admin/home),
      3. In the sidebar, expand the "Catalog" list,
      4. The submenu "Characteristics" is open",
      5. Characteristics "Test", "Test 1", "Test 2" are included in the group of characteristics "Overall dimensions",
      6. The subgroup "Groups of characteristics" is opened
   Steps to Reproduce:
      1. Click on the kebab menu next to the group "Dimensions",
      2. Select the "Delete" menu in the kebab
   Actual Result:
      1. Group deleted,
      2. When switching to the "Characteristics" tab, the characteristics "Test", "Test 1", "Test 2' are displayed with binding to the deleted group
   Expected Result:
      1. Group deleted,
      2. When switching to the "Characteristics" tab, the characteristics "Test", "Test 1", "Test 2" are displayed without binding to the remote group
 Attachment: https://drive.google.com/file/d/1KAg5XKZQIQC6zYaOxrDbs2ng1LBuOxcz/view?usp=sharing
 Assignee: -
 Reporter: Alona Kot
``` 
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
+ Нажать кнопку `Commit changes`
18. Синхронизировать внешний и локальный репозиторий TXT
+ `git pull`
