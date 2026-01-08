# Projet : Nettoyage des Ventes du Café

Présentation
Le but de ce projet était de transformer un fichier de ventes "sale" (erreurs de calcul, cases vides, doublons) en un fichier propre et prêt à être utilisé pour prendre des décisions.

Organisation du dossier
*DATA : Contient les données brutes et les données nettoyées.
*NOTEBOOKS : 
    1. 01_Exploration : Analyse des erreurs.
    2. 02_Nettoyage : Correction des prix et des types.
    3. 03_Transformation : Création de tableaux de bord.

Mon travail de "Data Refinement"
1. Audit : J'ai repéré les mots "ERROR" et les valeurs manquantes qui bloquaient les calculs.
2. Correction : 
   - J'ai forcé les colonnes à devenir des nombres.
   - J'ai recalculé le `Total Spent` (Quantité x Prix) pour corriger les erreurs.
   - J'ai remplacé les textes "UNKNOWN" par "Non Spécifié".
3. Nettoyage: J'ai supprimé les lignes en double et les ventes sans date.

Résultats et Décisions
Grâce aux tableaux générés dans l'étape 3, j'ai pu identifier :
- Top Produit : Le produit qui rapporte le plus d'argent.
- Affluence: Le jour de la semaine où il y a le plus de clients (pour mieux gérer le staff).
- Gain de qualité: Le chiffre d'affaires total est maintenant exact car les erreurs de calcul ont été réparées.
