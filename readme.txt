
Якщо зміни не вносилися:
git pull origin develop-merge
термінал
git merge develop-merge

vscode
Reset to base
Manual Resolution


git add .
git commit -m "Add section"
git push

Якщо зміни вносилися:
git pull origin develop-merge
git merge develop-merge

vscode
При виникненні конфлікту натискаємо Resolve in Merge Editor у vs code

Є 3 вікна: 
Incoming - зміни з гіглки develop-merge 
Current - зміни в нашій робочій гілці (header)
Result - як буде виглядати остаточний варіант


Вікно: Incoming (develop-merge)
Accept Incoming
Accept Combination (Incoming first)
Ignore

Вікно: Current (header)
Accept Current
Accept Combination (Current first)
Ignore

Result (header)
Remove Incoming
Remove Current
Rebase -?



Після вирішення конфлікту - натискаємо Complit merge у vscode
Потім маємо зробити commit

git commit -m "Add section"
git push