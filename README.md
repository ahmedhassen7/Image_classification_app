# Image_classification_app


Explication de chaque répertoire dans Notebooks: 

1-Pre_processing

* P6_PreProcessing: ce Notebook comporte le traitement des images effectué 
et le stockage des images

2-scrach CNN

* 5_breeds model: Ce notebook comporte 
                  - model CNN classique avec 5 races de chien 
                  - Correction de sur-apprentissage avec le tuning des hyper-paramètres
                  - les différentes techniques de data augmentation testées 
* 120_breeds_model: Ce notebook comporte
                  - tester les paramètres optimales avec 20 races de chien
                  - valider le meilleur technique de data augmentation
                  - déployer les méthodes validées sur le model 120 races

3- transfer Learning

* VGG model
* Inception V3
* Inception_ResNet
* ResNet50_V2
* Xception

tous ces notebook comporte trois étapes d'entrainement: 
 - sans le fine_tuning
 - fine_tuning avec la première stratégie
 - fine_tuning avec la deuxième stratégie 



Concernant le déploiement de modèle, je vous invite à visiter mon github où j'ai mis tous ce qui faut pour lancer le modèle 

lien github: https://github.com/ahmedhassen7/Image_classification_app

Les étapes à suivre sont: 

1. Télécharger : - model.h5
                 - app.py
                 - templates
                 - static
2. mettre tous les fichiers dans un seul répertoire 

3. Ouvrir une fenetre de commande (anaconda prompt)

4. se placer dans le repertoire crée et lancer la commande **python app.py

5. ouvrir le lien url local fourni
