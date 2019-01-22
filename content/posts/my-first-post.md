---
title: "My First Post"
date: 2019-01-22T10:10:30+07:00
---
# Это самый первый-препервый пост
## Пример .bat файла, который обновляет сайт на d0s.github.io

```bash
echo -e "\033[0;32mDeploying updates to GitHub...\033[0m"

rem Build the project. if using a theme, replace with `hugo -t <YOURTHEME>`
hugo -t techdoc -c content -b "https://d0sl.github.io"

rem Go To Public folder
cd public
rem Add changes to git.
git add .

rem Commit changes.
git commit -m "Rebuilding doc-site"

rem Push source and build repos.
git push origin master

rem Come Back up to the Project Root
cd ..
```
