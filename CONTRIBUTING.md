# Règles de contribution

## 1. Ne pas développer directement sur `main`

Chaque fonctionnalité, correction ou modification documentaire importante doit être réalisée dans une branche dédiée.

Exemples :

```text
feature/authentication
feature/gestion-clients
fix/erreur-connexion
docs/architecture
```

## 2. Créer une Issue avant une tâche importante

Avant de commencer une fonctionnalité ou une correction significative :

1. créer une Issue ;
2. décrire le besoin ou le problème ;
3. affecter un membre du groupe ;
4. ajouter l'Issue au Kanban ;
5. déplacer l'Issue au fur et à mesure de son avancement.

## 3. Commits

Les commits doivent être petits, cohérents et explicites.

Exemples :

```text
feat: ajout authentification utilisateur
fix: correction validation formulaire
docs: ajout diagramme architecture
test: ajout tests service utilisateur
refactor: simplification service commande
```

À éviter :

```text
modif
test
ça marche
update
final
```

## 4. Pull Requests

Une branche terminée doit faire l'objet d'une Pull Request vers `main`.

La Pull Request doit préciser :

- ce qui a été réalisé ;
- l'Issue concernée ;
- comment tester la modification.

Un autre membre du groupe doit relire la Pull Request avant fusion.

## 5. Branche principale

La branche `main` doit toujours contenir une version fonctionnelle du projet.

## 6. Responsabilité individuelle

Chaque étudiant doit pouvoir montrer sa contribution personnelle à travers :

- les Issues qui lui sont affectées ;
- ses branches ;
- ses commits ;
- ses Pull Requests ;
- les revues de code qu'il a effectuées.
