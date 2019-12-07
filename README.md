# AIO-Mamary-Gland
Ce Repository contient deux fichiers:
- un fichier MamelleBis.csv qui contient les différentes réactions biochimiques utilisées dans le cadre de la modélisation de la glande mammaire en lactation
- un fichier Mammary Gland.ipynb qui est un code python sur jupyter notebook permettant de calculer les AIO d'une distribution extrémale.
    - Il lit le fichier MamelleBis.csv pour produire un model au format sbml
    - Il permet de calculer une distribution extrémale par le FBA
    - Il calcule les AIO d'une distribution extrémale 
    - Il permet également de donner une estimation des min-max AIO en faisant du sampling sur l'espace de distribution de flux
