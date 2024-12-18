# Projet_DataScience_Classification_E-commerce

L'objectif de ce projet réalisé avec OpenClassrooms était d'identifier, pour la marketplace "Place de Marché", la faisabilité d'un moteur de classification automatique des produits à partir de leurs description produits et de leurs images produits.

Ainsi, il y avait deux types de modélisations qui était possible :

     - La modélisation textuelle (NLP)
     - Le traitement d'images (Computer Vision)

Pour chacun des 2 types de modélisation le principe était d'appliquer différents algorithmes sur l'ensemble des données ou une partie de celles-ci (pour la modélisation textuelle : titre uniquement, description uniquement, titre+description).

Ces algorithmes transformaient ces données en vecteurs de nombres. Chaque vecteur représentait ainsi un produit. Ensuite, il s'agissait d'appliquer un K-Means à ces vecteurs pour pouvoir les répartir en 7 groupes. Nous pouvions ensuite voir si ces groupes de vecteurs correspondaient au 7 catégories établies sur la marketplace "Place de Marché".

Le fichier P6_01_notebook.ipynb présente le traitement de la base de données utilisée pour ce projet ainsi que les résultats des différents algorithmes mis en oeuvre pour transformer une image ou un texte d'un produit en un vecteur.

Le fichier P6_02_presentation.pptx présente la démarche qui a été mise en oeuvre tout au long du projet ainsi que les conclusions sur la faisabilité du moteur de classification automatique.
