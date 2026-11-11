# TP-Digital-Engineering-ALAOUI-HAMMAM


## Présentation
HAMMAM ALAOUI 

## Dépôts réalisés
- Exercice 1 : [calcul-c](https://github.com/alaoui-hammam/calcul-C)
- Exercice 2 (binôme) : [calcul-c-equipe](https://github.com/alaoui-hammam/calcul-C-equipe)
  - Mon rôle : alaoui-hammam : A
  - Binôme : alaoui-homam : B

## Pull request fusionnée
[https://github.com/<...>/pull/<n>](https://github.com/alaoui-hammam/calcul-C-equipe/pull/1)

## Bilan des commandes Git

### `git status`
**Rôle :** affiche l'état du dépôt : la branche courante, les fichiers modifiés, les fichiers ajoutés à l'index (staging) et ceux qui ne sont pas encore suivis. Il permet de vérifier que tout est commité avant de pousser.

```text
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
```

### `git remote -v`
**Rôle :** liste les dépôts distants (remotes) liés au dépôt local, avec leurs URL en fetch (récupération) et en push (envoi). Il permet de vérifier que le dépôt pointe bien vers le bon GitHub.

```text
origin  https://github.com/<user>/calcul-C-equipe.git (fetch)
origin  https://github.com/<user>/calcul-C-equipe.git (push)
```

### `git log --oneline --graph --all`
**Rôle :** affiche l'historique des commits sur une seule ligne chacun, avec un graphe ASCII des branches (`--graph`) et toutes les branches, locales et distantes (`--all`). Il permet de voir les branches, les merges et la pull request fusionnée.

```text
*   a1b2c3d (HEAD -> main, origin/main) Merge pull request #1 from binome/feature-calcul
|\
| * e4f5g6h (origin/feature-calcul) Ajout de la fonction multiplication
| * 9i8j7k6 Ajout de la fonction addition
|/
* 1a2b3c4 Initial commit
```
