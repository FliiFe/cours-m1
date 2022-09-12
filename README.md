# Cours de M1

Je met dans ce repo mes notes de cours de M1, sans garantie que mes notes sont correctes, à jour, complètes, etc. Mes matières du premier semestre sont a priori: Advanced Algebra, Advanced Geometry, Advanced Analysis, Quantum Computer Science.

### Compilation

Un Makefile (autodocumenté) permet la compilation aisée des fichiers du repo. Il faut avoir installé `latexmk`.
Pour obtenir une liste des targets disponible, utiliser simplement `make`. Pour tout compiler, utilise `make all`.

### PDF Compilés

À chaque push, Github Actions se charge de compiler le projet et déploie les fichiers compilés en tant que release.
La dernière version des fichiers compilés est donc toujours disponible [ici](https://github.com/FliiFe/cours-m1/releases/latest)

Le fichier `cours.zip` contient l'ensemble de tous les fichiers compilés, y compris les pdf des chapitres compilés individuellement.
