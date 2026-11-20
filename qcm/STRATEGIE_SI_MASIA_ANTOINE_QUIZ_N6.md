# Stratégie SI

**Étudiant :** MASIA Antoine  
**Livrable :** QUIZ N6  
**Chapitres couverts :** 6  
**Modalité :** Travail individuel  
**Professeur :** À compléter  

---

## Consignes

- Répondez aux questions suivantes en détaillant votre réponse.
- Appuyez-vous sur les notions du chapitre 6 (politique de sécurité du SI : PCA et PRA).
- Évitez les listes à puces sans explication : développez et justifiez chaque idée.
- Format de dépôt attendu : `STRATEGIE_SI_MASIA_ANTOINE_QUIZ_N6.pdf`

---

## Questions

### Question 1

Qu'est-ce qu'un Plan de Continuité d'Activité (PCA) et quel est son principal objectif ?

Le **Plan de Continuité d'Activité (PCA)** est un document stratégique qui décrit les actions à entreprendre pour que les **fonctions vitales** de l'entreprise continuent à fonctionner en cas de perturbation majeure.

Son **principal objectif** est de garantir que les services critiques restent opérationnels pendant la crise, qu'elle soit d'origine humaine (panne, cyberattaque) ou naturelle (inondation, séisme). Autrement dit, le PCA ne cherche pas d'abord à « tout réparer », mais à **maintenir l'activité essentielle** malgré l'incident, afin de limiter les pertes et de préserver la confiance des clients et partenaires.

---

### Question 2

Décrivez le rôle du Plan de Reprise d'Activité (PRA) dans la sécurité des systèmes d'information.

Le **Plan de Reprise d'Activité (PRA)** est le complément du PCA : il se concentre sur la **restauration des systèmes d'information** après une interruption majeure.

Son rôle dans la sécurité du SI est de permettre la **réinitialisation et la récupération** des infrastructures, applications et données une fois la crise maîtrisée ou en cours de résolution. Il organise les sauvegardes, le redémarrage des serveurs critiques, la reconstruction des environnements et la réintégration dans l'infrastructure globale. Sans PRA, même un PCA efficace laisserait l'entreprise dans un mode dégradé durable ; avec un PRA, elle récupère ses capacités complètes de façon ordonnée et priorisée.

---

### Question 3

Comment identifier les services critiques lors de l'élaboration d'un PCA ?

L'identification des services critiques est la **première étape** de mise en place du PCA. Elle consiste à repérer les services essentiels dont l'arrêt provoquerait des **perturbations majeures** pour l'entreprise.

Concrètement, on :

