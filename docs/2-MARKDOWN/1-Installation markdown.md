# Installation Markdown sur MAC

## Procédure pour Installer Markdown avec Visual Studio Code et GitHub Desktop

Cette procédure vous guidera à travers l'installation de **Visual Studio Code**, **GitHub Desktop**, et l'utilisation de **Markdown** pour créer et gérer des fichiers de documentation.

## 1. Installation de Homebrew (Facultatif)

Pour faciliter l'installation des différents outils, nous allons d'abord installer **Homebrew**, un gestionnaire de paquets pour macOS. Si vous avez déjà Homebrew, vous pouvez passer cette étape.

### Étape 1 : Installer Homebrew

1. **Ouvrez le Terminal** (Cmd + Espace, tapez "Terminal" et appuyez sur Entrée).
2. **Tapez la commande suivante** pour installer Homebrew :

   ```sh
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

3. **Ajoutez Homebrew au PATH** (si nécessaire) en suivant les instructions affichées à la fin de l'installation.
4. **Vérifiez l'installation** en tapant :

   ```sh
   brew --version
   ```

## 2. Installation de Visual Studio Code

**Visual Studio Code** (VS Code) est un éditeur de texte puissant que nous utiliserons pour écrire du Markdown.

### Étape 1 : Télécharger Visual Studio Code

1. Allez sur le site officiel de **Visual Studio Code** : [https://code.visualstudio.com/](https://code.visualstudio.com/).
2. Cliquez sur le bouton **Download** pour télécharger la version pour **macOS**.
3. Une fois téléchargé, **ouvrez le fichier `.dmg`** et **glissez** l'icône de Visual Studio Code dans le dossier **Applications**.

### Étape 2 : Lancer Visual Studio Code

1. Ouvrez le dossier **Applications** et double-cliquez sur **Visual Studio Code** pour le lancer.
2. Vous pouvez également installer **l'outil en ligne de commande** `code` en utilisant Visual Studio Code. Ouvrez VS Code, appuyez sur `Cmd + Shift + P`, puis tapez "Shell Command: Install 'code' command in PATH".

## 3. Installation de GitHub Desktop

**GitHub Desktop** est une interface graphique qui vous permet de gérer vos dépôts Git sans utiliser directement la ligne de commande.

### Étape 1 : Télécharger GitHub Desktop

1. Allez sur le site officiel de **GitHub Desktop** : [https://desktop.github.com/](https://desktop.github.com/).
2. Cliquez sur le bouton **Download for macOS** pour télécharger le fichier d'installation.
3. Ouvrez le fichier `.dmg` téléchargé et **glissez** l'icône de GitHub Desktop dans le dossier **Applications**.

### Étape 2 : Lancer GitHub Desktop

1. Allez dans le dossier **Applications** et ouvrez **GitHub Desktop**.
2. Suivez les instructions pour **vous connecter** à votre compte GitHub ou en créer un.

## 4. Installation de Git

Git est un outil de gestion de version qui vous permet de suivre les modifications apportées à vos fichiers Markdown.

### Étape 1 : Installer Git avec Homebrew

1. **Ouvrez le Terminal**.
2. Tapez la commande suivante pour installer **Git** :

   ```sh
   brew install git
   ```

3. **Vérifiez l'installation** en tapant :

   ```sh
   git --version
   ```

## 5. Créer et Gérer des Fichiers Markdown

Maintenant que tous les outils sont installés, vous pouvez créer des fichiers Markdown et les gérer avec Git et GitHub.

### Étape 1 : Créer un Nouveau Fichier Markdown

1. **Ouvrez Visual Studio Code**.
2. **Créez un nouveau fichier** : Appuyez sur `Cmd + N` pour créer un nouveau document, puis enregistrez-le en tant que `mon_fichier.md`.
3. **Commencez à écrire en Markdown** en utilisant la syntaxe Markdown (par exemple, `# Titre`, `- Liste à puces`, etc.).

### Étape 2 : Versionner avec Git et GitHub Desktop

1. **Ouvrez GitHub Desktop**.
2. **Créez un nouveau dépôt** ou **clonez un dépôt existant**.
3. **Ajoutez vos fichiers Markdown** au dépôt en les plaçant dans le dossier de votre dépôt local.
4. Utilisez **GitHub Desktop** pour **committer** vos modifications et les **pusher** vers GitHub.

### Étape 3 : Synchroniser avec GitHub

1. Pour chaque modification dans Visual Studio Code, enregistrez le fichier (`Cmd + S`).
2. Dans GitHub Desktop, ajoutez un **commit message** pour décrire la modification, puis **Commit to main**.
3. Cliquez sur **Push origin** pour synchroniser vos modifications avec le dépôt distant sur GitHub.

## 6. Résumé

- **Homebrew** : Permet d'installer des outils facilement.
- **Visual Studio Code** : Utilisé pour éditer des fichiers Markdown.
- **GitHub Desktop** : Interface graphique pour gérer vos projets Git.
- **Git** : Outil de gestion de version.







# Installation Markdown sur Windows