#  Репозиторий с командами, которые были использованы при выполнении практического задания 8.5

### Задание 1

```git
git clone https://github.com/AndZhelBack/AndZhelBack
cd ..
git clone https://github.com/testrusau/testrusau
*editing of README.md via VS Code*
git add .
git commit -m "upd README"
git push
```
### Задание 2

```git
git init api_testing
cd api_testing
git remote add origin https://github.com/AndZhelBack/api_testing.git
touch README.md
git add .
git commit -m "add README"
git push --set-upstream origin master

cd ..
git init web_testing
cd web_testing
git remote add origin https://github.com/AndZhelBack/web_testing.git
touch README.md
git add .
git commit -m "add README"
git push --set-upstream origin master
```
