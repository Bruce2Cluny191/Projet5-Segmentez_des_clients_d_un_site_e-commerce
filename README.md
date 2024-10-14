# Segmentation des Clients pour Olist

<img src="https://user.oc-static.com/upload/2019/02/24/15510251487267_Capture%20d%E2%80%99e%CC%81cran%202019-02-20%20a%CC%80%2017.37.38.png" />

## Contexte
Olist, une entreprise brésilienne spécialisée dans la vente sur les marketplaces en ligne, souhaite obtenir une segmentation de ses clients pour optimiser ses campagnes de communication. L'objectif est de comprendre les différents types d'utilisateurs à partir de leur comportement et de leurs données personnelles.

## Objectif du Projet
- Fournir une segmentation des clients exploitable par l'équipe marketing d'Olist.
- Proposer une description actionnable de la segmentation et de sa logique sous-jacente.
- Recommander une fréquence de mise à jour du modèle de segmentation pour maintenir sa pertinence.

## Étapes du Projet

### 1. Analyse Exploratoire
- Importation et nettoyage des données fournies par Olist.
- Fusion des datasets pour créer un dataframe unique.
- Feature engineering pour extraire les variables Récence, Fréquence, Montant, Score moyen des avis, Délai moyen de livraison, et Avance de livraison moyenne.

### 2. Modélisation
- Utilisation de méthodes non supervisées pour regrouper les clients en profils similaires.
- Test de différentes configurations de dataframes et algorithmes de clustering (KMeans, CAH, DBSCAN).
- Sélection du modèle final basé sur KMeans avec 4 clusters.

### 3. Simulation de Maintenance
- Analyse de la stabilité des segments au cours du temps.
- Utilisation de l'Indice Rand Ajusté (ARI) pour déterminer la fréquence de mise à jour nécessaire du modèle de segmentation.

## Résultats
- Segmentation des clients en 4 clusters : 
  - Cluster A : Anciens clients ponctuels à faible pouvoir d'achat
  - Cluster B : Nouveaux clients à faible pouvoir d'achat
  - Cluster C : Clients récurrents à pouvoir d'achat modéré
  - Cluster D : Clients occasionnels à haut pouvoir d'achat
- Recommandation de mise à jour du modèle tous les 32 jours pour maintenir sa pertinence.

## Livrables
- [Pham-Van_Yann_1_notebook_exploration_062023.ipynb](https://github.com/Bruce2Cluny191/Projet5-Segmentez_des_clients_d_un_site_e-commerce/blob/main/Pham-Van_Yann_1_notebook_exploration_062023.ipynb) : Un notebook d'analyse exploratoire.
- [Pham-Van_Yann_2_notebook_essais_062023.ipynb](https://github.com/Bruce2Cluny191/Projet5-Segmentez_des_clients_d_un_site_e-commerce/blob/main/Pham-Van_Yann_2_notebook_essais_062023.ipynb) : Un notebook d'essais des différentes approches de modélisation.
- [Pham-Van_Yann_3_notebook_simulation_062023.ipynb](https://github.com/Bruce2Cluny191/Projet5-Segmentez_des_clients_d_un_site_e-commerce/blob/main/Pham-Van_Yann_3_notebook_simulation_062023.ipynb) : Un notebook de simulation pour déterminer la fréquence de mise à jour du modèle.
- [Pham-Van_Yann_4_presentation_062023.pdf](https://github.com/Bruce2Cluny191/Projet5-Segmentez_des_clients_d_un_site_e-commerce/blob/main/Pham-Van_Yann_4_presentation_062023.pdf) : Une présentation pour obtenir des retours sur l'approche.

## Contact
Pour toute question, veuillez me contacter sur [LinkedIn](https://www.linkedin.com/in/chasseur2valeurs/).
