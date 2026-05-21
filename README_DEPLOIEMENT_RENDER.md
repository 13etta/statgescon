# Étude statistique Gescon — site statique Render

Ce dossier contient un site statique prêt à déposer sur GitHub puis à connecter à Render.

## Contenu

- `index.html` : tableau de bord interactif complet.
- `statistiques_par_chien.csv`
- `statistiques_par_affixe.csv`
- `statistiques_par_discipline.csv`
- `statistiques_chien_discipline.csv`
- `evolution_annuelle.csv`
- `repartition_qualificatifs.csv`
- `statistiques_par_categorie.csv`
- `render.yaml` : configuration Render optionnelle si déploiement par Blueprint.

## Déploiement manuel recommandé sur Render

1. Créer un dépôt GitHub, par exemple `etude-gescon-setter`.
2. Envoyer tous les fichiers de ce dossier à la racine du dépôt.
3. Dans Render : New > Static Site.
4. Connecter le dépôt GitHub.
5. Paramètres :
   - Name : `etude-gescon-setter-anglais`
   - Branch : `main`
   - Build Command : laisser vide, ou mettre `true`
   - Publish Directory : `.`
6. Cliquer sur Create Static Site.
7. Partager l'URL `https://...onrender.com`.

## Point de vigilance

Le site ne contient pas d'accès privé. Toute personne qui possède le lien peut consulter la page si le service reste public.
