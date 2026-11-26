<!--
  MODÈLE DE README — Pipeline Data, séquence 1, chapitre 5
  Les blocs comme celui-ci sont des consignes : GitHub ne les affiche pas.
  Remplace chaque [crochet] par ton texte, puis supprime les crochets.
  Repères Markdown : une ligne qui commence par # est un titre ; une ligne qui commence par - est une puce.
-->

# Enseignement supérieur - évolution du choix d'une école de commerce

<!-- Une phrase qui dit ce que fait ton projet. Exemple : « Prévoir la production de 6 boulangeries selon la météo pour réduire les invendus. » -->
Prévoir les effectifs attendus dans les écoles de commerce post-bac

## 1. Le problème d

<!-- Reprends ta fiche projet : le contexte en 2 ou 3 phrases, la question centrale, l'utilisateur. -->
- **Contexte** : Le marché des écoles de commerce post-bac est confronté à une évolution des comportements des candidats, dans un contexte de concurrence accrue entre établissements et de multiplication des formations proposées sur Parcoursup.
La question est de savoir si un éventuel recul des candidatures traduit une désaffection générale pour ces formations ou s'il masque une polarisation du marché, avec des établissements qui continuent à attirer de nombreux candidats tandis que d'autres perdent progressivement en attractivité

- **Question centrale** : Comment analyser l'évolution des candidatures dans les écoles de commerce post-bac pour déterminer si le recul est global ou s'il traduit une polarisation croissante entre établissements attractifs et établissements en difficulté ?
- **Utilisateur** : Le décideur : un directeur du développement ou de la stratégie d'un groupe d'écoles de commerce, ou un responsable d'un organisme de conseil spécialisé dans l'enseignement supérieur.
Sa décision : il souhaite comprendre le positionnement concurrentiel des écoles afin de :
•	Identifier les établissements qui gagnent ou perdent en attractivité.
•	Repérer les écoles dont la situation se dégrade.
•	Adapter la stratégie de recrutement, de communication et de développement des établissements.


## 2. Les données

<!-- Une ligne par source envisagée, comme dans ta fiche projet. -->
| Source | Type | Ce qu'elle apporte |
| --- | --- | --- |
| Parcoursup – Ministère de l'Enseignement supérieur | Bases de données statistiques en Open Data, accessibles en consultation, téléchargement et via API | Données par formation et établissement : effectifs de candidats, capacités d'accueil, propositions d'admission et admissions. Source principale pour mesurer l'évolution de la demande et calculer les trois KPI. Parcoursup 2025 – données ouvertes | 
| Cartographie des formations Parcoursup – Ministère de l'Enseignement supérieur | Base de données en Open Data, accessible en téléchargement et via API | Permet d'identifier les établissements et les formations, leurs caractéristiques, leur localisation et leur statut. Sert à sélectionner les écoles de commerce post-bac et à constituer le panel étudié. Cartographie des formations Parcoursup |
| CEFDG – Commission d'évaluation des formations et diplômes de gestion | Référentiel institutionnel | Source complémentaire permettant de vérifier les formations et établissements de management évalués, ainsi que certaines reconnaissances officielles. Contribue à qualifier le panel d'établissements étudiés. 
Accueil - CEFDG - Commission d'évaluation des formations et diplômes de gestion

Lien indicatif ci-dessous pour d’autres informations
Bilans académiques Parcoursup 2025 |
| [Nom de la source et qui la publie] | [Type] | [Les données utiles au projet] |

## 3. L'organisation du dépôt

<!-- Laisse cette liste telle quelle : elle décrit les dossiers créés au chapitre 3. -->
- `data/raw/` : les données brutes, telles que reçues, jamais modifiées
- `data/processed/` : les données nettoyées, prêtes pour l'analyse
- `notebooks/` : les notebooks Jupyter d'exploration et d'analyse
- `scripts/` : les scripts Python du projet
- `sql/` : les requêtes SQL
- `api/` : l'API du projet
- `dashboard/` : le rapport Power BI et ses captures d'écran
- `docs/` : la fiche projet et les documents du projet

## 4. L'avancement

<!-- Les étapes de ton projet. La première est faite. Tu cocheras les suivantes une fois le module terminé, quand tu appliqueras chaque méthode à ton projet : remplace alors [ ] par [x]. -->
- [x] Sujet choisi, dossiers créés, dépôt publié
- [ ] Collecte des données
- [ ] Requêtes SQL
- [ ] Nettoyage et dataset final
- [ ] Stockage en base
- [ ] API
- [ ] Analyse et tableau de bord

---
[Ton prénom et ton nom] · Formation Data Analyst & IA · DataSuits
