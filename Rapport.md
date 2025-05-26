# 📘 Rapport de Clôture — Hiver 2025

**Cours :** 420-0SH-SW – Gestion de Projets Informatiques  
**Nom :** [Derek Aldair Lopez Oria]  
**Date de remise :** [2025-05-21]

---

## 🕒 Section 1 – Journal de Temps

| Début       | Fin         | Commentaire / Explication                                                                 |
|-------------|-------------|-------------------------------------------------------------------------------------------|
| 2025-03-12  | 2025-03-19  | Prototype : Base de données (création initiale)                                           |
| 2025-03-12  | 2025-03-19  | Prototype canvas 3D – Recherche initiale (Livrable 1)                                     |
| 2025-03-12  | 2025-03-19  | Page panier : Affichage, total, paiement, validation, gestion des quantités              |
| 2025-03-26  | 2025-04-02  | Optimisation de la base de données (Livrable 2)                                          |
| 2025-03-26  | 2025-04-02  | Recherche concurrente – Livrable 2                                                       |
| 2025-04-09  | 2025-04-16  | Prototype canvas 3D – Optimisation + intégration Thread.js (Livrable 3)                  |
| 2025-04-09  | 2025-04-16  | Affichage d’une galerie de vêtements – Intégration responsive                            |
| 2025-04-09  | 2025-04-16  | Recherche des innovations et optimisations (Livrable 3)                                  |
| 2025-04-23  | 2025-04-30  | Amélioration du prototype canvas 3D – Fluidité, rendu (Livrable 4)                       |
| 2025-04-23  | 2025-04-30  | Connexion du canvas 3D avec fonctionnalités interactives (click, drag, etc.)             |
| 2025-04-23  | 2025-05-07  | Design de vêtements en 3D – Modèles personnalisables                                     |

---

### 2.1 Développement

#### a. Tâches planifiées vs réalisées

| Tâche                                                                 | Personne prévue      | Statut final / Personne réelle           |
|-----------------------------------------------------------------------|----------------------|------------------------------------------|
| Prototype : Base de données                                           | Derek                | Complété                                 |
| Backend (setup et connexion à la BD)                                  | Taha, Badr           | Complété                                 |
| Prototype canvas 3D – Recherche et intégration                        | Derek, Taha, Badr    | Complété                                 |
| Page panier : Affichage, total, paiement, validation                  | Derek                | Complété                                 |
| Menu du site et pages (accueil, bas de page, personnalisation)       | Badr                 | Complété                                 |
| Page de connexion (front-end + back-end)                              | Badr, Taha           | Complété                                 |
| Système de gestion des stocks en temps réel                           | Taha                 | Complété                                 |
| Recherche concurrente pour options uniques                            | Tous                 | Complété                                 |
| Intégration musique dans la rulette                                   | Taha                 | Complété                                 |
| Déploiement (hébergement du site)                                     | Taha                 | Complété                                 |
| Création d’une galerie dynamique de vêtements                         | Derek                | Complété                                 |
| Ajout de filtres avancés (taille, couleur, prix)                      | Derek                 | Non complété                             |
| Système de paiement sécurisé externe (Stripe, PayPal...)              | Taha                 | Non complété                             |
| Facturation automatique PDF                                           | Badr                 | Non complété                             |
| Tableau de bord administrateur                                        | Derek                | Non complété                             |
| Tests unitaires sur le backend                                        | Taha                 | Non complété                             |
| Intégration d’un système de messagerie client                         | Derek                 | Non complété                             |


#### b. Difficultés et modifications

- Difficulté 1 : Mon principal problème était de savoir comment créer le prototype 3D, comment l'ajouter au projet (site web), comment le faire fonctionner. Ce problème nous a généré beaucoup de problèmes et de maux de tête, à la fin, je peux dire que finalement, j'ai réussi à trouver une bonne façon de le faire, j'ai utilisé thread.js, j'ai implémenté un modèle 3d déjà fait en .gltf, puis j'ai utilisé plusieurs outils que thread offre, et avec cela, j'ai pu commencer à travailler sur la modélisation 3d.
- Difficulté 2 : Grâce à l'IA, j'ai pu créer une galerie de mes propres produits de la marque « URBAN PULSE », car au début, nous pensions développer nos propres produits, nous pensions utiliser Renderer ou AutoCad pour pouvoir faire nos propres dessins, mais c'était très compliqué et cela prenait beaucoup de temps.
- Difficulté 3 : Pour les filtres et les changements de la personnalisation 3D, j'ai eu des problèmes pour rendre réaliste la modification du texte et du logo, c'est à dire pouvoir le déplacer en x,y,z, et pouvoir le « coller » au produit, ce que j'ai fait a été d'implémenter l'option de déplacer le texte et le logo dans toutes les directions, donc j'ai résolu le problème.

