JSON
 1. Создать внешний репозиторий c названием JSON. 
Create repository
 2. Клонировать репозиторий JSON на локальный компьютер.
git clone git@github.com:JackBlaaack/JSON.git
 3. Внутри локального JSON создать файл “new.json”.
cd JSON 
touch new.json
 4. Добавить файл под гит.
git add .
 5. Закоммитить файл.
git commit -m "adding new.json"
 6. Отправить файл на внешний GitHub репозиторий.
git push
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
{
"name": "Jack",
"age": 27,
"countofpets": 0,
"futuresalary": 1500
}

 8. Отправить изменения на внешний репозиторий.
git fetch
git pull
 9. Создать файл preferences.json
touch preferences.json
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
vim preferences.json
i
{
        "preferences":[
        {"favoritefilm": "HarryPotter",
        "favoriteserial": "HowImetYourMum",
        "deliciousfood": "Meat in french",
        "favoritetimeofyear": "Spring",
        "favoriteCountry": "TheUSA"
        }
        ]
}

 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
touch sklls.json
vim sklls.json
i
{
        "skills": [
        {
        "GitBash",
        "HTML",
        "JIRA",
        "TestTrail",
        "TestCase",
        "Checklist",
        "JavaScript"
        }
        ]
}

 12. Отправить сразу 2 файла на внешний репозиторий.
git add .
git commit -am "Adding 2 new files"
git push
 13. На веб интерфейсе создать файл bug_report.json.
Add new file
Create new file
bug_reprt.json
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Writing Bug report
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
{
  "BugReport": [
    {
    "Summary": "Menu:error, at the entrance",
    "Type": "Bug",
    "Priority": "Medium",
    "Severity": "Major",
    "AffectsVersion": 1.0,
    "Enviroment": "Windows 10 Pro, Google Chrome 98",
    },
    "Description": [
    {
    "FirstStep": "Open web-site",
    "SecondStep": "pass authorization",
    "ThirdStep": "Press the button Menu",
    "FourthStep": "Pay attention to the screen",
    "ExpectedResult": "Press the button Menu and see categories of products",
    "Result": "Press the button Menu and see eror"
    }
    ],
    "Status": "Open",
    "TypeofBug": "Functional"
}
]
}
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Writing bug reprt
 17. Синхронизировать внешний и локальный репозиторий JSON
git fetch
git pull 
git push

