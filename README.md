# LearnRoadSigns
Première expérience de classification multi-classe avec les données réels

Pour ce travail, nous allons nous baser sur le dataset GTSRB (German Traffic Sign Recognition Benchmark) https://paperswithcode.com/dataset/gtsrb mais nous allons utuliser seulement une partie pour réduire le volume de données à télécharger en classe.

Nous allons utiliser les données suivantes :

1. Extrait du dataset (archive.zip)
https://drive.google.com/file/d/1r7mW-X_pFU74Xa3F4u0f4GRFdn7b_NHg/view?usp=sharing

2. Quelques images pour tester (test.zip)
https://drive.google.com/file/d/1lU51IeKpVvxlMFWMOF3RU-K91nhAopDf/view?usp=sharing

3. Si vous souhaitez savoir à quoi correspondent les labels
https://drive.google.com/file/d/12HNXYaOKWvY5SSNi8NLSqJhbiPcpQavC/view?usp=sharing

## Séance 1 

Pour réaliser le travail, suivez les consignes dans le google colab (travail sur les données 1-3)

## Séance 2 (programmée comme PERS)

Lors de cette séance, vous devez compléter le travail suivant : 
1 -  avec l'architecture du réseaux de NN qui donne les meilleurs résultats, refaires l'entrainement tout en améliorant la qualité des images par une égalisation de l'histogramme
vous pouvez utiliser la fonction exposure.equalize_adapthist de la bibliothéque OpenCV ou tester une autre méthode.

2 - Pour 2 classes différentes, trouvez dans le dataset des images des panneaux routiers de ces deux classes pour lequelles votre meilleure architecture ne va pas fonctionner 
- expliquez pourquoi et essayez de proposer une piste de solution

3 - Pour au moins 3  architectures des réseaux  NN que vous avez testé, évaluer les métriques suivantes :
- Matrices de confusion pour les ensemble train et test
- F1 score (F-mesure), Recall et Précision : https://stanford.edu/~shervine/l/fr/teaching/cs-229/pense-bete-machine-learning-petites-astuces, https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html

Commentez, expliquez les résultats
