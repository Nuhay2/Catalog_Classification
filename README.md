# Catalog_Classification

Ce projet vise à classifier des produits e-commerce dans leurs catégories respectives (multiclass classification) en utilisant des descriptions textuelles, des titres et des marques.
Le modèle retenu est un LinearSVC couplé à une vectorisation TF-IDF.

Le projet utilise Python 3.13 et le gestionnaire de paquets moderne uv pour la rapidité et la reproductibilité.

Si vous avez uv installé :

# Installer les dépendances et créer l'environnement virtuel
uv sync

# Lancer le notebook
uv run jupyter notebook

Si vous n'utilisez pas uv, un fichier standard est fourni :
pip install -r requirements.txt
jupyter notebook
