## Homework GitHub_1

TXT
 1. Создать внешний репозиторий c названием TXT.

в интерфейсе GitHub создаем репозиторий с названием HW1_GIT_TXT
 
`вкладка repositories --> new`

 2. Клонировать репозиторий TXT на локальный компьютер.

клонируем репозиторий через Терминал `git clone ссылка на репозиторий`git

 3. Внутри локального TXT создать файл “new.txt”.

в Терминале переходим в папку репозитория TXT (HW1_GIT_TXT) и создаем файл hw1_git_new.txt `touch hw1_git_new.txt`

 4. Добавить файл под гит.

в Терминале добавляем файл в индекс `git add hw1_git_new.txt`

 5. Закоммитить файл.

`git commit -m "добавлен файл hw1_git_new.txt"`

 6. Отправить файл на внешний GitHub репозиторий.

`git push`

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

открываем файл на локальной машине, редактируем и сохраняем (например, в pycharm или VSCOde)

 8. Отправить изменения на внешний репозиторий.

`git add hw1_git_new.txt&&git commit -m "в файл hw1_git_new.txt добавлена общая информация о пользователе" && git push`

 9. Создать файл preferences.txt

на локальной машине через Терминал создаем в папке репозитория TXT (HW1_GIT_TXT) файл hw1_git_preferences.txt `touch hw1_git_preferences.txt`

 10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

открываем файл на локальной машине, редактируем и сохраняем (например, в pycharm или VSCOde)

 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 
- на локальной машине через Терминал создаем в папке репозитория TXT (HW1_GIT_TXT) файл hw1_git_skills.txt `touch hw1_git_skills.txt`
- открываем файл на локальной машине, редактируем и сохраняем (например, в pycharm или VSCOde)

 12. Сделать коммит в одну строку.

````
git add hw1_git_preferences.txt hw1_git_skills.txt
git commit -m "добавлено два файла hw1_git_preferences.txt hw1_git_skills.txt"
````

 13. Отправить сразу 2 файла на внешний репозиторий.

`git push`

 14. На веб интерфейсе создать файл bug_report.txt.

````
- заходим в веб интерфейс GitHub
- переходим в репозиторий TXT (HW1_GIT_TXT)
- создаем файл при помощи add file --> create new file hw1_git_bug_report.txt
````

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

````
- в веб интерфейсе GitHub в нижней части экрана заполняем title коммита (но сейчас description не заполняем, потому что 
коммит простой и в детальном описании нет необходимости)
- оставляем по умолчанию выбранный радиобаттон - commit directly to the main branch (поскольку работаем именно с main)
- в нижней части окна с файлом нажимаем кнопку commit new file
````

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.

```
- заходим в веб интерфейс GitHub
- переходим в репозиторий TXT 
- переходим в режим редактирования файла hw1_git_bug_report.txt (иконка редактирования в правой части)
- добавляем информацию о баге в формате txt в файл hw1_git_bug_report.txt
```

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

````
- в веб интерфейсе GitHub в нижней части экрана заполняем title коммита (но сейчас description не заполняем, потому что 
коммит простой и в детальном описании нет необходимости)
- оставляем по умолчанию выбранный радиобаттон - commit directly to the main branch (поскольку работаем именно с main)
- в нижней части окна с файлом нажимаем кнопку commit new file
````



 18. Синхронизировать внешний и локальный репозиторий TXT

`git pull && git push`
