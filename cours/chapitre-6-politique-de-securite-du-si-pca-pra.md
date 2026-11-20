# Stratégie SI

## Chapitre 6 – Politique de sécurité du SI : PCA, PRA

### Objectifs

- Comprendre les concepts clés du Plan de Continuité d'Activité (PCA) et du Plan de Reprise d'Activité (PRA).
- Identifier les risques et les menaces auxquels un système d'information est exposé.
- Élaborer une stratégie de sécurité pour garantir la continuité des opérations en cas d'incident.
- Savoir comment concevoir et mettre en œuvre des PCA et PRA efficaces pour minimiser les interruptions d'activité et les pertes de données.

### En résumé

La sécurité des systèmes d'information repose en grande partie sur des politiques de prévention et de résilience en cas de crise.

Le **PCA** vise à maintenir les activités essentielles d'une entreprise en cas de sinistre ou d'incident majeur, tandis que le **PRA** se concentre sur la restauration rapide des systèmes après une interruption.

Ces plans sont indispensables pour assurer la continuité des opérations, minimiser les pertes, et restaurer la confiance des clients et partenaires après une perturbation.

### A – Détail de la politique de sécurité du SI : PCA et PRA

#### Introduction à la politique de sécurité du SI

La politique de sécurité des systèmes d'information (SI) est un cadre global visant à protéger les actifs informationnels de l'entreprise.

Ces deux éléments sont complémentaires :

- le **PCA** se concentre sur le maintien de l'activité en situation de crise ;
- le **PRA** s'assure que, suite à un incident, les systèmes d'information peuvent être rapidement restaurés.

### B – Le Plan de Continuité d'Activité (PCA)

#### Définition et objectifs

Le Plan de Continuité d'Activité (PCA) est un document stratégique qui décrit les actions à entreprendre pour que les fonctions vitales de l'entreprise continuent à fonctionner en cas de perturbation majeure.

Il permet de garantir que les services critiques restent opérationnels, même en cas d'incidents graves, qu'ils soient d'origine humaine (panne, cyberattaque) ou naturelle (inondation, tremblement de terre).

#### Étapes de mise en place du PCA

##### Identification des services et processus critiques

- La première étape consiste à identifier les services essentiels à l'entreprise, c'est-à-dire ceux dont l'arrêt provoquerait des perturbations majeures.
- Il est également crucial de cartographier les dépendances technologiques et opérationnelles entre ces processus et d'autres services pour comprendre quels éléments doivent être protégés en priorité.

##### Analyse des risques et menaces

- Une fois les services critiques identifiés, l'étape suivante consiste à réaliser une analyse des risques.
- L'analyse des risques permet d'anticiper les scénarios les plus probables et de définir des plans d'actions adaptés à chaque type de crise.

##### Définition des scénarios de continuité

- Le PCA doit intégrer différents scénarios en fonction des types de risques identifiés.
- Par exemple, dans un scénario d'attaque par ransomware, le PCA pourrait prévoir des mécanismes de sauvegarde et de restauration de données spécifiques.

##### Mise en place des outils et solutions de continuité

- Virtualisation des serveurs
- Sauvegardes en temps réel
- Redondance des infrastructures

##### Sensibilisation et formation des équipes

- Il est essentiel de former les employés aux procédures d'urgence prévues dans le PCA.
- Chaque acteur doit connaître ses responsabilités en cas de crise.
- Des simulations et des exercices doivent être réalisés régulièrement pour tester la réactivité des équipes et la bonne exécution des procédures.

##### Mise en place de la gouvernance de la continuité

- Un PCA doit être supervisé et maintenu en permanence. Cela implique la création d'une équipe de gestion de la continuité, chargée de s'assurer que le plan reste à jour et de coordonner les tests réguliers.
- Cette équipe doit inclure des représentants des services IT, des métiers, et de la direction pour garantir que le PCA reste aligné avec les priorités stratégiques de l'entreprise.