1. analyse les processus métier et leur impact en cas d'indisponibilité ;
2. **cartographie les dépendances** technologiques et opérationnelles entre ces processus et les autres services ;
3. priorise les éléments à protéger en premier (ceux dont dépendent le chiffre d'affaires, la sécurité des personnes, les obligations légales, etc.).

Cette cartographie évite de protéger des systèmes secondaires au détriment des fonctions vitales.

---

### Question 4

Quelles sont les principales menaces auxquelles un SI peut être exposé nécessitant un PCA ?

Un SI peut être exposé à des menaces d'origines diverses, justifiant un PCA :

- **humaines / techniques :** panne matérielle ou logicielle, erreur opérationnelle, cyberattaque (ex. ransomware) ;
- **naturelles :** inondation, tremblement de terre, incendie, etc. ;
- plus largement, tout incident majeur capable d'interrompre les processus critiques.

Le PCA doit intégrer des **scénarios de continuité** adaptés à ces risques. Par exemple, face à un ransomware, il prévoit des mécanismes de sauvegarde et de restauration spécifiques. L'analyse des risques permet d'anticiper les scénarios les plus probables et de définir des plans d'actions adaptés.

---

### Question 5

Quelles sont les technologies souvent utilisées pour garantir la continuité des services pendant une crise ?

Pour assurer la continuité pendant une crise, le cours met en avant notamment :

- la **virtualisation des serveurs** (redémarrage rapide sur une autre infrastructure) ;
- les **sauvegardes en temps réel** (ou quasi temps réel) pour limiter la perte de données ;
- la **redondance des infrastructures** (sites, réseaux, systèmes doublés).

Côté reprise (PRA), on retrouve aussi les sauvegardes régulières, la virtualisation et les **solutions de cloud computing**, qui facilitent la reconstruction et la bascule. Ces technologies ne remplacent pas le plan organisationnel, mais elles en sont le socle technique.

---

### Question 6

Comment testez-vous l'efficacité d'un PCA au sein d'une entreprise ?

L'efficacité d'un PCA se vérifie par des **simulations et exercices réguliers**. Il faut former les employés aux procédures d'urgence, s'assurer que chaque acteur connaît son rôle, puis **tester la réactivité** des équipes et la bonne exécution des procédures.

Ces tests permettent de détecter les trous dans le plan (procédures floues, dépendances oubliées, délais trop longs) et d'alimenter la gouvernance de la continuité : une équipe dédiée maintient le plan à jour et coordonne ces exercices. Un PCA non testé reste théorique ; un PCA exercé devient opérationnel.

---

### Question 7

En quoi la redondance des infrastructures peut-elle aider dans le cadre d'un PRA ?

La **redondance** (sites, serveurs, réseaux, stockages doublés) offre une capacité de bascule lorsque le site ou le système principal est hors service. Dans le cadre d'un PRA, elle accélère la **restauration** : on redémarre les services critiques sur une infrastructure de secours plutôt que de reconstruire entièrement depuis zéro.

Couplée à la virtualisation et aux sauvegardes (locale ou cloud), la redondance réduit le temps de reprise (RTO) et la perte de données admissible (RPO). Elle est donc un levier majeur pour que le plan de récupération soit réaliste et rapide après un incident majeur.

---

### Question 8

Quelles sont les étapes clés pour mettre en œuvre un PRA après un incident majeur ?

Après un incident majeur, le PRA s'articule typiquement ainsi :

1. **Évaluer les impacts** : systèmes touchés, données perdues ou corrompues, priorisation des systèmes à rétablir.
2. **Exécuter le plan de récupération** : restauration via sauvegardes, redémarrage des serveurs critiques, reconstruction des environnements virtuels, réintégration dans l'infrastructure.
3. **Coordonner les équipes** IT, métiers et direction, avec des rôles clairs et une communication fluide pour éviter les retards.
4. **Valider** le retour en service et, ensuite, capitaliser via des tests de reprise réguliers pour améliorer le plan.

L'idéal est que ce PRA soit déjà conçu en cohérence avec le PCA, pour une transition fluide de la continuité vers la reprise.

---

### Question 9

Expliquez la différence entre un PCA et un PRA en termes de timing et d'objectifs.

| Critère | PCA | PRA |
|---------|-----|-----|
| **Timing** | Pendant la crise / l'incident | Après (ou en sortie de) l'interruption majeure |
| **Objectif** | **Maintenir** les activités essentielles | **Restaurer** les systèmes d'information |
| **Focus** | Continuité métier en mode dégradé ou de secours | Récupération technique et retour à la normale |

Le PCA répond à la question : *« Comment continuer à fonctionner malgré l'incident ? »*  
Le PRA répond à : *« Comment remettre le SI en état après l'incident ? »*

Ils sont complémentaires et doivent être conçus ensemble pour assurer une transition fluide.

---

### Question 10

Pourquoi est-il important d'informer régulièrement les parties prenantes pendant et après une crise informatique ?

Informer régulièrement les parties prenantes (IT, métiers, direction, parfois clients / partenaires) est crucial car la réussite d'un PRA — et plus largement de la gestion de crise — dépend de la **coordination** et de communications **fluides**.

Sans information claire :

- les rôles se brouillent et les opérations de reprise prennent du retard ;
- les métiers prennent de mauvaises décisions faute de statut fiable ;
- la confiance interne et externe se dégrade.

Pendant la crise, la communication aligne les priorités et accélère l'exécution du PCA/PRA. Après la crise, elle permet de rendre compte, de rassurer, et d'alimenter les retours d'expérience pour mettre à jour les plans. C'est aussi un facteur de succès de la stratégie PCA/PRA : engagement des équipes et gouvernance forte.
