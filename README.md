![](https://scikit-image.org/_static/img/logo.png)

---
# Tutoriel d'utilisation du module scikit-image
Tutoriel ayant pour objectif d'illustrer une utilisation de la bibliothèque scikit-image pour la manipulation et l'analyse d'images en Python. &#x1F40D; 

Vous pouvez lancer les notebooks du tutoriel avec Binder  

[![Binder](https://mybinder.org/badge_logo.svg)]()  


Il y a 2 notebooks jupyter dans le répertoire `notebook` :  
- `intro.ipynb` : Introduction au tutoriel. cette intro vous présente comment est encoder une image et plus particulièrement en Python. Ainsi que l'intérêt d'utiliser le format TIFF pour des images de microscopie. Il vous présente également, les fonction du module scikit-image que l'on utilisera pour le tutoriel et les références qui nous ont permis de créer ce petit tutoriel.  

- `demo.ipynb` : Tutoriel d'utilisation du module scikit-image. Ce tutoriel vous guide pas à pas, pour détecter, analiser et réaliser des mesures sur les noyaux d'une image de microscopie photonique à épifluorescence.

---
## Manipulation des notebooks sur votre pc local

1. Assurrez-vous d'avoir une une installation miniconda ou anaconda (à l'aide de la commande : `conda --version`) et le logiciel de gestion de version Git. Si ce n'est pas le cas procéder à une installation de `conda` ([Miniconda](https://docs.conda.io/en/latest/miniconda.html) • [Anaconda](https://www.anaconda.com/products/individual)) et/ou de `Git` ([Git](https://git-scm.com/downloads)) 

1. clonez le dépot du tutoriel :  
```
git clone https://github.com/w2994a/projet_scikit-image.git
```
ou via connexion ssh : 
```
git clone git@github.com:w2994a/projet_scikit-image.git
```  

3. Déplacez-vous dans le répertoire du dépot du tutoriel :
```
cd projet_scikit_image
```  

4. créez l'environnement conda pour le tutoriel :
```
conda env create -f binder/environment.yml
```  

5. Activez l'environnement pour le tutoriel :
```
conda activate analyze-images
```  

6. Lancez Jupyter Lab pour commencer le tutoriel :
```
jupyter lab
```  

Si vous souhaitez refaire tutoriel ou utiliser l'environnement conda, seules les étapes 3, 5 et 6 seront nécessaires. On espère que ce petit tutoriel vous donnera envie d'explorer plus en profondeur, le module scikit-image et plus généralement la manipulation et l'analyse d'image en Python. &#x1F363;