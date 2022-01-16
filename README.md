# Projet 5 - OpenClassrooms
Parcours Data Science

Projet n°5 : "Segmentez des clients d'un site e-commerce"

- Source des données : https://www.kaggle.com/olistbr/brazilian-ecommerce

## Introduction du projet
La plateforme de e-commerce *Olist* souhaite réaliser une segmentation de ses clients qu'elle pourra utiliser au quotidien dans ses campagnes de communication. L'objectif de cette segmentation est de comprendre les différents types d'utilisateurs grâce à leur données comportementales et personnelles.

Il nous est demandé de fournir à l'équipe marketing une description actionable de notre segmentation et de sa logique sous-jacente pour une utilisation optimale, ainsi qu'une proposition de contrat de maintenance basée sur la stabilité des segments au cours du temps.

**Conclusions:** Il ressort de l'analyse que seulement 3% des utilisateurs contenus dans le jeu de données ont commandé plusieurs fois sur le site. Dans cette population l'analyse RFM permet de faire ressortir les différents types de profil permettant d'instruire les actions marketing à réaliser. L'analyse des segments montre une instabilité significative au delà de 3 mois, période que l'on retiendra dans la proposition du contrat de maintenance.


## Travail réalisé
- Cleaning du dataset
- Jointures et aggrégations sur la variable id client
- Segmentation RFM (Récence, Fréquence, Montant)
- Analyse exploratoire
- Standard scaling
- Réduction de dimensions
- Clustering + identification des profils clients
- Evolution des clusters dans le temps et proposition du contrat de maintenance


## Compétences évaluées
- Mettre en place le modèle d'apprentissage non supervisé adapté au problème métier
- Transformer les variables pertinentes d'un modèle d'apprentissage non supervisé
- Adapter les hyperparamètres d'un algorithme non supervisé afin de l'améliorer
- Évaluer les performances d’un modèle d'apprentissage non supervisé
