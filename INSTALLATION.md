# Installation du README de profil GitHub

## 1. Créer le dépôt de profil

Crée un dépôt public nommé exactement :

```text
melvin-phyllis
```

Le nom doit être identique à ton identifiant GitHub.

## 2. Ajouter les fichiers

Place ces fichiers dans le dépôt :

```text
README.md
.github/workflows/snake.yml
```

## 3. Envoyer les fichiers sur GitHub

```bash
git clone https://github.com/melvin-phyllis/melvin-phyllis.git
cd melvin-phyllis

# Copier README.md et le dossier .github dans ce dossier

git add .
git commit -m "feat: create animated GitHub profile"
git push origin main
```

## 4. Activer l’animation du serpent

1. Ouvre l’onglet **Actions** du dépôt.
2. Accepte l’activation de GitHub Actions si GitHub le demande.
3. Ouvre le workflow **Generate contribution snake**.
4. Clique sur **Run workflow**.
5. Attends la fin de l’exécution.
6. Recharge ton profil.

Le workflow crée une branche `output` contenant les deux animations SVG.

## 5. Personnalisation conseillée

Tu peux remplacer ou ajouter dans le README :

- les liens directs vers tes vrais dépôts ;
- ton profil LinkedIn, si tu en as un ;
- une photo ou un logo personnel ;
- les technologies réellement utilisées dans chaque projet.

## Remarque

Les cartes de statistiques sont chargées depuis des services externes. Elles peuvent parfois être temporairement indisponibles sans que ton README soit cassé.
