**Plateforme de gestion de versions et de collaboration** permettant de stocker, partager et gérer du code source à l'aide de [Git](https://git-scm.com/).

---

## 📂 Contenu d'un Dépôt GitHub
- ✅ **Fichiers textes** (ex. : `.txt`, `.py`, `.maxpat`, etc.)
- ✅ **Code source** de projets logiciels
- ✅ **Historique des modifications**

🚨 **Attention :** GitHub **ne fonctionne pas bien** avec certains types de fichiers binaires qui ne sont pas lisibles par un éditeur de texte :
- 🛑 Fichiers audio (`.wav`, `.mp3`)
- 🛑 Projets TouchDesigner (`.tox`, `.toe`)
- 🛑 Images (`.png`, `.jpg`)

Ces fichiers peuvent entraîner des **conflits et des problèmes d'encodage** (affichage de caractères UTF-8). Pour ces types de fichiers, il est recommandé d'utiliser des solutions alternatives comme **Git LFS (Large File Storage)** ou d'éviter de les stocker dans Git (**utiliser Onedrive, Google Drive ou une autre solution de stockage en ligne** à la place).

---

## 🏗️ Concepts Clés
### 1. Dépôt (**Repository**)
Un **dépôt** est l'espace où est stocké **tout le code source et l'historique des modifications**.

### 2. Fork
Un **fork** est une **copie d'un dépôt existant**, permettant à un utilisateur de modifier le code sans affecter l'original. Il permet de :
- 🧪 **Expérimenter** sans modifier la source
- 🛠️ **Proposer des améliorations** via des *Pull Requests*
- 🌍 **Contribuer** à des projets open-source

### 3. Branches
Une **branche** représente une **version spécifique** d'un projet. Les branches permettent de travailler sur différentes fonctionnalités ou corrections en parallèle.
- La branche principale est souvent `main` ou `master`.
- Créer une nouvelle branche revient à **copier tout le code** du projet.

### 4. Commit & Push
- ✅ **Commit** : Sauvegarde locale d'une modification dans Git.
- 🚀 **Push** : Envoie les modifications locales vers le dépôt distant sur GitHub.

🛑 Toutes les modifications sont enregistrées dans un **dossier caché** `.git`, qui contient l'historique et la configuration du projet. **Ne JAMAIS toucher, déplacer ou modifier ce dossier.**

### 🔄 Workflow classique :
- **Modifier** un fichier
- **Commit** : `git commit -m "Description de la modification"`
- **Push** vers GitHub : `git push`

---

## 📜 Licence
Pour s'assurer que le code peut être utilisé par d'autres, il est recommandé d'ajouter une **licence** au projet.

La licence **MIT** est l'une des plus courantes, car elle permet **une utilisation commerciale, académique et privée sans restriction**. 

Les licences **GNU** sont intéressantes pour le logiciel libre, car elles garantissent que personne ne pourra rendre le code propriétaire par la suite.

---

## 🔥 Bonnes Pratiques
📌 Ne jamais modifier le dossier `.git` manuellement.

📌 Suivre un cycle de commits et push réguliers
- ⏳ **Commit** : toutes les **~1 heure** pour enregistrer les changements significatifs (ou jusqu'à ce que **Ctrl-Z** ne soit plus une option).
- 📡 **Push** : au moins **1 fois par jour** pour synchroniser le travail sur GitHub (**En pratique, le push intervient généralement après chaque commit. Il ne signifie pas nécessairement que le code est finalisé ou à jour, d'où l'intérêt des forks).**

📌 Utilisation de **GitKraken** 
🐙 **GitKraken** est un **client Git visuel** qui facilite la **gestion des branches, commits et pushs**. Il est recommandé pour ceux qui préfèrent **une interface graphique** plutôt que la ligne de commande.
