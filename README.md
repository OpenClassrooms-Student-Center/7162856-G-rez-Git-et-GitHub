# Open Source Project OpenClassrooms

Bienvenue sur le README!

Pour cloner le projet en local sur votre machine, copiez l'URL de ce repo et lancez la commande suivante:  

`git clone https://github.com/OpenClassrooms-Student-Center/7162856-G-rez-Git-et-GitHub.git`

il fat également git clone <ORIGINAL_ORIGIN>
git branch -r | awk -F'origin/' '!/HEAD|master/{print $2 " " $1"origin/"$2}' | xargs -L 1 git branch -f --track 
git fetch --all --prune --tags
git pull --all
