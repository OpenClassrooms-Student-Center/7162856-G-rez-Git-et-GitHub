# Open Source Project OpenClassrooms

Bienvenue sur le README!

Pour cloner le projet en local sur votre machine, copiez l'URL de ce repo et lancez la commande suivante:  

`git clone https://github.com/OpenClassrooms-Student-Center/7162856-G-rez-Git-et-GitHub.git`

Pour récupérer les modifications, lancez un `git pull`!

Le cours est loin d'être explicite, concernant les branches affiché dans le gitbash (new-version-css et update-readme)
avec les commandes envoyées, elles n'apparaissent pas... J'ai du demander à un ami comment faire et voici sa réponse.

faire un git fetch --all

la, on peut apercevoir les différentes branches qui sont dans le repository d'openclassrooms.

pour accéder à ces branches, il faut ensuite faire la commande suivante (à répéter pour chaque branche bien sur)

git checkout --track origin/'nomDeLaBranche'
exemple : 
git checkout --track origin/new-version-css

Et la vous pourrez alors avoir accès aux branchs depuis votre bash.

Concernant le pull request, c'est à taton que j'écris ce texte après avoir fait un fork dans mon repository.
Car avec le manque d'étape explicative dans le cours, je n'ai aucun bouton "compare et pull request" sur le repository d'openclassrooms... 
Je tourne en rond depuis tout à l'heure donc si vous tomber sur ce message et que cela fonctionne, hallelujah
