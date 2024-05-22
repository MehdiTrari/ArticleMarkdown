### Introduction

#### Présentation de la thématique abordée dans l’article
L'article "Intent Communication between Autonomous Vehicles and Pedestrians" de Milecia Matthews, Girish V. Chowdhary et Emily Kieson traite de la communication d'intention entre les véhicules autonomes et les piétons. Avec l'avènement des véhicules autonomes, il devient crucial de comprendre comment ces véhicules peuvent interagir en toute sécurité avec les piétons aux intersections, aux passages piétons, et dans d'autres situations de circulation. Traditionnellement, les conducteurs humains utilisent des signaux visuels et des gestes pour communiquer leurs intentions aux piétons (Page 1). Cependant, l'absence de conducteur humain dans les véhicules autonomes pose un nouveau défi : comment ces véhicules peuvent-ils signaler leurs intentions de manière claire et compréhensible aux piétons pour éviter les malentendus et les situations dangereuses ?

#### Explication de votre choix de travailler sur cet article
Nous avons choisi cet article parce qu'il aborde une problématique cruciale pour l'intégration des véhicules autonomes dans notre société : la sécurité des piétons. La communication efficace entre les véhicules autonomes et les piétons est essentielle pour prévenir les accidents et assurer une coexistence harmonieuse sur les routes. De plus, cet article combine des aspects techniques et psychologiques, offrant une perspective complète sur le développement de systèmes de communication d'intention (Page 2). En travaillant sur cet article, nous avons l'opportunité d'explorer comment les avancées technologiques peuvent être appliquées de manière à respecter et à s'adapter aux comportements humains.

### Première Partie: Présentation du domaine de recherche et des définitions à connaître

#### Communication d'intention (Intent Communication System - ICS)
La communication d'intention (ICS) est un système conçu pour signaler clairement les intentions des véhicules autonomes aux piétons. Ce système utilise des dispositifs matériels comme des LED et des haut-parleurs pour afficher des messages visuels et audio (Pages 3-4). Par exemple, des messages comme "Cross Now" peuvent être affichés pour indiquer aux piétons qu'ils peuvent traverser en toute sécurité (Page 4). L'ICS vise à remplacer les signaux visuels traditionnels utilisés par les conducteurs humains, en fournissant des indications claires et prévisibles.

#### Problèmes d'interaction véhicule-piéton
Les interactions entre les véhicules autonomes et les piétons présentent des défis uniques. Sans conducteur humain pour fournir des signaux visuels directs, il est nécessaire de développer des systèmes qui peuvent communiquer les intentions du véhicule de manière intuitive et compréhensible pour les piétons (Pages 1-2). La confiance des piétons dans les actions des véhicules autonomes est essentielle pour éviter les situations de blocage et les accidents. Par exemple, lors des expériences, il a été observé que les piétons réagissent plus positivement lorsque l'intention du véhicule est clairement communiquée via l'ICS (Pages 4-5).

#### Modèles de Processus de Décision Markov Décentralisés (Dec-MDP)
Pour modéliser les interactions entre les piétons et les véhicules autonomes, l'article utilise les Processus de Décision Markov Décentralisés (Dec-MDP). Ce modèle permet de prendre en compte l'incertitude des actions des piétons et du véhicule en observant leurs états respectifs et en ajustant les actions en conséquence (Pages 7-8). Les Dec-MDP sont utilisés pour simuler différentes situations et évaluer comment les piétons réagissent aux actions du véhicule, ce qui aide à améliorer la conception du système ICS (Page 9).

#### Importance de la Connaissance Préalable
L'article souligne également l'importance de la connaissance préalable des piétons sur le fonctionnement des véhicules autonomes. Les expériences ont montré que les piétons qui ont été introduits au système ICS et qui comprennent son fonctionnement sont plus susceptibles de faire confiance aux actions du véhicule et de réagir de manière prévisible (Pages 6-7). Cette connaissance préalable réduit l'hésitation des piétons et augmente leur confort autour des véhicules autonomes.

### Références aux Pages
- **Page 1:** Introduction à la problématique de la communication d'intention entre véhicules autonomes et piétons.
- **Page 2:** Exploration de la psychologie derrière la perception des véhicules autonomes par les piétons.
- **Pages 3-4:** Description du système ICS et des composants matériels et logiciels utilisés.
- **Pages 4-5:** Résultats des tests en conditions réelles montrant l'impact positif de l'ICS sur la confiance des piétons.
- **Pages 7-8:** Présentation des modèles Dec-MDP utilisés pour simuler les interactions et ajuster les actions des véhicules.
- **Pages 6-7:** Importance de la connaissance préalable des piétons sur le fonctionnement des véhicules autonomes et l'impact sur leur comportement.

