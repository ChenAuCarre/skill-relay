# User stories

Format : **En tant que** [rôle], **je veux** [action], **afin de** [bénéfice].

Les stories sont organisées par **rôle**. Celles qui reposent sur une capacité du moteur de recommandation l'indiquent entre crochets (voir [Capacités du moteur](#capacités-du-moteur)).

## Capacités du moteur

Trois capacités transverses, partagées par plusieurs rôles :

- **Capacité A – Matching et classement** : associer à chaque personne un ensemble de compétences et proposer les meilleurs profils pour les compétences demandées, selon un critère quantitatif (nombre et niveau des compétences couvertes) ou qualitatif (adéquation au besoin).
- **Capacité B – Compréhension du langage naturel** : traduire une phrase libre, qui ne contient pas forcément les bons mots-clés, en compétences. Quand la traduction n'est que partielle, demander des précisions en s'appuyant sur ce qui a été compris.
- **Capacité C – Typologie de référent** : identifier, selon le contexte, le type de référent adapté.
  - *Expert* : expertise pointue sur un sujet (beaucoup de compétences précises pour un sujet étroit).
  - *Référent transverse* : connaissance d'ensemble (compétences plus larges pour un sujet plus vaste), par exemple un chef d'équipe ou un référent métier.

## Collaborateur

- **C1 – Profil** : je veux construire mon profil en décrivant mes compétences en langage naturel, ou en important mon CV ou mon profil LinkedIn, afin de ne pas avoir à tout saisir manuellement.
- **C2 – Visibilité** : je veux choisir qui peut voir mes compétences (mes collègues, mon manager, tout le Groupe), afin de rester maître de mes données tout en gagnant en visibilité.
- **C3 – Suggestions** : je veux recevoir des suggestions de postes correspondant à mon profil, afin de découvrir des opportunités de mobilité.
- **C4 – Candidature** : je veux consulter les offres internes et y candidater directement, afin de simplifier ma mobilité interne.
- **C5 – Fraîcheur** : je veux que le référentiel de compétences reflète les arrivées, les départs et les mobilités internes, afin qu'il reste fiable dans le temps.

## Manager (dont responsable de projet)

- **M1 – Synthèse équipe** : je veux voir la synthèse des compétences de mon équipe, afin d'identifier ses forces et ses lacunes.
- **M2 – Recherche** : je veux rechercher des profils par compétence, dans mon équipe comme dans le reste du Groupe, afin de trouver rapidement la bonne expertise, y compris pour constituer l'équipe d'un nouveau projet. [Capacité A]
- **M3 – Besoin en langage naturel** : je veux décrire un besoin avec mes propres mots et obtenir les profils ou équipes les plus pertinents, avec l'explication de leur pertinence, afin de choisir en confiance. [Capacité B]
- **M4 – Pilotage** : je veux m'appuyer sur ces données pour répartir la charge de travail et piloter le développement des compétences de mon équipe, afin d'anticiper les besoins de formation.
- **M5 – Classement** : je veux que les profils trouvés soient classés selon la quantité et la qualité des compétences demandées, afin de voir en premier les personnes les plus adaptées à mon projet. [Capacité A]

## RH (dont chargé de recrutement)

- **R1 – Vue globale** : je veux disposer d'une vue globale des compétences de l'ensemble des collaborateurs, afin de piloter la stratégie de compétences de l'entreprise.
- **R2 – Écarts** : je veux identifier les compétences insuffisamment représentées dans l'effectif, afin de proposer des formations internes ou d'engager des recrutements externes.
- **R3 – Recrutement** : je veux croiser le besoin d'un projet avec le référentiel interne avant d'ouvrir un recrutement, afin de repérer les personnes déjà présentes qui ont les compétences et de privilégier la mobilité interne. [Capacités A, B]

## Équipe de première ligne (support client ou interne, accueil, hotline, guichet)

- **F1 – Orientation** : je veux saisir une demande telle que je l'ai reçue, même sans savoir la traduire en vocabulaire métier, et obtenir les compétences associées ainsi que la personne ou le service qui peut la traiter, afin de réduire les allers-retours quand le problème est mal identifié. [Capacité B]
- **F2 – Clarification** : je veux que, lorsque ma demande n'est comprise que partiellement, l'outil me pose des questions en s'appuyant sur ce qu'il a déjà compris, afin d'affiner le besoin sans repartir de zéro. [Capacité B]

## Équipe de communication (interne et externe)

- **K1 – Porte-parole** : je veux identifier, pour un sujet d'actualité (article, enregistrement audio ou vidéo, conférence, table ronde), le collaborateur le plus pertinent, afin de représenter au mieux l'expertise de l'entreprise. [Capacités A, B]
- **K2 – Expert ou vulgarisateur** : je veux que l'outil distingue, selon le sujet, le besoin d'un expert pointu de celui d'un référent aux connaissances transverses (chef d'équipe, référent métier), afin de choisir entre une parole technique et une explication accessible au plus grand nombre. [Capacité C]

## Points à trancher

- **Visibilité (C2) et rôles opérationnels** : si un collaborateur restreint la visibilité de ses compétences, la première ligne et la communication ne le verront pas. Quel comportement par défaut pour ces rôles ?
- **Périmètre du démonstrateur** : la mobilité (C3, C4) et la formation (M4, R2) relèvent moins du cœur « trouver le bon expert ». Faut-il les marquer hors du premier périmètre ?
- **Redirection vers un service (F1)** : le référentiel couvre-t-il les services et responsables, ou seulement les personnes ?
