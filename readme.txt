
Якщо зміни не вносилися:

термінал
git merge develop-merge

vscode
Reset to base
Manual Resolution


git add .
git commit -m "Add section"
git push

Якщо зміни вносилися:
git merge develop-merge

vscode
При виникненні конфлікту натискаємо Resolve in Merge Editor у vs code
Після вирішення конфлікту - маємо зробити commit

git commit -m "Add section"
Після commit потрібно синзронізувати git push
git push