
On part du projet précedent (0_API_DevContainer) et on y rajoute :

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=devVvincent_API_CI&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=devVvincent_API_CI)

## Règles de protection GitHub

- Le push direct sur la branche `main` est interdit grâce à des règles de protection.
- Toute modification sur `main` doit passer par une Pull Request validée.
- Le workflow `Test & Format` doit obligatoirement passer avec succès avant de pouvoir fusionner une PR.

## Spécificités de ce projet

- Intégration CI/CD avec GitHub Actions :
   - Workflows pour le formatage, les tests et l’analyse SonarQube.
   - Utilisation d’une action composite locale pour l’installation de .NET et la restauration des dépendances.

---

## Auteur
devVvincent

## Licence
Ce projet est simplement un projet de démonstration.
