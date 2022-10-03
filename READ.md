# Exemple pour le cours versioning de code - l'outil Git
## EFREI 03/10/22 

# Gros titre (h1)
## Sous-titre (h2)
### Plus petit (h3)
#### Encore plus petit (h4)
##### Toujours plus petit (h5)
###### Le plus petit (h6) 

_Je suis un super paragraphe en italique_\
_avec un retour à la ligne_\
**Je suis un paragraphe en gras.**

| Syntax    | Description | Test |
| :------:  | :---------: | ---: |
| Header    | Title       | Texte|
| Paragraph exemple à aligné à gauche | Texte exemple centré | Texte exemple à aligné à droite |

Je suis une nouvelle phrase !

## Résumé matinée

| Commande | Options | Fonction |
| :------ | :-----: | :------: |
| git init | | Initialiser un projet Git |
| git config user.email | | Définir l'e-mail de l'utilisateur courant pour Git |
| git config user.name | | Définir le nom de l'utilisateur courant pour Git |
| git status | | Afficher le statut actuel de la branche courante |
| git add | | "Stage" un ou plusieurs fichiers |
| git commit | --amend | Modifier le message du dernier commit |
| git commit | -m | Ajouter un message au commit en ligne de commande |
| git tag | [-a, -m, -d, -f] [commit or tag number] | Ajouter, supprimer ou déplacer un tag sur un commit donné |
| git show | [commit number] | Afficher les informations relatives à un commit donné |
| git diff | [file] | Afficher les changements entre maintenant et le dernier commit sur un ou tous les fichiers |
| git log | | Afficher la liste des commits sur la branche actuelle |
| git reset | --soft, --hard | Revenir à un état précédent de notre code projet |
| git ls-files | | Liste les fichiers suivis par Git |
| git rm | --cached | | Retirer un ou plusieurs fichiers de l'historique de suivi de Git |
| git restore | --staged | | Unstage un ou plusieurs fichiers |
| git branch | -M, -d, -a (--all) | Créer ou renommer une branche de travail |
| git merge | | Permet de fusionner l'historique Git de deux branches |
| git push [<alias> <branche>] | -u (--set-upstream) | Envoie le code source et l'historique des versions sur le dépôt distant mentionnée |
| git stash | | Retire et stocke en mémoire les changements non commité de la branceh actuelle |
| git stash apply | Applique les changements du dernier patch sur la branche courante |
| git fetch | -p forcée | récupérer les nvtés des autres branches et fichier |