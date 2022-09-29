## Point n°5 : Dev et Ops

La solution à la bataille entre Dev et Ops est ce qu'est le DevOps et les pratiques qui le composent : atteindre l'équilibre entre innovation et stabilité. Dev et Ops doivent tous deux changer leur mode de fonctionnement et mieux s'aligner.

| en tant que Dev, je devrais  | en tant qu'Ops, je devrais |
| :---------------: | :-----:|
| travailler avec les Ops pour comprendre l'infratructure sur laquelle l'application sera exécutée  |     travailler avec le Dev dès la phase de définition des exigences et des spécifications du projet |
| comprendre l'architecture de notre système  | connaître les évolutions à venir et leur impact sur le système |
| comprendre comment les modifications de mon code peuvent avoir un impact sur l'environnement de production et pas que sur l'application  | m'assurer que le système peut accueillir de nouvelles évolutions sur l'applications au fur et à mesure qu'elles arrivent |
| comprendre les propriétés de l'environnement de production et comment mon applications doivent s'y comporter  | automatiser la gestion du système, car il est difficile, voir impossible de réaliser des changements rapides tout en assurant la stabilité des systèmes sans automatisation. L'automatisation permettra non seulement des changements rapides, mais aussi des retours arrière rapides, en cas de problème pendant le déploiement |
| comprendre sous quelles contraintes mon application doit fonctionner  | idéalement, versionner le système. Cela n'est possible que si l'infrastructure et toutes les modifications qui y sont apportées sont saisies et gérées sous forme de code |
|m'impliquer davantage dans les tests pour m'assurer que mon code fonctionne correctement et observer comment il se comportera en production. Cette phase nécessite une collaboration étroite avec l'équipe d'assurance qualité (QA) pour tester l'application dans un environnement similaire à celui de la production (iso-Prod)  | tout surveiller, dans les différents environnements (développement, test, réproduction, production) devant héberger l'application |
| apprendre à surveiller les applications déployées et à comprendre les mesures dont les Ops se soucient généralement (consommation RAM/CPU, Latence, etc.)  | être capable de repérer une instabilité potentielle avant qu'elle ne se produit, via du monitoring et de l'alerting |
| plus communiquer avec Ops  | plus communiquer avec les Dev |
