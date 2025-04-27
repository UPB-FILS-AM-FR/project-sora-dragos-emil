<h2>Système de parking automatisé avec barrière utilisant Arduino Uno 🚗🚧</h2>

## Description

Ce projet présente un système intelligent de parking avec barrière automatisée, contrôlé par Arduino Uno.
Le système détecte l'arrivée des véhicules grâce à des capteurs IR, actionne une barrière via un servo-moteur pour contrôler l'accès, et affiche des informations pertinentes sur un écran LCD, comme le nombre de places disponibles ou des messages d'instruction pour les utilisateurs.

## Pourquoi ce projet?

Les systèmes de gestion de parking automatisés représentent une solution pratique à plusieurs problèmes urbains actuels:

1)<b>Optimisation de l'espace:</b> En contrôlant précisément les entrées et sorties, ce système permet une utilisation maximale des emplacements disponibles.

2)<b>Application pratique:</b> Ce prototype démontre des concepts fondamentaux d'électronique et de programmation dans un contexte d'usage quotidien, rendant l'apprentissage immédiatement applicable.

3)<b>Formation technologique complète:</b> Ce projet intègre des notions d'électronique, de programmation, de mécanique et d'interface utilisateur dans une seule réalisation.

## Fonctionnement

Le système de parking automatisé opère selon trois mécanismes principaux:

1)<b>Système de détection</b>

a)<b>Capteurs IR:</b> Stratégiquement placés à l'entrée du parking, ces capteurs détectent l'arrivée ou le départ d'un véhicule et envoient un signal au microcontrôleur.

b)<b>Comptage des véhicules:</b> Le système maintient un décompte précis des places occupées et disponibles, assurant ainsi une gestion optimale de l'espace.

2)<b>Contrôle d'accès</b>

a)<b>Servo-moteur:</b> Actionnant une barrière physique, le servo-moteur régule l'accès au parking en fonction des informations reçues des capteurs et de la logique programmée.

b)<b>Logique décisionnelle:</b> L'Arduino analyse les données des capteurs en temps réel pour déterminer si la barrière doit s'ouvrir (places disponibles) ou rester fermée.

3)<b>Interface utilisateur</b>

a)<b>Écran LCD avec module I2C:</b> Fournit des informations essentielles comme le nombre de places disponibles, des instructions pour les conducteurs, ou des messages de bienvenue.

b)<b>Indicateurs visuels:</b> Des signaux lumineux peuvent compléter l'affichage LCD pour indiquer rapidement si le parking est complet ou disponible.

## Schéma des composants du système

![Schéma fonctionnel](./CircuitD.png)