# PsyH — Facturation confidentielle

Application de facturation statique, à héberger sur GitHub Pages.

## Confidentialité

L’application est exclue de l’indexation par les moteurs de recherche :

- `robots.txt` demande aux robots de ne pas explorer le site.
- `index.html` contient `noindex, nofollow, noarchive, nosnippet, noimageindex`.
- `.nojekyll` évite le traitement Jekyll de GitHub Pages.

Pour une confidentialité maximale : gardez le dépôt GitHub **privé**, ne partagez pas l’URL, et utilisez une adresse difficile à deviner.

## Fichiers à téléverser

À la racine du dépôt GitHub :

- `index.html`
- `robots.txt`
- `.nojekyll`

## Mise en ligne sur GitHub

1. Connectez-vous à GitHub.
2. Cliquez sur **New repository**.
3. Nom : `psyh-factures`.
4. Sélectionnez **Private**.
5. Cliquez sur **Create repository**.
6. Sur la page du dépôt, cliquez sur **uploading an existing file**.
7. Glissez-déposez `index.html`, `robots.txt` et `.nojekyll`.
8. Cliquez sur **Commit changes**.
9. Allez dans **Settings** → **Pages**.
10. Dans **Build and deployment** :
    - Source : `Deploy from a branch`
    - Branch : `main`
    - Folder : `/ (root)`
11. Cliquez sur **Save**.
12. Attendez quelques minutes ; GitHub affiche l’URL publique de l’application.

Exemple d’URL :

`https://votre-nom-utilisateur.github.io/psyh-factures/`

## Utilisation

- Mot de passe initial : `PsyH2026`
- Modifiable dans **Paramètres**
- Ajout du logo et de la signature dans **Paramètres**
- Enregistrement des factures par référence
- Réouverture, duplication ou suppression des factures
- Export et import de toutes vos données au format JSON
- Génération du PDF
- Envoi via Gmail avec message prérempli ; ajoutez le PDF en pièce jointe avant l’envoi.

## Sauvegarde recommandée

Utilisez régulièrement **Exporter mes données**. Le fichier JSON contient vos factures, votre email, votre mot de passe, votre logo et votre signature encodés localement.

Conservez-le dans un coffre-fort numérique ou un disque chiffré.
