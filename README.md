# helloFlask

## Installation et utilisation de Pyenv : 
### Installer une version de Python :
`pyenv install X.XX.X`
#### Verifier son installation : 
`python --version`
#### en faire une version par defaut : 
`pyhton global X.XX.X`
#### Installer localement : 
Aller dans le dossier voulu et taper la commande :
`pyenv local X.XX.X`

## Installation et utilisation de Pyenv :
`curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -`
### Vérification de l'installation :
`poetry --version`
Il se peut qu'il y ait besoin de redemarrer la session. (Srun en prompt source ./.poetry/bin) précisé à la fin de l'install

### Pour créer un dossier : 
Se mettre dans le dossier ou on veut créer notre dossier puis :
`poetry new <nom-du-document>`
`cd <nom-du-dossier>`
`touch nom_du_dossier/script.py`

### Pour ajouter un package :
`poetry add paquet`

### run un script :
`poetry run`

### pour partager son script et le rendre exportable :
`poetry build`