### Deuxième Partie: Le Fond de l’Article

#### Objectif de l’Article
L'objectif principal de l'article est de développer et de tester un système de communication d'intention (ICS) pour les véhicules autonomes. Ce système vise à signaler les intentions du véhicule de manière claire et compréhensible aux piétons pour éviter les malentendus et les situations de blocage (Page 1). L'ICS doit être simple, efficace et capable de fonctionner dans divers environnements tout en intégrant les attentes et les perceptions psychologiques des piétons (Page 2).

#### Présentation de l’Approche Innovante Utilisée pour Atteindre cet Objectif

##### Système de Communication d'Intention (ICS)
- **Composants du Système :**
  - L'ICS est composé de LED pour afficher des messages visuels, de haut-parleurs pour les messages audio, et de lumières stroboscopiques pour attirer l'attention des piétons (Pages 3-4).
  - Le système est intégré dans un véhicule de golf autonome équipé de capteurs lidar, de caméras et de logiciels de détection de piétons (Page 4).

- **Fonctionnement :**
  - Le système utilise des caméras et des capteurs pour détecter les piétons et afficher des messages appropriés sur les écrans LED du véhicule. Les messages sont simples, tels que "Cross Now" pour indiquer aux piétons qu'ils peuvent traverser en toute sécurité (Page 4).
  - Les haut-parleurs émettent des signaux audio pour renforcer les messages visuels.

##### Expériences Réelles et Simulations
- **Tests en Conditions Réelles :**
  - Des tests ont été effectués avec 76 participants, divisés en groupes en fonction de leur connaissance préalable du véhicule et de l'activation ou non de l'ICS (Page 5).
  - Les résultats ont montré que les piétons réagissent plus positivement et de manière plus prévisible lorsque l'ICS est activé. Les participants avec une connaissance préalable du système ont montré une confiance accrue (Pages 6-7).

- **Simulations :**
  - Des simulations basées sur le modèle Dec-MDP ont été utilisées pour modéliser les interactions entre les piétons et les véhicules autonomes dans différents scénarios (Pages 7-8).
  - Les simulations ont permis de tester des situations potentiellement dangereuses et d'ajuster les paramètres de l'ICS pour améliorer la confiance des piétons (Pages 9-10).

##### Mesure et Quantification de la Confiance
- **Niveaux de Confiance :**
  - Les simulations ont inclus cinq niveaux de confiance (20%, 40%, 60%, 80%, et 99%) pour évaluer l'impact de la communication d'intention sur les piétons (Pages 11-12).
  - Les résultats ont montré que la confiance des piétons augmente avec une connaissance préalable du véhicule et que l'activation de l'ICS joue un rôle crucial dans la réduction de l'hésitation et l'augmentation de la sécurité perçue (Page 12).

#### Conclusions de l’Article
L'article conclut que le système de communication d'intention (ICS) est efficace pour améliorer la sécurité et la confiance des piétons lorsqu'ils interagissent avec des véhicules autonomes. Les tests réels et les simulations ont démontré que l'ICS réduit les situations de blocage et permet aux piétons de comprendre clairement les intentions du véhicule (Pages 11-12). L'introduction préalable des piétons au système joue également un rôle significatif dans l'augmentation de leur confiance (Page 12).

#### Travaux Futurs
L'article propose plusieurs pistes pour les recherches futures, notamment :
- Étudier comment augmenter la confiance des piétons envers les véhicules autonomes en introduisant des dynamiques de groupe dans les tests.
- Améliorer la compréhension des attentes des utilisateurs pour développer des systèmes de communication d'intention encore plus efficaces (Page 12).

### Conclusion

#### Ce que vous avez appris grâce à cet article
Cet article nous a permis de comprendre l'importance de la communication claire et efficace entre les véhicules autonomes et les piétons pour assurer la sécurité et la confiance. Nous avons également appris comment les aspects psychologiques et comportementaux doivent être intégrés dans le développement de nouvelles technologies pour qu'elles soient acceptées par le public (Pages 1-2).

#### Votre opinion sur la recherche en général
La recherche sur l'interaction entre les véhicules autonomes et les piétons est essentielle pour le futur de la mobilité urbaine. Il est crucial de continuer à explorer comment les technologies peuvent être conçues pour être non seulement fonctionnelles mais aussi intuitives et sûres pour les utilisateurs. Les études comme celle-ci montrent l'importance d'intégrer des tests réels et des simulations pour développer des systèmes robustes et acceptables par le public (Pages 11-12).

