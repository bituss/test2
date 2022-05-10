#hello
…or create a new repository on the command line
echo "# test" >> README.md #fájl létrehozása, az első sorba '#tesz' kerül 
git init mappa inicializálása
git add README.md #stagig changes, azaz a változtatások mentése.
git commit -m "first commit" #változtatások jóváhagyása, és megjelölés beküldése
git branch -M main #a fejlesztési ág megnevezése a main-re
git remote add origin https://github.com/bituss/test.git
git push -u origin main #a fejlesztési ág feltültetése első alkalommal
…or push an existing repository from the command line
git remote add origin https://github.com/bituss/test.git
git branch -M main
git push -u origin main

git pull origin main #a friss repo letöltése

további terminál parancsok:
get remote -v
#aktuális távoli repo lekérdezése
git status
git comfig --global --list # globális beállítások listázása
#change, stage, commit állapotának lekérdezése
cd <directory name> #change directory
cd .. #egy mappával feljebbi mkdir
mkdir # make directory
rmdir #remove directory
ls #list- könyvtár listázása 
levi buzi