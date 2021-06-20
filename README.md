# ProjectMajor (Projet majeur année 5 à l'ESAIP)

Identification du port de masque avec le ML.

Vous trouverez tout dans le fichier .ipynb, le notebook google colab.

Architecture : 

YOLOv5 
    |--Dataset
        |--Facemask : copie du dataset
        |--images : test, train, val
        |--labels : test, train, val
    |-Kaggle : dataset importé
        |--annotations
        |--images
        |--kaggle.json
    |-data
    |-models
    |-utils
    |-runs
        |--detect : résultats des détections après inférence
        |--train : résultats de l’entraînement
    |--train.py : script pour entraîner le modèle
    |--detect.py : script pour la détection après l'entraînement
    |--weights
    |--requirements.txt
    |--Correct.jpg : image masque correct
    |--Incorrect.jpg : image masque incorrect
