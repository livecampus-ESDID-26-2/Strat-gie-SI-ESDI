# Stratégie SI

## Chapitre 3 – Les principes d'évolutivité du SI : SOA, API, Micro-services

### Objectifs

- Comprendre l'importance de l'évolutivité pour maintenir un système d'information performant.
- Explorer les principales architectures facilitant l'évolutivité : SOA, API et Micro-services.
- Savoir comment intégrer ces concepts dans une stratégie SI pour répondre aux défis futurs.

### En résumé

L'évolutivité d'un système d'information (SI) consiste à anticiper la croissance des besoins d'une organisation.

### A – SOA (Service-Oriented Architecture)

#### Définition

La SOA (Service-Oriented Architecture) est une architecture logicielle modulaire qui organise les fonctionnalités d'un système d'information (SI) en plusieurs services indépendants et autonomes.

Chaque service représente une unité fonctionnelle distincte, telle que la gestion des commandes, la facturation, l'authentification des utilisateurs ou la gestion des stocks.

#### Caractéristiques clés

- **Services indépendants :** les services sont autonomes.
- **Communication via des interfaces standardisées :** les services interagissent entre eux en utilisant des API (Application Programming Interface) ou d'autres mécanismes de communication standardisés comme SOAP ou REST.
- **Réutilisation des services :** un service peut être réutilisé par plusieurs applications, ce qui favorise l'efficacité et réduit la redondance.

#### Avantages

- **Flexibilité :** la SOA favorise l'agilité des systèmes d'information en permettant l'ajout ou la suppression de services sans affecter le fonctionnement global du SI.
- **Facilite la maintenance :** chaque service étant indépendant, il peut être mis à jour ou corrigé sans que cela impacte les autres services.
- **Interopérabilité :** la SOA facilite l'interaction entre des systèmes hétérogènes, développés dans des langages différents ou hébergés sur des plateformes différentes.

#### Étude de cas SOA : Netflix

Netflix utilise une architecture SOA pour gérer efficacement son service de diffusion de contenu à grande échelle.

- Gestion des comptes
- Recommandations de contenu
- Streaming vidéo

Grâce à cette architecture SOA, Netflix peut évoluer rapidement, introduire de nouvelles fonctionnalités sans affecter la disponibilité générale du service.

### B – API (Application Programming Interface)

#### Définition

Les API sont des interfaces qui permettent à différentes applications ou systèmes de communiquer entre eux. Elles définissent un ensemble de règles pour les requêtes et les réponses, permettant à un logiciel d'accéder à un autre, ou d'utiliser des fonctionnalités externes.

Par exemple, une application peut utiliser une API pour accéder à une base de données distante, ou pour interagir avec un service de paiement.

#### Caractéristiques clés

- **Interface standardisée :** les API sont normalisées, ce qui permet aux développeurs de les utiliser facilement.
- **Types d'API :** les API REST (basées sur HTTP) sont les plus courantes, mais il existe aussi des API SOAP (basées sur XML) et des API GraphQL, qui permettent des requêtes plus flexibles.
- **Sécurité :** les API incluent souvent des mécanismes de sécurité comme l'authentification via des clés API, des jetons OAuth, ou d'autres méthodes pour assurer que seules les parties autorisées accèdent aux données.

#### Avantages

- **Connectivité :** les API facilitent l'intégration des services externes (comme les solutions de paiement ou de gestion de la relation client) avec les systèmes internes.
- **Évolutivité :** une API bien conçue permet d'ajouter des fonctionnalités ou de mettre à jour les services sans interrompre les autres processus du système.
- **Automatisation :** grâce aux API, les entreprises peuvent automatiser de nombreux processus.

#### Étude de cas API : Facebook

Facebook utilise une API qui permet aux développeurs d'intégrer des fonctionnalités de la plateforme dans d'autres applications.

Principales fonctionnalités de l'API Facebook :

- Connexion via Facebook
- Partage de contenu
- Accès aux données des utilisateurs

### C – Micro-services

#### Définition

L'architecture des micro-services divise une application en petits services indépendants, chacun étant responsable d'une tâche spécifique.

Contrairement à une architecture monolithique, où toutes les fonctionnalités sont regroupées dans une seule application, les micro-services sont isolés, autonomes, et peuvent évoluer indépendamment.

#### Caractéristiques clés

- **Services indépendants :** chaque micro-service peut être développé, testé et déployé indépendamment des autres, ce qui permet une grande agilité dans le développement et la maintenance.
- **Technologies variées :** chaque micro-service peut être écrit dans un langage différent selon ses besoins spécifiques.
- **Communication entre micro-services :** les micro-services communiquent entre eux via des API ou des systèmes de messagerie, assurant une interaction fluide sans dépendance forte.

#### Avantages

- **Évolutivité :** chaque micro-service peut évoluer indépendamment, ce qui permet d'adapter rapidement le SI aux besoins croissants, sans affecter le reste du système.
- **Résilience :** si un micro-service tombe en panne, cela n'affecte pas l'ensemble du système, car les autres services continuent de fonctionner normalement.
- **Flexibilité technologique :** cette approche permet d'utiliser différentes technologies pour chaque micro-service selon ses besoins spécifiques.

#### Étude de cas micro-services : Uber

Uber utilise une architecture de micro-services pour garantir la fiabilité et la performance de son application. En tant que plateforme reliant chauffeurs et passagers, Uber doit gérer un volume élevé de données et de transactions en temps réel.

Organisation des micro-services chez Uber :

- Gestion des trajets
- Facturation et paiement
- Géolocalisation

En résumé, l'architecture micro-services permet à Uber de gérer efficacement des millions de transactions tout en offrant une expérience utilisateur fluide et fiable.

### D – Conclusion

L'évolutivité du système d'information (SI) est un facteur clé pour assurer la pérennité et la compétitivité des entreprises dans un environnement technologique en constante évolution. La capacité d'un SI à s'adapter aux nouveaux besoins, aux évolutions du marché, ainsi qu'aux innovations technologiques est cruciale pour éviter l'obsolescence, améliorer les performances, et répondre rapidement aux exigences des clients et des utilisateurs.

Par ailleurs, ces architectures favorisent une meilleure gestion des risques. En isolant les services, les entreprises limitent l'impact des défaillances potentielles à un seul composant du SI, réduisant ainsi les interruptions globales. Cette résilience est particulièrement importante pour assurer la continuité des activités dans des environnements fortement interconnectés. En outre, la capacité à réutiliser les services à travers différents projets et domaines permet d'optimiser les ressources, de réduire les coûts de développement, et de faciliter la maintenance.

En résumé, les architectures SOA, API et microservices ne sont pas seulement des modèles techniques, mais des **leviers stratégiques** pour assurer la durabilité et la compétitivité des systèmes d'information à long terme. En mettant en place ces approches, les entreprises s'assurent de pouvoir s'adapter à des environnements en constante mutation, tout en conservant la flexibilité nécessaire pour innover, évoluer et répondre aux besoins futurs, sans compromettre ni la performance ni la stabilité de leur SI.

### Question / débat oral

Une API fait-elle partie du SOA ?
