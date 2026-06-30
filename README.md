# Estimation-It-rative-de-Quantiles
Intervalles de Confiance pour l’Algorithme de Robbins-Monro

Résumé

Dans le cadre de l’analyse des données massives ou arrivant en flux continu (streaming data), le stockage des observations passées peut devenir rapidement impossible. Ce travail s’intéresse à l’estimation
de quantiles en ligne via l’algorithme stochastique de Robbins-Monro, combiné à la méthode innovante du bootstrap pondéré de Fang pour la construction d’intervalles de confiance non-paramétriques
sans stockage de données. Nous étudions empiriquement les performances de cet algorithme à travers
K = 100 simulations indépendantes sur un horizon de N = 1 000 itérations, appliquées à quatre distributions de données variées : Normale, Uniforme, Exponentielle et Log-Normale. L’implémentation
finale montre une robustesse remarquable, parvenant à atteindre précisément les taux de couverture
nominaux cibles (jusqu’à 90% pile pour le quantile extrême de la loi Log-Normale), validant ainsi l’efficacité et la précision de cette approche adaptative en ligne pour modéliser l’incertitude sur différents
types de supports.

Abstract

In the context of large-scale or streaming data analysis, storing past observations quickly becomes
computationally unfeasible. This work focuses on online quantile estimation using the Robbins-Monro
stochastic algorithm, combined with Fang’s innovative weighted bootstrap approach to build nonparametric confidence intervals without data storage. We empirically investigate the performance of this
algorithm through K = 100 independent simulations over a horizon of N = 1, 000 iterations, applied to
four distributions with distinct geometries : Normal, Uniform, Exponential, and Log-Normal. The final
implementation demonstrates remarkable robustness, precisely reaching the targeted nominal coverage
rates (up to exactly 90% for the extreme quantile of the Log-Normal distribution), thus validating the
efficiency and accuracy of this adaptive online approach in capturing uncertainty across various types
of supports.
