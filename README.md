# MAM PARTAGE

## Naissance du Git

Suite à l'**égoïsme** et l'**hypocrisie** de certains étudiants de notre chère filière, ce git s'est imposé comme une alternative sécurisée à notre célèbre drive ([MAM Partage](https://drive.google.com/drive/folders/14sXfUbgN3qCsjIV7yLSrbB1hRzD_Pqit)), qui avait pourtant été utile à beaucoup d'entre nous, mais dont l'existence était menacée par ceux qui se croyaient au-dessus des règles et se permettaient de supprimer les fichiers partagés.

## Un couteau à double tranchant

Ce git a donc pour but de partager les cours, TD, TP, comptes rendus et examens de chaque année. Il faut donc savoir l'utiliser à **bon escient**.
Certes, on cherche tous à avoir notre diplôme, mais copier bêtement les comptes rendus dans l'espoir d'avoir une bonne note n'aura d'effet qu'à court terme — et pourra même te desservir sur le long terme...

## Comment utiliser


### 1. Cloner le dépôt sur ta machine

Tu peux aussi récupérer tout le contenu en local pour travailler hors ligne ou contribuer plus facilement :

```bash
git clone https://github.com/moh8dhia/MAM-PARTAGE.git
```

Cela créera un dossier `MAM-PARTAGE/` contenant tous les fichiers.

### 2. Ajouter des fichiers au dépôt (push)

**Étapes :**

#### 1. Faire un fork du dépôt

Si tu n'as pas accès en écriture sur le dépôt principal, tu devras d'abord créer une copie personnelle du dépôt, qu'on appelle un **fork**.

Pour cela :

- Rends-toi sur la page du dépôt : [https://github.com/moh8dhia/MAM-PARTAGE](https://github.com/moh8dhia/MAM-PARTAGE)
- En haut à droite, clique sur le bouton **Fork**
- GitHub va créer automatiquement une copie du dépôt dans ton propre compte GitHub.

#### 2. Cloner ton fork

Une fois le fork créé, copie l’URL de **ton propre dépôt**, puis fais :

```bash
git clone https://github.com/ton-pseudo/MAM-PARTAGE.git
```

3. Ajoute ou modifie un fichier dans le bon dossier

4. Nomme correctement ton fichier selon les règles suivantes :

- **Cours (CM)** : `chapX_anneescolaire.extension`  
  *Exemple* : `chap3_2023-2024.pdf`

- **TD** : `tdX_anneescolaire.extension`  
  *Exemple* : `td2_2023-2024.pdf`

- **TP** : `tpX_anneescolaire_noteobtenue.extension`  
  *Exemple* : `tp1_2023-2024_18-5.pdf`

- **Examens (CC, partiels...)** : `ccX_anneescolaire.extension`  
  *Exemple* : `cc1_2022-2023.pdf`

5. Pousse tes modifications :

```bash
git add .
git commit -m "Ajout de td3 en probabilités - 2023-2024"
git push
```

6. Ouvre une pull request depuis GitHub pour proposer l’ajout au dépôt principal.  
Les modifications seront examinées avant d’être intégrées.


**Bonne utilisation ;)**
