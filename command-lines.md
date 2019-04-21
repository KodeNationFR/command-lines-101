# Lignes de commande de base

### Les commandes liées aux chemin

`pwd `
> permet d'afficher l'emplacement actuel

` cd `
> permet de changer de dossier (en l’occurrence revenir au répertoire home de l'utilisateur)

` cd dossier/sous-dossier `
> permet de se rendre dans un dossier particulier ( en l'occurrence "sous-dossier" )

` cd .. `
> permet de revenir au dossier parent

` ls `
> permet de lister les éléments du dossier courant, on peut préciser un chemin, on peut également ajouter un drapeau -l qui a pour effet d'afficher plus d'infos sur les éléments du dossier, ou le drapeau -a qui affiche les éléments cachés, il est possible de combiner les 2 drapeaux => ls -la

### Administration des dossiers/fichiers

` mkdir <nom du dossier> `
> permet de créer un dossier

` rmdir <nom du dossier> `
> inverse de "mkdir" !! ne supprime pas un dossier contenant des éléments !!

` touch <nom du fichier> `
> permet de créer un fichier

` rm <nom du fichier> `
> inverse de touch

` mv <nom du fichier/dossier> `
> permet de déplacer et/ou de renommer un fichier/dossier

` rm -r `
> permet de supprimer un dossier ainsi que son contenu !! à utiliser avec précaution, si utiliser au mauvais endroit, peut détruire votre système !!

### Générer une sortie

` cat <nom du fichier> `
> permet d'afficher le contenu d'un fichier dans une sortie de terminal

### Tips

[TAB]
> permet d'auto-completer une commande

[DOWN]
> permet de ré-afficher la dernière commande tapée

[UP]
> permet de ré-afficher les dernières commandes tapées en commençant par la dernière

[CTRL + A] [CTRL + E] [CTRL + C]
> ctrl + a permet de placer le curseur au début de la ligne, crtl + e place le curseur en fin de ligne, ctrl + c stop une commande en cour d'éxécution

` clear `  ou [CTRL + L]
> nettoie l'affichage de votre terminal

`exit`
> ferme le terminal

` help ` ou `<commande help>`
> vous affiche les commande possibles en fonction du contexte
