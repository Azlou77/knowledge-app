# knowledge-app

## Cahier des charges "Mes Connaissances"
**Objectif:**
Créer une application web simple pour recenser ses connaissances personnelles, les classer par catégorie et leur attribuer un niveau d’évaluation.

### Stack technique imposée:
**Frontend**
- React
- Tailwind CSS
- TypeScript (recommandé mais non obligatoire)

**Backend:**
- PHP natif (sans utilisation de Framework)
- Base de données: MySQL, MariaDB ou PostgreSQL

### Fonctionnalités – Connaissances:
L'application permet aux utilisateurs de gérer leurs connaissances avec les fonctionnalités suivantes :
- Ajouter une nouvelle connaissance
- Modifier ou supprimer une connaissance existante
- Afficher la liste complète des connaissances

Chaque élément de connaissance contient :
- Nom (exemple : React, Git, PostgreSQL) – Obligatoire
- Description – Optionnelle
- Niveau (Débutant, Intermédiaire, Avancé, Expert) – Obligatoire
- Date d’acquisition ou d’apprentissage – Optionnelle
- Catégorie – Obligatoire, définie selon des critères précis

### Catégories
Chaque connaissance appartient à une catégorie.
Exemples : Frontend, Backend, DevOps, Bases de données, Outils.

L'utilisateur peut :
- Créer une nouvelle catégorie.
- Supprimer ou renommer une catégorie.
- Filtrer les connaissances par catégorie.

### Interface:
- Interface responsive et épurée.
- Formulaires simples pour ajouter/modifier une connaissance ou une catégorie.
- Possibilité de filtrer les connaissances par catégorie.

### Critères d'évaluation:
- Simplicité d’utilisation.
- Code clair et bien structuré.
- Organisation et maintenabilité du projet.
- README complet et à jour.

### Livrables attendus pour le projet GitHub:
- L'application doit inclure les éléments suivants dans le dépôt GitHub :
- README détaillé avec instructions de lancement (frontend + backend).
- Base de données préremplie avec les connaissances et évaluations.
- Capture(s) d’écran de l’interface utilisateur (optionnel).
- Documentation technique (optionnel).
- Documentation utilisateur (optionnel).
