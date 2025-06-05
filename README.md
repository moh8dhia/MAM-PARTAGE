# MAM PARTAGE

## Naissance du Git

Suite à l'**égoïsme** et l'**hypocrisie** de certains étudiants de notre chère filière, ce git s'est imposé comme une alternative sécurisée à notre célèbre drive ([MAM Partage](https://drive.google.com/drive/folders/14sXfUbgN3qCsjIV7yLSrbB1hRzD_Pqit)), qui avait pourtant été utile à beaucoup d'entre nous, mais dont l'existance était menacée par ceux qui se croyaient au dessus des règles et se permettaient de supprimer les fichiers partagés.

## Un couteau à double tranchant

Ce git a donc pour but de partager les cours, TD, TP, comptes rendus et examens de chaque année. Il faut donc savoir l'utiliser à **bonne escient**.
Certes, on cherche tous à avoir notre diplôme, mais copier bêtement les comptes rendus dans l'espoir d'avoir une bonne note n'aura d'effet qu'à court terme — et pourra même vous desservir sur le long terme...

## **Comment utiliser**

### 1. Consulter les fichiers via GitHub Pages

Le site GitHub Pages permet de parcourir rapidement les ressources sans cloner le dépôt.  
Rendez-vous simplement sur : [https://moh8dhia.github.io/MAM-PARTAGE/](https://moh8dhia.github.io/MAM-PARTAGE/)

Vous y trouverez l’arborescence des semestres (S5 à S10), les matières associées, et leurs sous-dossiers (`CM`, `TD`, `TP`, `Examens`).

---

### 2. Cloner le dépôt sur votre machine

Vous pouvez récupérer tout le contenu en local pour travailler hors-ligne ou contribuer plus facilement :

```bash
git clone https://github.com/moh8dhia/MAM-PARTAGE.git
```

Cela créera un dossier `MAM-PARTAGE/` contenant tous les fichiers.

### 3. Ajouter des fichiers au dépôt (push)

**Étapes :**

#### 1. Faire un fork du dépôt

Si vous n'avez pas accès en écriture sur le dépôt principal, vous devez d'abord créer une copie personnelle du dépôt, qu'on appelle un **fork**.

Pour cela :

- Rendez-vous sur la page du dépôt : [https://github.com/moh8dhia/MAM-PARTAGE](https://github.com/moh8dhia/MAM-PARTAGE)
- En haut à droite, cliquez sur le bouton **Fork**
- GitHub va créer automatiquement une copie du dépôt dans votre propre compte GitHub

#### 2. Cloner votre fork

Une fois le fork créé, copiez l’URL de **votre propre dépôt**, puis faites :

```bash
git clone https://github.com/votre-pseudo/MAM-PARTAGE.git
```

3. Ajoutez ou modifiez un fichier dans le bon dossier

4. Nommez correctement votre fichier selon les règles suivantes :

- **Cours (CM)** : `chapX_anneescolaire.extension`  
  *Exemple* : `chap3_2023-2024.pdf`

- **TD** : `tdX_anneescolaire.extension`  
  *Exemple* : `td2_2023-2024.pdf`

- **TP** : `tpX_anneescolaire_noteobtenue.extension`  
  *Exemple* : `tp1_2023-2024_18-5.pdf`

- **Examens (CC, partiels...)** : `ccX_anneescolaire.extension`  
  *Exemple* : `cc1_2022-2023.pdf`

5. Poussez vos modifications :

```bash
git add .
git commit -m "Ajout de td3 en probabilités - 2023-2024"
git push
```

6. Ouvrez une pull request depuis GitHub pour proposer l’ajout au dépôt principal.  
Les modifications seront examinées avant d’être intégrées.

