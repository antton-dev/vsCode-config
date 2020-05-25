# vsCode-config
Memo configuration pour VSCode

## Préparation des fichiers
Pour commencer, à la racine du projet, créer un **dossier** `.vscode`, contenant un **fichier** `settings.json`.

## Association extension/langage
Pour associer un langage avec une extension, placer ce code dans le fichier `settings.json`.

    {
        "files.associations": {
        "*.extension": "langage",
        }
    }
    
### Correspondances
|Extension|   Langage   |
|---------|-------------|
|  *.html |    html     |
|  *.html | django-html |
|  *.css  |     css     |
|  *.py   |    python   |
|  *.php  |     php     |
|  *.js   | javascript  |
|  *.json |    json     |
