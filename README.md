# Formation GitHub

## Introduction
GitHub est une plateforme de gestion de versions et de collaboration permettant de stocker, partager et gérer du code source à l'aide de Git. Ce document présente les concepts fondamentaux à comprendre pour une utilisation efficace de GitHub.

---

## Contenu d'un Dépôt GitHub
Un dépôt GitHub contient :
- **Fichiers textes** (ex. : `.txt`, `.md`, `.py`, `.cpp`, etc.)
- **Code source** de projets logiciels
- **Historique des modifications**

**Attention :** GitHub **ne fonctionne pas bien** avec certains types de fichiers binaires qui ne sont pas lisibles par un éditeur de texte comme Notepad, tels que :
- Fichiers audio (`.wav`, `.mp3`)
- Documents bureautiques (`.docx`, `.xlsx`)
- Images (`.png`, `.jpg`)

Ces fichiers binaires peuvent générer des conflits et des problèmes d'encodage (ex. : affichage de caractères UTF-8 bizarres). Pour ces types de fichiers, il est recommandé d'utiliser des solutions alternatives comme Git LFS (Large File Storage) ou d'éviter de les stocker dans Git.

---

## Concepts Clés
### 1. Dépôt (Repository)
Un **dépôt** est l'espace où est stocké tout le code source ainsi que son historique des modifications.

### 2. Fork
Un **fork** est une copie d'un dépôt existant, permettant à un utilisateur de modifier le code sans affecter l'original. Il permet de :
- Expérimenter sans modifier la source
- Proposer des améliorations via des *Pull Requests*
- Contribuer à des projets open-source

### 3. Branches
Une **branche** représente une version spécifique du projet. Les branches permettent de travailler sur différentes fonctionnalités ou corrections en parallèle.
- La branche principale est souvent `main` ou `master`.
- Créer une nouvelle branche revient à copier tout le code du projet.

### 4. Commit & Push
- **Commit** : Sauvegarde locale d'une modification dans Git.
- **Push** : Envoie les modifications locales vers le dépôt distant sur GitHub.

Workflow classique :
1. **Modifier** un fichier
2. **Commit** : `git commit -m "Description de la modification"`
3. **Push** vers GitHub : `git push`

---

## Licence
Pour s'assurer que le code peut être utilisé par d'autres, il est recommandé d'ajouter une **licence** au projet.
La licence **MIT** est l'une des plus courantes, car elle permet une utilisation commerciale, académique et privée sans restriction.

Exemple de fichier `LICENSE` :
```
MIT License

Copyright (c) [année] [auteur]

Permission est accordée, gratuitement, à toute personne obtenant une copie
...
```

---

## Bonnes Pratiques
### 1. Ne pas modifier le dossier `.git`
Le dossier `.git` contient toute l'historique et la configuration du dépôt. **Ne jamais le modifier manuellement.**

### 2. Suivre un cycle de commits et push réguliers
Respecter une discipline de versionnement permet d'éviter la perte de travail et de faciliter le suivi des modifications :
- **Commit** : toutes les **1 heure** pour enregistrer les changements significatifs.
- **Push** : au moins **1 fois par jour** pour synchroniser le travail sur GitHub.

---

## Conclusion
GitHub est un outil puissant pour le développement collaboratif et la gestion de versions. En respectant ces bonnes pratiques, vous pourrez travailler efficacement tout en minimisant les risques de conflits et de perte de données.

Happy coding ! 🚀

