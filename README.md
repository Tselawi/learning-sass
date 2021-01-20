# learning-sass

A la source de ton dossier, crée un fichier package.json en tapant la commande :

> npm init  
Tu es prêt à installer la dépendance node-sass :

npm install node-sass
Sass est installé dans ton projet, tu peux donc l'utiliser, mais encore faut-il lui donner les bonnes instructions.

Ca se déroule dans le fichier package.json. Crée le paramètre scripts.

En fonction de comment tu as organisé tes fichiers, note les chemins d'accès de tes fichiers Sass et où tu veux que ton scss soit compilé.

Ici, un exemple :

  "scripts": {
    "scss": "node-sass --watch src/scss -o src/css"
  }
Pour lancer le compilateur, tape dans ton terminal npm run scss et c'est parti !