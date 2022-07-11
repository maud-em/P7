# Preuve de Concept


## SEGMENTATION D’IMAGES MEDICALES

Notre client, qui fabrique des appareils d’Imagerie à Résonance Magnétique (IRM), souhaite mettre à jour sa méthode de segmentation automatiquement d’organes dans le cadre du diagnostic et du traitement médical assisté par ordinateur. Les données en question, sont des tranches de scans IRM. Le but étant de détecter les organes présents selon la zone observée.

Nous testons ici plusieurs modèles: 
* le Fully Convolutional Network **U-Net** de la librairie tensorflow/keras **segmentation-models**
* le TransUNet de la librairie **transunet** qui combine les atouts d'auto attention d'un Vision transformer avec un U-Net
* le UNETR qui n'utilise que des transformers empilés dans l'encoder connectés au décodeur U-Net

DESCRIPTION DES NOTEBOOKS

* [Notebook d’entraînement U-Net](https://github.com/maud-em/P7/blob/main/uwm-unet-2-5d-aug-training-tf.ipynb)
* [Notebook d’entraînement TransUNet](https://github.com/maud-em/P7/blob/main/uwm-transunet-2-5d-aug-training-tf.ipynb)
* [Notebook d’entraînement UNETR](https://github.com/maud-em/P7/blob/main/tensorflow-unetr-train%20(1).ipynb)


DEPENDENCES

* Librairies **Transunet** and **segmentation-models**


## Authors

Maud Comboul
https://github.com/maud-em/
