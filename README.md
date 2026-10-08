# Men in Mind

Jeu de facilitation bilingue (français / anglais) autour du bien-être mental des hommes. Interface en HTML, CSS et JavaScript, sans compte ni score.

## Données des participants

Le nom ou pseudonyme et les choix obligatoires à chaque situation (A, B ou C) sont enregistrés dans Appwrite afin de pouvoir consulter les réponses par participant. Le numéro de téléphone est facultatif et n’est envoyé que si la personne donne son accord pour être recontactée après l’activité. L’accès aux réponses reste réservé au propriétaire du projet Appwrite; le jeu envoie les données à une fonction dédiée.

## Lancer le jeu

Ouvrir `index.html` dans un navigateur. La langue suit automatiquement la préférence du navigateur (français ou anglais) et peut être changée avec le sélecteur.

## Déployer sur Vercel

Importer le dépôt GitHub `allurebami/Men-in-Mind` dans Vercel. Le projet est un site statique : sélectionner **Other** comme framework et conserver la racine du dépôt comme répertoire du projet. Aucun build command ni output directory n’est nécessaire.
