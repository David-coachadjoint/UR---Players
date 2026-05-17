# CONTEXT — Union Rochefortoise Scout DB

## Glossaire

### Joueur
Un individu tracké dans l'application. Appartient à l'une des deux populations : **Noyau** ou **Cible**.

### Noyau
Les joueurs actuellement sous contrat ou engagés avec l'Union Rochefortoise. L'objectif est de les évaluer, comprendre leur profil, et former l'ADN de l'équipe.

### Cible
Un joueur extérieur au club, identifié pour un recrutement futur. Dispose d'une **fiche de contexte** (poste, club actuel, niveau estimé, contact) et d'**observations datées** permettant de suivre son évolution et de la comparer à d'autres Cibles sur le même Manquement.

### ADN d'équipe
La signature collective du Noyau — répartition des Profils de poste et niveau moyen par catégorie de Compétences (Technique, Physique, Mental). Révèle si l'équipe est naturellement axée sur la transition, la possession, le jeu direct, etc. Sert à adapter le plan de jeu et les entraînements pour mettre en valeur les forces collectives réelles de l'équipe.

### Style de jeu
L'orientation tactique qui émerge de l'ADN d'équipe (ex : transition rapide, possession, jeu direct). N'est pas choisi arbitrairement — il est lu dans les données du Noyau et sert de boussole pour les décisions d'entraînement et de recrutement.

### Profil
L'ensemble des postes qu'un Joueur peut occuper (ex : Latéral + Ailier). Un Profil peut comporter plusieurs postes simultanément et **évoluer en cours de saison** si le joueur performe sur un nouveau poste. Sert à positionner un Joueur dans l'ADN d'équipe ou à identifier une Cible pour un Manquement.

### Compétence
Une aptitude évaluée sur 10, classée en trois catégories : Technique, Physique, Mental.

### Évaluation
Une notation datée des Compétences d'un Joueur. Les évaluations s'accumulent dans le temps pour former un **historique de progression**. L'historique permet d'identifier les axes de progression et de déclencher les actions adéquates (travail physique, mental, tactique, technique) au bon moment.

### Historique de progression
La série chronologique des Évaluations d'un Joueur du Noyau. Sert à mesurer l'évolution et à déclencher des Plans d'action ou des Alertes.

### Résultat
L'issue d'un match (victoire, match nul, défaite) avec son score, la Composition de départ, et les Changements effectués (joueur entrant, joueur sortant, minute).

### Composition
L'ensemble des joueurs du Noyau alignés pour un match, à un instant T. Sert de base pour calculer la Pondération de performance.

### Changement
Une substitution en cours de match : joueur sortant, joueur entrant, minute. Permet d'attribuer le Résultat à la bonne Composition. Ex : si 2 changements à la 75' et victoire 1-2, le Résultat est attribué à la Composition post-changement.

### Pondération de performance
Le poids d'un Résultat attribué à chaque Composition qui a joué ce match, proportionnel au temps de jeu. Permet de mesurer l'efficacité collective d'un groupe de joueurs sur la durée.

### Choix optimal d'équipe
La meilleure Composition possible à l'instant T, calculée en croisant l'Historique de progression individuel de chaque Joueur et la Pondération de performance des Compositions passées. Évolue dans le temps au fil des résultats et de la progression individuelle.

### Alerte
Un signal automatique déclenché quand un Joueur régresse sur une Compétence clé entre deux Évaluations. Invite à une prise de décision (plan d'action, discussion, suivi renforcé).

### Manquement
Un déficit identifié dans le Noyau — profil, compétence ou poste insuffisamment couvert — qui justifie l'ouverture d'une Recherche.

### Recherche
Une démarche de recrutement ouverte suite à un Manquement identifié. Une Recherche est associée à un Profil cible et génère le suivi de plusieurs Cibles.

## Flux principal

Noyau évalué → Manquement identifié → Recherche ouverte → Cibles suivies.
Les deux missions (gestion du Noyau et recrutement) sont liées : le recrutement découle de l'analyse du Noyau.

## Contexte sportif

**Club** : Union Rochefortoise (UR)
**Compétition** : National 1 ACFF — 3e division belge
**Utilisateur** : le directeur sportif (David). App mono-utilisateur, pas de collaboration.

## Saison et historique

L'historique d'un Joueur est **cumulatif sur plusieurs saisons** — les Évaluations ne sont pas effacées en fin de saison. La notion de saison (ex : 2024-2025) sert à contextualiser les données mais ne réinitialise pas l'historique.
