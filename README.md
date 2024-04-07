## Name
temgoua_thierry_gravelaine_tic-tac-toe

## Description
Ce projet permet de mettre une CI/CD sur Jenkins via un projet react hébergé sur gitlab


## installation du projet

Pour démarrer, cloner le projet
installer les dépendances du projet react
> npm i
> npm run bluid
> npm start


## Workflow GitFlow gitlab :

Le workflow GitFlow utilisé définit une structure de branches spécifique, comprenant deux branches : La branche principale qui est la main ainsi qu'une branche secondaire de développement pour effectuer des travaux ainsi que gérer les versions de l'application. Une fois que cette branche de développement a un travail pret à etre livré, on va créer à chaque fois une Merge Request pour valider les travaux et envoyer le resultat final sur la main pour le déploiement.

Avantages :
Offre une structure claire et définie pour le développement logiciel, adaptée aux projets avec des versions multiples et des cycles de développement complexes.
Permet un développement parallèle des fonctionnalités tout en maintenant une branche de développement stable.

## Test and Deploy

Use the built-in continuous integration in GitLab.

- [ ] [Get started with GitLab CI/CD](https://docs.gitlab.com/ee/ci/quick_start/index.html)
- [ ] [Analyze your code for known vulnerabilities with Static Application Security Testing (SAST)](https://docs.gitlab.com/ee/user/application_security/sast/)
- [ ] [Deploy to Kubernetes, Amazon EC2, or Amazon ECS using Auto Deploy](https://docs.gitlab.com/ee/topics/autodevops/requirements.html)
- [ ] [Use pull-based deployments for improved Kubernetes management](https://docs.gitlab.com/ee/user/clusters/agent/)
- [ ] [Set up protected environments](https://docs.gitlab.com/ee/ci/environments/protected_environments.html)

***
