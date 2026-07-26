# 🐔 Étude de marché international - Segmentation de pays par clustering

## 🎯 Contexte
Dans le cadre d'une stratégie d'expansion à l'international pour une entreprise 
agroalimentaire, ce projet vise à identifier les marchés export les plus prometteurs 
pour la viande de volailles, à partir de données de consommation et de démographie 
mondiale (FAO, ONU).

## 🔧 Méthodologie
- **Nettoyage & préparation des données** : traitement de datasets FAO (disponibilité 
  alimentaire) et démographiques (200+ pays), gestion des valeurs manquantes et 
  incohérences
- **Analyse exploratoire** : sélection des variables pertinentes (consommation, 
  production, population, importations)
- **Classification non supervisée** : Classification Ascendante Hiérarchique (CAH) 
  et K-Means pour segmenter les pays en groupes homogènes
- **Réduction de dimension** : Analyse en Composantes Principales (ACP) pour 
  visualiser et interpréter les clusters
- **Interprétation métier** : profilage des clusters (heatmaps) pour formuler des 
  recommandations stratégiques de ciblage

## 🛠️ Stack technique
`Python` `Pandas` `NumPy` `Scikit-Learn` `Scipy` `Matplotlib` `Seaborn`

## 📈 Résultat
Identification de groupes de pays à fort potentiel de croissance, permettant de 
prioriser les marchés à cibler pour une stratégie d'expansion commerciale.
