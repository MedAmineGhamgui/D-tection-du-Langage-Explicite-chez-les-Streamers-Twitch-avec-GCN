# Description du Jeu de Données

Ce jeu de données est utilisé pour la classification de nœuds et l'apprentissage par transfert. Il s'agit de réseaux sociaux d'utilisateurs de Twitch, des joueurs qui diffusent en direct dans une certaine langue. Les nœuds représentent les utilisateurs eux-mêmes, et les liens sont des amitiés mutuelles entre eux. Les caractéristiques des nœuds sont extraites en fonction des jeux joués et appréciés, de la localisation et des habitudes de streaming. Les jeux de données partagent le même ensemble de caractéristiques de nœuds, ce qui permet l'apprentissage par transfert entre les réseaux. Ces réseaux sociaux ont été collectés en mai 2018. La tâche supervisée associée à ces réseaux est la classification binaire des nœuds : il s'agit de prédire si un streamer utilise un langage explicite.

# Prédiction

Dans ce projet, nous utilisons un réseau de graphes (GCN) implémenté en PyTorch pour prédire si un streamer utilise un langage explicite dans un réseau social de jeux Twitch.

---
Cette version est développée par Mohamed Amine Ghamgui.