#### Les défis de la mise en œuvre du PCA

La mise en place d'un PCA peut rencontrer plusieurs obstacles, notamment :

- **Coût élevé :** la redondance des infrastructures, les solutions de virtualisation et de sauvegarde, ainsi que les tests réguliers peuvent représenter des investissements importants.
- **Résistance au changement :** les employés, y compris au sein des équipes IT, peuvent être réticents à l'idée de modifier les processus opérationnels.
- **Complexité organisationnelle :** dans les grandes entreprises avec des systèmes très intégrés, la mise en place d'un PCA nécessite une coordination entre différents départements et peut devenir un processus complexe.

### C – Le Plan de Reprise d'Activité (PRA)

#### Définition et objectifs

Le Plan de Reprise d'Activité (PRA) est un plan complémentaire au PCA qui se concentre sur la restauration des systèmes d'information après une interruption majeure.

Contrairement au PCA qui vise à maintenir l'activité pendant l'incident, le PRA se focalise sur la réinitialisation et la récupération des systèmes une fois la crise résolue.

#### Étapes de mise en place du PRA

##### Évaluation des impacts après l'incident

- La première étape consiste à évaluer les dommages causés par l'incident.
- Cette analyse doit permettre d'identifier les systèmes touchés, les données perdues ou corrompues.
- Cette évaluation doit également permettre de prioriser les systèmes à rétablir.

##### Définition d'un plan de récupération

- Le PRA définit un ensemble de mesures pour restaurer les infrastructures, les systèmes applicatifs et les données.
- Cela inclut l'utilisation de sauvegardes (locale ou cloud), le redémarrage des serveurs critiques, la reconstruction des environnements virtuels, et la réintégration des systèmes dans l'infrastructure globale.

##### Coordination des équipes techniques et métiers

- La réussite d'un PRA dépend de la capacité à coordonner les différentes équipes impliquées dans la reprise d'activité, notamment les équipes IT, les équipes métiers, et la direction.
- Chaque équipe doit être informée de son rôle spécifique, et les communications entre elles doivent être fluides pour éviter tout retard dans les opérations de reprise.

##### Outils technologiques pour la reprise

- Sauvegardes régulières
- Virtualisation des systèmes
- Solutions de cloud computing

##### Tests de reprise réguliers

- Un PRA efficace doit être testé régulièrement à travers des simulations de crise.
- Les tests de PRA doivent également inclure des simulations d'incidents majeurs.

#### Intégration avec le PCA

Le PRA doit être étroitement lié au PCA pour garantir une continuité sans interruption majeure. L'idéal est que les deux plans soient conçus ensemble pour assurer une transition fluide de la continuité d'activité à la reprise après incident.

### D – Facteurs de succès d'une stratégie PCA/PRA

#### Préparation et planification minutieuses

Une stratégie PCA/PRA réussie repose sur une planification rigoureuse, basée sur une analyse approfondie des risques et une bonne compréhension des besoins de l'entreprise.

#### Engagement des équipes

La réussite des PCA et PRA dépend de l'implication de toutes les équipes, y compris les équipes métiers.

#### Évolution et mise à jour continue

Les risques évoluent avec le temps (cybermenaces, nouvelles technologies). Les PCA et PRA doivent donc être continuellement mis à jour pour refléter ces changements.

#### Gouvernance et supervision

Une gouvernance forte est nécessaire pour s'assurer que le PCA et le PRA sont exécutés correctement.

### E – Conclusion

La mise en œuvre d'un PCA et d'un PRA fait partie intégrante de la résilience organisationnelle et est essentielle pour protéger les entreprises des interruptions d'activité. Leur bonne conception, mise en place et gestion sont la clé pour garantir que, même en cas de sinistre majeur, une entreprise peut continuer à fonctionner et récupérer rapidement ses capacités complètes.

L'interconnexion entre ces deux plans, accompagnée de tests réguliers et de mises à jour continues, assure une protection optimale et une réactivité face aux imprévus.
