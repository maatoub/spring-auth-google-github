# Spring Boot Authentication with Google and GitHub

## Description
Cette application permet aux utilisateurs de s’authentifier en utilisant leurs comptes Google et GitHub. Elle est construite avec Spring Boot et utilise OAuth2 pour gérer les processus d’authentification.
## Prérequis
  - Java 17 ou supérieur
  - Maven
  - Un compte Google et un compte GitHub
## Configuration
### Google
1. Accédez à la Console des développeurs Google.
2. Créez un nouveau projet ou sélectionnez un projet existant.
3. Accédez à APIs & Services > Credentials.
4. Cliquez sur Create Credentials et sélectionnez OAuth 2.0 Client IDs.
5. Configurez l’écran de consentement OAuth si ce n’est pas déjà fait.
6. Remplissez les informations nécessaires et ajoutez http://localhost:8080/login/oauth2/code/google comme URI de redirection.
7. Enregistrez les Client ID et Client Secret.

### Github
1. Accédez à GitHub Developer Settings.
2. Cliquez sur New OAuth App.
3. Remplissez les informations nécessaires et ajoutez http://localhost:8080/login/oauth2/code/github comme URI de redirection.
4. Enregistrez les Client ID et Client Secret.

## Lancer l’applicationù

##### http://localhost:8080