Modifications par ordre d'importance :
- Il y a eu beaucoup de changements dans le développement de la personnalisation 3D, au début nous avons pensé à utiliser Renderer.js, ensuite nous avons pensé à engager quelqu'un pour faire les modèles pour nous et nous nous sommes concentrés sur l'intégration dans le site web, finalement, j'ai trouvé l'outil génial "Thread.js" qui a rendu la vie plus facile pour nous tous.
- Il y a également eu un changement important dans le design de notre site, au début nous avons développé un style classique, plus compact, plus "actuel", puis nous avons changé pour un style plus futuriste, il a été difficile de développer ce dernier, parce qu'il y avait beaucoup d'animations que nous ne pouvions pas mettre en œuvre finalement.

#### c. Utilisation des outils

- **Outils utilisés :** ChatGPT, StackOverflow, Youtube.
- **Utilité :** ChatGPT nous a littéralement aidés à résoudre un grand nombre de nos problèmes, ainsi qu'à les reconnaître. Parfois, nous avions des problèmes dans le code que nous ne savions pas comment interpréter, sans parler de le comprendre, et ChatGPT nous a donc principalement aidés dans ce domaine, ainsi que dans l'utilisation de certains outils.
Avec StackOverflow, nous avons cherché des idées et des moyens de corriger certains bogues dans notre code.
Youtube m'a beaucoup aidé à réaliser la personnalisation 3D, ainsi qu'à apprendre de nouveaux sujets théoriques et pratiques pour pouvoir les utiliser et les comprendre.

- **Améliorations :** [Comment les utiliser plus efficacement à l’avenir]

---

### 2.2 Auto-Évaluation

| Critère                                                                                       | Note (0–4) | Justification détaillée             |
|-----------------------------------------------------------------------------------------------|------------|-------------------------------------|
| Respect de la charge de travail assignée                                                      |      4      |  Enfin, dans chaque tâche qui m'a été confiée, j'ai consacré le temps et la concentration nécessaires, je considère donc que ma participation et mon travail ont été essentiels, indispensables au bon déroulement de ce projet.                                   |
| Participation aux rencontres                                                                  |      3      |  Nous n'avons eu ni trop ni trop peu de réunions, mais elles étaient adéquates et nécessaires, afin d'avancer progressivement dans chacun des projets suivis.                                   |
| Respect des critères et normes de qualité                                                     |      3      |  Je considère que j'ai respecté les critères mais pas dans leur intégralité, donc je ne considère pas que cet aspect mérite un 4, car j'aurais pu mieux suivre les critères.                                   |
| Participation aux discussions et à la résolution de problèmes                                 |      3      |  Il m'est arrivé de devoir résoudre seul certains problèmes de groupe, mais à part cela, la communication a été très bonne, surtout avec mon partenaire Taha, nous nous sommes très bien entendus et nous avons réussi à avancer en tant qu'équipe.                                   |
| Satisfaction du travail personnel                                                             |      2      |   Je sens que je ne suis pas très fort en informatique, je fais beaucoup d'efforts mais parfois je sature et je n'arrive pas à me dépasser, je sens que j'aurais pu faire un travail deux fois meilleur, peut-être avec un peu plus de temps et d'autonomie.                                  |

---

### 2.3 Évaluation des Pairs

#### Coéquipier : [Taha Othmane]

| Critère                                                                                       | Note (0–4) | Justification             |
|-----------------------------------------------------------------------------------------------|------------|---------------------------|
| Respect de la charge de travail assignée                                                      |    4       |   Taha était toujours au courant de tout ce que nous avions à faire, de chaque tâche, de presque tous les problèmes qui se présentaient, nous nous soutenions mutuellement, il était un élément clé du projet.                        |
| Participation aux rencontres                                                                  |    3       |   Parfois, il n'a pas pu être présent, mais en raison de son mode de vie, de son travail, de sa famille et de ses cours, il a été en mesure de faire des progrès lors de chaque réunion.                       |
| Respect des critères et normes de qualité                                                     |    4       |   Il a respecté tous les points et tous les critères du projet, même plus que moi, je n'ai rien à signaler.                        |
| Participation aux discussions et à la résolution de problèmes                                 |    3       |   Lors de chaque réunion, il parlait toujours et aidait beaucoup à résoudre les problèmes, il avait beaucoup d'idées créatives.                        |
| Contribution globale au projet                                                                |    4       |    Sa contribution au travail a été vraiment importante, une partie essentielle du travail, il a vraiment apporté beaucoup d'idées, beaucoup de développement au projet.                       |

#### Coéquipier : [Badr Mellouki]

