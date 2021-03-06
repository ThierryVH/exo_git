# Défis GIT

### Défi n°1
- Déplacez-vous dans le dossier **sites/lab/**
- Créez un dossier **exo_git**. Déplacez-vous y
- Créez un dossier **defi_git_1**. Déplacez-vous y
- Initialiser un dépôt GIT
- Créez 2 fichiers:
  - **Fichier1**
  - **Fichier2**
- Affichez le statut du répertoire
- Ajoutez les deux fichiers aux éléments qui doivent être suivis
- Affichez le statut du répertoire
- Enregistrez les changements (les valider avec un **commit**)
- Affichez le statut du répertoire
- Éditez le **Fichier1** en lui ajoutant du texte (avec un éditeur en ligne de commande : Vim, Nano, Emacs, etc.), et enregistrez les modifications sur le fichier
- Affichez le statut du répertoire
- Ajoutez le fichier aux éléments qui doivent être suivis
- Enregistrez les changements (les valider avec un **commit**)
- Supprimez le **Fichier2**
- Ajoutez le fichier aux éléments qui doivent être suivis
- Enregistrez les changements (les valider avec un **commit**)
- Afficher les commits (**q** pour quitter)

### Défi n°2
- Déplacez-vous dans le dossier **sites/lab/exo_git**
- Créez un dossier **defi_git_2**. Déplacez-vous y
- Initialiser un dépôt GIT
- Créez 2 fichiers:
  - **Fichier1**
  - **Fichier2**
- Ajoutez les deux fichiers aux éléments qui doivent être suivis
- Affichez le statut du répertoire
- Annulez l'ajout du **Fichier2** aux éléments qui doivent être suivis
- Affichez le statut du répertoire
- Enregistrez les changements (les valider avec un **commit**)
- Affichez le statut du répertoire
- Ajoutez le **Fichier2** aux éléments qui doivent être suivis
- Affichez le statut du répertoire
- Enregistrez les changements (les valider avec un **commit**)
- Listez les branches du dépôt (vous devriez voir la branche **master**)
- Créez une nouvelle branche avec votre prénom
- Listez à nouveau les branches du dépôt
- Créez un fichier **Fichier3**
- Listez le contenu du dossier
- Ajoutez le **Fichier3** aux éléments qui doivent être suivis
- Enregistrez les changements (les valider avec un **commit**)
- Déplacez-vous sur la nouvelle branche créée
- Listez le contenu du dossier. Que remarquez-vous?
- Fusionnez le contenu de la branche **master** sur la nouvelle branche pour récupérer le fichier manquant
- Listez le contenu du dossier

### Défi n°3
- Déplacez-vous dans le dossier **sites/lab/exo_git**
- Supprimez les dossiers **defi_git_1** et **defi_git_2**
- Créez un dossier **defi_git** et déplacez-vous y
- Créez 2 fichiers:
  - **Fichier1**
  - **Fichier2**
- Ajoutez les 2 fichiers aux éléments qui doivent être suivis
- Enregistrez les changements (les valider avec un **commit**)
- Listez les branches du dépôt et regardez sur laquelle vous vous trouvez
- Créez une branche **test** et déplacez-vous y
- Listez le contenu du dossier
- Créez 2 nouveaux fichiers
- Déplacez-vous sur la branche **master**
- Enregistrez les changements (les valider avec un **commit**)
- Listez le contenu du dossier
- Déplacez-vous sur la branche **test**
- Listez le contenu du dossier. Pourquoi les 2 nouveaux fichiers n'existent pas sur cette branche alors qu'ils y ont été créés?
- Fusionnez le contenu de la branche **master** sur la branche **test**
- Listez le contenu du dossier
- Déplacez-vous sur la branche **master**
- Supprimez la branche **test**
- Listez les branches du dépôt
- Ajoutez du texte au **Fichier1** et enregistrez les modifications
- Ajoutez le **Fichier1** aux éléments qui doivent être suivis
- Enregistrez les changements (les valider avec un **commit** et le commentaire "edit Fichier2")
- Listez les commits
- Le message du commit n'est pas bon, nous avons modifié le **Fichier1**, et non le **Fichier2**. Modifiez le message du dernier commit (Astuce: **git commit --amend**)
- Listez à nouveau les commits

### Défi n°4
- Déplacez-vous dans le dossier **sites/lab/exo_git**
- Créez un dossier **defi_git_4** et déplacez-vous y
- Créez le fichier **index.html** et ajoutez-y le code suivant
```<!DOCTYPE html>
<html lang="fr">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>Défi Git 4</title>
</head>
<body>

	<p>Premier paragraphe</p>

</body>
</html>
```
- Faites un commit pour enregistrer les modifications
- Créez une branche **css** et déplacez-vous y
- Créez le fichier **style.css** et ajoutez-y le code
```
p {
	border: 2px solid black;
	padding: 15px 20px;
	color: red;
	font-size: 2em;
}
```
- Modifiez le fichier **index.html** en ajoutant la ligne
```
<link rel="stylesheet" href="style.css">
```
juste après la ligne
```
<title>Document</title>
```
- Et ajoutez un deuxième paragraphe
```
<p>Deuxième paragraphe</p>
```
- Enregistrez les modifications avec un commit
- Listez les commits
- Déplacez vous sur le premier commit
- Créez une nouvelle branche à partir de ce commit et déplacez-vous y
- Observez le contenu de votre fichier **index.html**. Il n'y a plus qu'un paragraphe.
- Ajoutez y un troisième paragraphe.
- Enregistrez les modifications avec un commit
- Listez les commits
- Déplacez vous sur la branche **css**
- Listez les commits
- Fusionnez le contenu de la troisième branche créée avec la branche **css**. Un problème? Un conflit? À vous de le résoudre.
- Une fois le conflit résolu, commitez les changements
- Créez un repository sur github (donnez lui le nom que vous voulez)
- Ajouter la remote à votre dossier (voir git remote add)
- Envoyer votre travail sur github

### Défi n°5
- Déplacez-vous dans le dossier **sites/lab/exo_git**
- Créez un dossier **defi_git_5** et déplacez-vous y
- Créez le fichier **index.html** et ajoutez-y le code suivant
```<!DOCTYPE html>
<html lang="fr">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>Défi Git 5</title>
</head>
<body>

	<p>Premier paragraphe</p>

</body>
</html>
```
- Faites un commit pour enregistrer les modifications
- Créez une branche **test**
- Vous êtes toujours sur la branche **master**. Modifiez le fichier **index.html** en rajoutant un paragraphe
- Faites un commit pour enregistrer les modifications
- Déplacez-vous sur la branche **test**, et fusionnez-là avec la master
- Créez un fichier **style.css**
- Faites un commit pour enregistrer les modifications
- Créez une branche **css** et déplacez-vous dessus
- Supprimez la branche **test**
- Créez un repository sur github (donnez lui le nom que vous voulez)
- Ajoutez la remote à votre dossier
- Envoyer votre travail sur github
- Sur github directement, modifiez les fichiers **index.html** et **style.css** en y ajoutant le code que vous voulez
- Revenez sur votre éditeur de texte en local (Atom, Sublime, etc.) et faites également des modifications sur les fichiers **index.html** et **style.css**
- Faites un commit
- Envoyez votre travail sur github. Un problème? À vous de le résoudre
- Modifiez à nouveau votre fichier **index.html** en supprimant le premier paragraphe et en y ajoutant un nouveau paragraphe.
- Faites un commit
- Listez les commits
- Afficher les différences entre votre travail actuel, et le travail enregistré lors du premier commit (voir **git diff**)
- Même chose entre votre travail actuel et celui enregistré lors du troisième commit
