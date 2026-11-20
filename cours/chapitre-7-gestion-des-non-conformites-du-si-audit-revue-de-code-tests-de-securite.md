# Stratégie SI

## Chapitre 7 – Gestion des non-conformités du SI : audit, revue de code, tests de sécurité

### Objectifs

- Comprendre les différentes approches pour identifier et corriger les non-conformités dans un système d'information.
- Savoir utiliser les audits, revues de code et tests de sécurité comme outils pour évaluer et améliorer la sécurité et la conformité du SI.
- Développer une stratégie efficace de gestion des non-conformités, incluant l'identification, la correction et la prévention des vulnérabilités.

### En résumé

La gestion des non-conformités du SI est une démarche essentielle pour assurer la sécurité, la fiabilité et la conformité des systèmes d'information.

Les audits, les revues de code et les tests de sécurité permettent de détecter des failles et de mettre en place des mesures correctives.

Ce chapitre aborde les principes, les outils et les méthodes pour évaluer la conformité du SI.

### A – Audit du SI

L'audit du système d'information (SI) est un processus incontournable pour évaluer l'efficacité des contrôles internes, vérifier la conformité aux réglementations et identifier les faiblesses qui pourraient compromettre la sécurité ou la performance des systèmes.

Ces audits peuvent être menés par des équipes internes ou externes, selon l'ampleur et les objectifs visés.

#### Les audits couvrent plusieurs dimensions du SI

- Sécurité des systèmes
- Conformité aux réglementations
- Efficacité des processus

#### Étapes de l'audit

##### Planification

La première étape de tout audit est la phase de planification. Il s'agit de déterminer quels aspects du SI seront évalués et quelles seront les méthodes employées. Cela nécessite souvent des discussions préalables avec les responsables métiers et techniques pour s'assurer que les objectifs de l'audit sont en adéquation avec les priorités de l'entreprise.

##### Collecte des données

Une fois la planification réalisée, la collecte des données peut commencer. Cette étape inclut généralement des entretiens avec les parties prenantes, des observations directes, et l'analyse des documents clés (logs, rapports de performance, configurations des systèmes, etc.).

##### Analyse des résultats

À partir des données collectées, l'équipe d'audit commence à analyser les résultats. L'objectif est d'identifier les vulnérabilités et non-conformités potentielles, qu'elles soient liées à la sécurité, à l'efficacité des processus ou à la conformité réglementaire.

##### Rapport d'audit

L'analyse se traduit par la rédaction d'un rapport d'audit détaillant les résultats obtenus. Ce rapport met en lumière les points faibles du SI, les zones à améliorer, ainsi que les recommandations pour corriger les failles identifiées.

##### Suivi et mise en œuvre des recommandations

La phase de suivi consiste à vérifier que les actions correctives proposées ont bien été mises en place.

### B – Revue de code

La revue de code est une pratique courante dans le développement logiciel, mais elle joue également un rôle clé dans la gestion des non-conformités au sein du SI. En effet, la qualité du code source des applications utilisées dans une entreprise a un impact direct sur la sécurité et la performance du SI.

#### Objectifs de la revue de code

La revue de code a plusieurs objectifs, qui convergent vers l'amélioration globale de la qualité des logiciels utilisés par l'entreprise.

- **Identification des erreurs :** une analyse approfondie du code permet de détecter des erreurs de logique ou de syntaxe qui pourraient entraîner des bugs en production.
- **Amélioration des performances :** la revue de code permet d'optimiser certains segments du code pour améliorer la rapidité ou l'efficacité des applications.
- **Conformité aux normes de sécurité :** la revue permet de s'assurer que le code respecte les normes de sécurité.
- **Homogénéité des pratiques :** la revue garantit que le code suit les conventions de style et les pratiques de développement.

#### Types de revue de code

Il existe plusieurs façons de réaliser une revue de code, en fonction des besoins de l'entreprise et des ressources disponibles :

- Revue par les pairs (Peer Review)
- Revue par des experts en sécurité
- Outils automatisés de revue de code

#### Processus de revue de code

1. **Préparation :** avant de commencer la revue, le code doit être stable et prêt pour l'examen.
2. **Analyse :** les relecteurs passent en revue le code en se concentrant sur les aspects définis à l'avance.
3. **Retour et corrections :** les commentaires et suggestions sont retournés au développeur.
4. **Validation finale :** une fois que toutes les modifications ont été effectuées, le code est approuvé.

La revue de code n'est pas uniquement bénéfique pour améliorer la qualité du logiciel. Elle est aussi un levier d'apprentissage pour les développeurs, qui bénéficient d'un retour d'expérience continu.

### C – Tests de sécurité

Les tests de sécurité, souvent appelés tests d'intrusion ou *penetration testing*, sont un pilier fondamental de la gestion des non-conformités du SI.

#### Différents types de tests de sécurité

- **Tests de pénétration (Pen testing) :** simuler des attaques sophistiquées contre le SI pour identifier des failles que des hackers pourraient exploiter.
- **Tests d'intrusion :** se concentrer sur la tentative d'accès non autorisé aux systèmes. Ils visent à identifier des faiblesses dans les contrôles d'accès et dans les mécanismes d'authentification.
- **Scans de vulnérabilité :** analyses automatisées qui passent en revue les systèmes pour identifier les vulnérabilités connues.

#### Processus de tests de sécurité

1. **Préparation et définition de la portée :** avant d'effectuer un test de sécurité, il est essentiel de définir quels systèmes et composants seront testés.
2. **Réalisation des tests :** les tests de sécurité sont ensuite menés selon des scénarios prédéfinis. Les équipes de test tentent d'exploiter des failles et d'accéder à des données ou des systèmes sans autorisation.
3. **Analyse des résultats et rapport :** une fois les tests effectués, les résultats sont analysés pour comprendre quelles failles ont été exploitées, comment elles ont été identifiées et quelles sont leurs implications pour la sécurité globale du SI.
4. **Correction et validation :** l'entreprise doit alors mettre en œuvre les recommandations issues du rapport, corriger les vulnérabilités identifiées, puis réaliser des tests de validation pour s'assurer que les correctifs ont été efficaces.

### D – Processus global de gestion des non-conformités

La gestion des non-conformités est un processus itératif qui repose sur plusieurs étapes :

1. **Identification :** les audits, les revues de code et les tests de sécurité.
2. **Analyse et hiérarchisation :** une fois les non-conformités détectées, il est nécessaire de les analyser.
3. **Action corrective :** les équipes techniques mettent en place les correctifs nécessaires.
4. **Suivi et prévention :** il est indispensable de suivre les actions correctives pour s'assurer de leur efficacité.

Le suivi des non-conformités est crucial pour garantir la résilience du SI et prévenir les incidents de sécurité futurs.

### E – Conclusion

La gestion des non-conformités au sein du système d'information est un processus critique pour assurer la sécurité, la stabilité et la conformité de l'infrastructure technologique d'une entreprise.

Que ce soit à travers des audits réguliers, des revues de code approfondies ou des tests de sécurité rigoureux, chaque étape contribue à identifier et à corriger les vulnérabilités avant qu'elles ne se transforment en failles exploitables.

Ces pratiques permettent de prévenir les interruptions de service, de garantir la protection des données sensibles et de répondre aux exigences réglementaires.
