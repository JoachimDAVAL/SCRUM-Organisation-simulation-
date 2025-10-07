# SCRUM-Organisation-simulation-

Simulation d'une organisation SCRUM autour d'un projet DataOps

Dans un soucis de suivi de performances scolaires, l'école _Lorem Ipsum_ désire un tableau de bord analytique automatisée afin de mieux comprendre et interpréter le taux de réussite. L'objectif de notre équipe sera de concevoir un pipeline automatisé qui récupèrera et traitera les données pour une meilleure lisibilité.

# 👥 Composition de l'équipe

| Rôle           | Responsabilité principale |
| -------------- | ------------------------- |
| Scrum Master   | Joachim DAVAL             |
| Data Analyst   | Ludovic Dumet             |
| Data Analyst   | Quentin Nicolas           |
| Data Engineer  | Ilham BENYOUSSEF          |
| Data Scientist | Aichatou BAMBA            |
#  Étapes du TP
##  Étape 1 — Lecture du Backlog
| ID  | User Story                                                                                                  | Priorité |
| --- | ----------------------------------------------------------------------------------------------------------- | -------- |
| US1 | En tant que Data Engineer, je veux automatiser le téléchargement Kaggle pour standardiser la collecte.      | Haute    |
| US2 | En tant que Data Analyst, je veux transformer et structurer les données pour les rendre plus compréhensible | Moyenne  |
| US3 | En tant que Data Analyst, je veux enrichir les données avec des moyennes afin d'obtenir un comparatif       | Moyenne  |
| US4 | En tant que Data scientist, je veux pouvoir corriger les potentielles erreurs                               | Faible   |
| US5 | En tant que Responsable, je veux suivre les performances à l'aide d'un tableau de bord                      | Faible   |
 
##  Étape 2 — Détail des tâches
| ID  | Tâches                               | Description                                                                                                          |
| --- | ------------------------------------ | -------------------------------------------------------------------------------------------------------------------- |
| US1 | Authentification Kaggle              | Permet la récuperation et le parametrage de la clé api                                                               |
| US1 | Script d'automatisation récupération | Création de script pour la récupération des données                                                                  |
| US2 | Script d'automatisation traitement   | Création d'un script pour le traitement des données brutes                                                           |
| US2 | Test de conformité des données       | Création d'un script pour tester la conformité structurelle des données et d'alerter le responsable en cas d'erreur. |
| US3 | Script d'enrichissement des données  | Création d'un script pour enrichir les données déjà traitées                                                         |
| US4 | Intervention sur données erronées    | Etude d'un moyen d'intervenir sur les données erronées avant reporting                                               |
| US5 | Contact des métiers                  | Garde contact avec les métiers pour éviter tout problèmes                                                            |
| US5 | Préparation de l'environnement       | Création du dossier de travail et installation des dépendances                                                       |
| US5 | Mise en place du tableau de bord     | Choix  et configuration de l'outils de visualisation et création du tableau de bord                                  |
##  Étape 3 — Estimation (Story Points)
  
| ID  | Points | Signification |
| --- | ------ | ------------- |
| US1 | 2      | Simple        |
| US1 | 5      | Dur           |
| US2 | 5      | Dur           |
| US2 | 2      | Simple        |
| US3 | 5      | Dur           |
| US4 | 3      | Moyenne       |
| US5 | 1      | Très simple   |
| US5 | 1      | Très simple   |
| US5 | 5      | Dur           |
### Exemple de Sprint Backlog
| Tâche                                | Responsable    | Estimation | Livrable attendu    |
| ------------------------------------ | -------------- | ---------- | ------------------- |
| Authentification Kaggle              | Data Engineer  | 2 pts      | CSV brut téléchargé |
| Script d'automatisation récupération | Data Engineer  | 5 pts      | Script              |
| Script d'automatisation traitement   | Data Analyst   | 5 pts      | Script              |
| Script d'enrichissement des données  | Data Analyst   | 5 pts      | Script              |
| Contact des métiers                  | Responsable    | 1 pts      | Mail                |
| Préparation de l'environnement       | Responsable    | 1 pts      | Fichier             |
## Étape 5 — Événements Scrum à simuler

| Événement           | Objectif                            | Durée indicative |
| ------------------- | ----------------------------------- | ---------------- |
| **Sprint Planning** | Définir les priorités et les tâches | 1h               |
| **Daily Scrum**     | Faire un plan pour la journée       | 0.25h            |
| **Sprint Review**   | Présentation du travail fini        | 2h               |
#  Fin du TP

Vous aurez simulé **un sprint complet Scrum** appliqué à un **projet DataOps réel**.