| Critère                                                                                       | Note (0–4) | Justification             |
|-----------------------------------------------------------------------------------------------|------------|---------------------------|
| Respect de la charge de travail assignée                                                      |    2       |  Il a fait une partie du travail, mais pas suffisamment pour apporter une contribution majeure.                         |
| Participation aux rencontres                                                                  |    3       |  Il était présent à certaines réunions, mais pas à toutes, il participait à certaines tâches, mais en oubliait d'autres.                         |
| Respect des critères et normes de qualité                                                     |    3       |  Je ne sais pas quoi répondre ici, je pense qu'il a respecté les règles dans ce qu'il a fait.                         |
| Participation aux discussions et à la résolution de problèmes                                 |    2       |  Sa participation a été suffisante, mais il n'a pas été efficace.                         |
| Contribution globale au projet                                                                |    3       |  Il a contribué un peu, mais pas assez pour mériter un 3 ou un 4                        |


## ✅ Section 4 – Conclusion

### a. Écarts entre le projet prévu et le projet final

- **Écart 1 : Intégration du système de paiement externe non réalisée**  
  Bien que planifiée dès le départ (ex. : Stripe), cette fonctionnalité n’a pas pu être mise en place faute de temps et de complexité technique supplémentaire liée à la sécurité.

- **Écart 2 : Absence de filtres avancés dans la galerie de vêtements**  
  Les filtres par taille, couleur et prix étaient prévus pour améliorer l’expérience utilisateur, mais cette partie a été laissée de côté afin de prioriser la personnalisation 3D et les fonctionnalités de base.

- **Écart 3 : Tableau de bord administrateur non développé**  
  Le système de gestion interne des utilisateurs, commandes et produits était envisagé, mais n’a pas été entamé par manque de temps.

- **Écart 4 : Manque de tests unitaires et d’automatisation**  
  Le projet ne contient pas de suite de tests, bien que cela ait été prévu dans les bonnes pratiques de développement. L’équipe a choisi de tester manuellement les fonctionnalités clés pour gagner du temps.


### b. Résumé personnel

#### i. Ce que je changerais si c’était à refaire :

- Personnellement, le principal aspect que j'aurais changé serait le processus que nous avons utilisé pour trouver et développer la personnalisation 3D, nous avons pris trop de temps et peut-être que si nous l'avions fait avec plus de temps, nous aurions pu développer beaucoup plus de choses et perfectionner l'expérience, je pense vraiment que si nous avions trouvé un moyen plus rapide et plus facile de « trouver ce qu'il fallait utiliser pour la personnalisation 3D », la qualité du projet aurait été 20 fois meilleure.

 Peut-être que cela aurait aussi changé la répartition des tâches, nous avons mieux progressé lorsque nous nous sommes concentrés sur une seule chose, moi et Taha, passer d'une tâche à l'autre ensemble nous a aidés à terminer le site web.

#### ii. Auto-évaluation de ma performance

- **Note sur 5 :** [4/5]  
- **Justification :**
- Planification des tâches : j'ai eu beaucoup d'idées et j'ai contribué de différentes manières à la planification des tâches, je me suis toujours appuyé sur une méthode progressive évitant la stagnation, malheureusement je ne me donne pas une note parfaite parce qu'il y a eu des problèmes avec un aspect du projet, la personnalisation 3D, la planification de la recherche et du développement de cet aspect était très mauvaise au début.

-Exécution des tâches : J'ai accompli absolument toutes mes tâches, l'une après l'autre, en réévaluant toujours si cela fonctionnait correctement, sans bogues, sans problèmes de tiers, je les ai accomplies honnêtement par la recherche et le développement, je leur ai consacré le temps prévu et peut-être un peu plus que ce qui était indiqué, mais pour le bien du projet. 

-Ma contribution : Ma participation a été essentielle pour ce projet, je peux dire que j'ai fait une partie très importante du travail, surtout la plus compliquée et la plus intéressante "personnalisation 3D", ensuite avec le développement des méthodes de connexion, la base de données, les validations, le développement js, php, j'ai mis beaucoup de mes mains et de mes connaissances, J'ai mis beaucoup de mes mains et de mes connaissances, ainsi qu'en même temps j'ai beaucoup appris pour pouvoir atteindre l'objectif, dès le début je me suis senti dans la capacité d'exercer les tâches les plus compliquées malgré le peu de temps libre que j'avais, finalement bien que ce ne fut pas un succès retentissant, ce fut un objectif accompli dont je peux dire que 50% l'a été grâce au temps que j'y ai consacré.

#### iii. Appréciation de l’expérience

- J'ai vraiment aimé l'expérience, il me semble que ce que nous avons appris dans ce cours fera partie de notre vie quotidienne à l'avenir en tant qu'informaticiens, les réunions constantes, la contribution continue, la résolution de problèmes, la communication efficace sont des choses que nous devrons vraiment maîtriser sur le lieu de travail, et ce cours, ce projet, m'a beaucoup aidé à comprendre cela et à apprendre à ce sujet.
---

  

