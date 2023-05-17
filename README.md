# XML

###  1. Создать внешний репозиторий c названием XML

    Repositories -> New -> Repos Name:JSON -> Check "Add a README file" -> Press "Create repository"
   
###  2. Клонировать репозиторий JSON на локальный компьютер

    git clone <repository HTTPS>
    
###  3. Внутри локального JSON создать файл "new.xml"

    touch new.xml
    
### 4. Добавить файл под гит

    git add . или git add new.xml
    
### 5. Закоммитить файл

    it commit -m "любой комментарий"
    
### 6. Отправить файл на внешний GitHub репозиторий

    git push
    
### 7. Отредактировать содержание файла “new.xml” написать информацию о себе в формате XML (ФИО, возраст, количество домашних животных, будущая желаемая зарплата)

    vim new.xml -> input data -> esc -> enter ":wq"
    
### 8. Отправить изменения на внешний репозиторий

    git add . && git commit -m "любой комментарий"
    git push
    
### 9. Создать файл preferences.xml

    touch preferences.xml
    
### 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON

    vim preferences.xml -> insert data -> esc -> enter ":wq"
    
### 11. Создать файл skills.xml. Добавить информацию о скиллах которые будут изучены на курсе в формате XML

    touch skills.xml
    
### 12. Отправить сразу 2 файла на внешний репозиторий

    git commit -a -m "любой комментарий"  
    git push
    
### 13. На веб интерфейсе создать файл bug_report.xml

    Add file -> Create new file -> Name: bug_report.xml
    
### 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе

    Commit New File
    
### 15. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML

    Choose bug_report.xml -> Edit this file
    
### 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе

    Commit changes
    
### 17. Синхронизировать внешний и локальный репозиторий XML

    git pull
   
