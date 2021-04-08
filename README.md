cd .. (si no está en repos)
mkdir lab
cd lab
git flow init -d
git flow feature start f1
git branch
git add unique_words.py (después de haber metido el archivo en la carpeta lab del PC)
git commit -m "list of unique words"
git flow feature finish
git flow release start 1.0
