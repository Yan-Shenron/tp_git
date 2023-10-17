# Travaux Pratiques - Git (20 points)

## Objectif
Ce TP a pour objectif de vous familiariser avec les bases de Git, y compris l'initialisation d'un dépôt local, la liaison avec GitHub, la gestion des tokens, la génération de clés SSH, la récupération d'un dépôt distant, la fusion de branches, et la consultation des journaux.

## Étapes

### 1. Initialisation d'un dépôt Git local (4 points)
- Ouvrez votre terminal.
- Crée un dossier pour votre projet puis allez dedans
- Utilisez la commande `git init` pour initialiser un dépôt Git local dans le répertoire de votre choix.
- Ajouter votre projet a votre dit local avec `git add`
- Puis commitez le 

### 2. Lier le dépôt local à mon repo GitHub (1 point)
- Acceptez mon invitation au repository sur GitHub.
- Utilisez la commande `git remote add origin <URL_du_repo>` pour lier votre dépôt local à GitHub.
- Utilisez la commande `git pull origin main` pour récupérer les dernières modifications du dépôt distant.
- Copiez votre code dans le dossier du projet 
-`NE SURTOUT PAS PUSH MAINTENAT (-2 pts)`

### 3. Générer un token (2 points)
- Allez dans les paramètres de votre compte GitHub.
- Sous "Developer settings", générez un token d'accès personnel avec les autorisations nécessaires.

### 4. Générer une clé SSH (3 points)
- Utilisez la commande `ssh-keygen` pour générer une paire de clés SSH.
- Ajoutez votre clé publique à votre compte GitHub.

### 5. Récupérer le dépôt Git distant et fusionner avec une nouvelle branche (5 points)
- Créez une nouvelle branche qui aura pour nom votre prénom avec la commande `git checkout -b <votre prenom>`.
- Effectuez des modifications dans la nouvelle branche comme si on fait un hotfix (correctif).
- Créez une nouvelle branche qui aura pour nom votre prénom-hotfix avec la commande `git checkout -b <votre prenom>-hotfix`.
- Fusionnez la nouvelle branche avec la branche prénom-hotfix en utilisant `git merge`.

### 6. Regarder les journaux en ligne de commande (3 points)
- Utilisez `git log` pour afficher l'historique des commits dans votre dépôt.

### Bonus - Créer une documentation soignée (2 points)
- Vous pouvez améliorer la qualité de votre documentation en utilisant la syntaxe Markdown pour créer des listes, des titres, des blocs de code, etc.

Exemple :

\`\`\`markdown
## Documentation du TP Git

### Étape 1 - Initialisation du dépôt
- Utilisez \`git init\` pour initialiser un dépôt local.

### Étape 2 - Lier au dépôt distant
- Utilisez \`git remote add origin <URL_du_repo>\` pour lier le dépôt local à GitHub.

...

\`\`\`

N'oubliez pas de commenter chaque étape et d'expliquer clairement les commandes utilisées.

## Points totaux : 20 points

Profitez de cette opportunité pour apprendre les bases de Git, une compétence essentielle pour la gestion de versions de code et la collaboration en équipe. Bon travail !
