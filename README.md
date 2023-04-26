# TXT

1. Create an external repository with a name TXT.
+ Open https://github.com/, Login in 
+ Go to tab _"Repositories"_
+ Press _"New"_
+ Enter the name of the repository, make it public
+ Press _"create repository"_

 2. Clone repository TXT to the local computer.
+ open GitBash in the folder where the repository will be stored
+ enter the command on the command line _git clone + link to the repository we want to clone_

 3. Create file inside local TXT _new.txt_.
+ _cd TXT_ - go to local repository
+ _cat > new.txt_
+ _ctrl + c_ - get out of editing
 4. Add file on git.
+ _git add new.txt_ - to add a particular file
+ _git add ._ - to add all files
 5. Commit the file.
+ _git commit -m "new file"_
 6. Submit a file to an external GitHub repository.
+ _git push_
 7. Edit file content _new.txt_ - write information about yourself (name, age, number of pets, future desired salary). Write everything in the format TXT.
+ _cat > new.txt_
+ enter data
```
	Full name: Alona Kot
	age: 25
	Pets: 1
	Disired Salary: 600$
 ```
+ _ctrl + c_ - get out of editing

 8. Push changes to an external repository.
+ _git add new.txt_ - add the changed file to git
+ _git commit -am "edit file"_ - commit changes
+ _git push_ - push modified file to external repository 
 9. Create file _preferences.txt_
+ _cat > preferences.txt_
 10. To file _preferences.txt_ add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in the format TXT.
+ Enter text
```
	Favorite movie: "Indiana Jones"
	Favorite serias: "Scrubs"
	Favorite food: Burgers
	Country you would like to visit: Switzerland
```
+ _ctrl + c_ - get out of editing
 11. Create file _sklls.txt_ add information about the skills that will be studied on the course in the format TXT
+ _cat > sklls.txt_
+ Enter data:
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
+ _ctrl + c_ - get out of editing
 
 12. Make a commit in one line.
+ _git commit -m "new files"_
 13. Upload 2 files at once to an external repository.
+ _git add ._
+ _git push_
 14. Create a file on the web interface _bug_report.txt_
+ In the repository TXT press _"add file"_
+ Choose _"Create new file"_
+ Enter the file name
 15. Do Commit changes (save) changes on the web interface.
+ Press the button _"Commit new file"_
 16. Modify the file on the web interface _bug_report.txt_, add a bug report in the format TXT.
+ Open file _bug_report.txt_  Select edit. Enter text
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
 17. Do Commit changes (save) changes on the web interface.
+ Press the button _Commit changes_.
 18. Synchronize external and local repository TXT
+ _git pull_
