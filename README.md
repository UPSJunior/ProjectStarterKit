# Modèle de Projet Préparamétré

Ce repository contient un modèle de projet préparamétré qui peut être dupliqué pour démarrer de nouveaux projets rapidement. Ce README explique comment accéder au répertoire, travailler avec le code, et comment créer une copie du modèle pour un nouveau projet.

## Accès au Répertoire

### Cloner le Répertoire

Pour accéder au modèle de projet, suivez ces étapes :

1. Ouvrez votre terminal (invite de commande).
2. Naviguez vers le répertoire de travail souhaité où vous souhaitez cloner le modèle.
3. Utilisez la commande suivante pour cloner le répertoire :

```shell
git clone https://github.com/UPSJunior/ProjectStarterKit.git
```

### Accéder au Répertoire en Ligne

Vous pouvez également accéder au modèle de projet en ligne en [cliquant ici](https://github.com/UPSJunior/ProjectStarterKit).

## Travailler avec le Code

Une fois que vous avez cloné le modèle de projet ou accédé au répertoire en ligne, voici comment travailler avec le code.

### Pull (Récupérer les Dernières Modifications)

Avant de commencer à travailler sur le projet, assurez-vous de récupérer les dernières modifications depuis le modèle principal en utilisant la commande suivante :

```shell
git pull origin main
```

Cela vous mettra à jour avec les changements apportés au modèle de projet.

### Créer un Nouveau Projet

Lorsque vous êtes prêt à créer un nouveau projet basé sur ce modèle, suivez ces étapes :

1. Dupliquez le répertoire modèle dans un nouveau répertoire en utilisant la commande suivante (remplacez `nom-du-nouveau-projet` par le nom de votre nouveau projet) :

```shell
cp -r ProjectStarterKit ref_YYMMDD_NomProjet
```

2. Naviguez dans le nouveau répertoire :

```shell
cd ref_YYMMDD_NomProjet
```

3. Initialisez un nouveau référentiel Git pour votre projet :

```shell
git init
```

4. Vous pouvez maintenant travailler sur votre projet en effectuant des modifications dans ce répertoire nouvellement créé.

### Push (Envoyer les Modifications)

Lorsque vous souhaitez enregistrer vos modifications et les envoyer au référentiel distant, suivez ces étapes :

1. Ajoutez les fichiers modifiés au suivi de Git en utilisant la commande suivante :

```shell
git add *
```

2. Créez un commit avec un message descriptif :

```shell
git commit -m "Description de vos modifications"
```

3. Poussez les modifications vers le référentiel distant (remplacez `origin main` par la branche souhaitée) :

```shell
git push origin main
```

## Contribution

Si vous souhaitez contribuer à l'amélioration de ce modèle de projet, n'hésitez pas à soumettre des pull requests. Vos contributions sont les bienvenues !

---
