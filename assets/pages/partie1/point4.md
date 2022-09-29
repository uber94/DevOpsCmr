## Point n°4 : Dev vs Ops

Les développeurs et les professionnels des opérations avaient des objectifs distincts, souvent complètement opposés, une direction de service distincte, des indicateurs de performance clés distincts et travaillaient souvent à des étages différents, voire dans des bâtiments différents. Il en résultait des équipes cloisonnées qui ne se préoccupaient que de leurs propres fiefs, des heures de travail interminables, des versions bâclées et des clients mécontents.

Si leur objectif ultime est de faire en sorte que l'utilisateur soit satisfait des systèmes qu'ils fournissent, leurs points de vue sur la manière de le faire tendent à être intrinsèquement opposés.


| Dev  | Ops |
| :---------------: | :-----:|
| Le Dev a pour mission de produire des innovations sur l'application et de les transmettre aux utilisateurs dans les meilleurs délais  |L' Ops a pour mission de s'assurer que les utilisateurs ont accès à un système stable, fiable, rapide et réactif |
| Aucun développeur ne veut produire intentionnellement une fonctionnalité qui fait planter l'application en cours d'utilisation  | Aucun responsable des opérations ne serait mécontent que les développeurs produisent des mises à jour avec de nouvelles fonctionnalités et capacités intéressantes |
| Les développeurs veulent et sont censés produire de nouvelles fonctionnalités, très rapidement  | Les Ops veulent et sont censés fournir un système stable, à tout moment|

Les développeurs avaiennt dans des équipes traditionnelles une date de sortie de nouvelles fonctionnalités (release) fixée à l'avance. Ils ne pouvaient les publier qu'à ce moment-là.

Les Ops connaissaient cette date et avaient suffisamment de temps pour tester les nouvelles fonctionnalités avant de les déployer. Parfois Ils pouvaient prendre plusieurs jours pour les déploiements.

DevOps a changé cette façon de travailler avec l'intégration continue (CI) et la livraison continue (CD), les développeurs publient désormais leurs fonctionnalités quotidiennement. Les développeurs veulent désormais que leurs fonctionnalités soient disponibles et opérationnelles (sur les environnements de développement, de test et de production) à la même fréquence que celle à laquelle ils les produisent et intègrent.

L'Ops doit maintenant gérer non pas une version de temps en temps, mais plusieurs versions régulièrement. Ces versions issus des builds peuvent ou non être prêts à être déployés, mais doivent être gérés par l'Ops et déployés dans des environnements de test et éventuellement de production. Les services d'exploitation se soucient désormais davantage de la qualité. Ils ne souhaitent pas que des fonctionnalités qui n'ont pas été correctement testés l'environnement de production. Il n'est plus nécessaire de prendre plusieurs jours pour déployer des fonctionnalités une fois qu'elles sont testées avec succès. Cependant, la stabilité doit être maintenue.