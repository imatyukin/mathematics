# mathematics

Создать новый репозиторий:
```
echo "# mathematics" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/imatyukin/mathematics.git
git push -u origin master
git add *
git commit -m "Элементарная математика. Повторительный курс"
git push -u origin master
```
Автоматически добавить в индекс измененные и удаленные файлы и сделать commit:
```
git commit -a -m "Элементарная математика. Повторительный курс"
```
Сделать push только ветки master:
```
git push origin master
```
