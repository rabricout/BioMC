## BCM
#### Introduction au Deep Learning
Raphaël Bricout



#### Pourquoi le deep learning ?
Traduction (Natural Language Processing)
<image src="./rapport/Images/google_trad.png"></image>


#### Pourquoi le deep learning ?
Transfert de style
<image src="./rapport/Images/Style_transfer.png" control style="width:75%"></image>


#### Pourquoi le deep learning ?
Jeux (Deep Learning)
<image src="./rapport/Images/atari.png" control style="width:25%"></image>
<image src="./rapport/Images/alphaGo.jpg" control style="width:43.4%"></image>


#### Pourquoi le deep learning ?
Inpainting (GAN)
<image src="./rapport/Images/montagne_1.png" control style="width:45%"></image>
<image src="./rapport/Images/montagne_2.png" control style="width:45%"></image>


#### Pourquoi le deep learning ?
Génération de contenu (DCGAN)
<image src="./rapport/Images/face-arithmetic.png" control style="width:80%"></image>


### Parenthèse
*Pas ou peu de réflexion morale sur les applications directes ou potentielles des systèmes implémentés*



### Pour s'y retrouver
<image src="./rapport/Images/ensembles.png" control style="width:80%"></image>


### Le principe de l'apprentissage
<image src="./rapport/Images/ML_description.png" control style="width:80%"></image>


### A quoi ressemble un réseau de neurones
<image src="./rapport/Images/Reseau_MLP.png" control style="width:100%"></image>


### A quoi ressemble un réseau de neurones
<image src="./rapport/Images/Reseau.png" control style="width:100%"></image>


### Le deep learning
 - méthode d'optimisation non convexe
 - de très bons résultats
 - peu de théorie

*Ça fonctionne, mais on ne sait pas vraiment pourquoi...*



## Quelques problèmes liés au machine learning


### Les données
Il faut : 
 - beaucoup de données
 - des données annotées
 - savoir manipuler ses données


### Le problème de la surinterprétation
*Si on entraîne trop, on ne va pas réussir à bien généraliser*


#### Le problème de la surinterprétation
<image src="./rapport/Images/overfit_1.png"></image>


#### Le problème de la surinterprétation
<image src="./rapport/Images/overfit_2.png"></image>


#### Le problème de la surinterprétation
<image src="./rapport/Images/overfit_3.png"></image>


#### Le problème de la surinterprétation
<image src="./rapport/Images/overfit_4.png"></image>


#### Le problème de la surinterprétation
<image src="./rapport/Images/overfit_5.png"></image>


### Rasoir d'Occam
Entre deux solutions qui donnent des **résultats comparables**, privilégier la **plus simple**


### Connaître ses données
<image src="./rapport/Images/audio.png" control style="width:55%"></image>


### Fléau de la dimension
 - explosion combinatoire en grande dimension
 - ex : images de $16\times16$ pixels: 
  - dimension de $256$
  - nombre d'images possibles ~$10^{77}$


### Morale
Pour faire du "big data", il faut : 
 - avoir des connaissances en informatique et en statistiques
 - construire un modèle spécifique aux données du problème
 - il est impensable de recycler un modèle ou un réseau pour un autre problème



## Et la biologie dans tout ça ?


### Le D.L. s'applique bien à la biologie
 - une très grande quantité de données
 - un format qui est bien adapté (séquence de lettres)


### Exemples
 - imagerie médicale
 - biologie des systèmes
 - génomique
 - génétique



### Credits
Images: 
 - Francis Bach (INRIA, ENS)
 - Vincent Lepetit (LaBRI, Université de Bordeaux)
 - Matthieu Aubry (LIGM, ENCP)
 - Yves Clément (IBENS)


### Crédits
Papiers:
 - Radford, A., Metz, L., & Chintala, S. (2015). Unsupervised representation learning with deep convolutional generative adversarial networks.
 - Iizuka, S., Simo-Serra, E., & Ishikawa, H. (2017). Globally and locally consistent image completion.
 - Mnih, V., Kavukcuoglu, K., Silver, D., Graves, A., Antonoglou, I., Wierstra, D., & Riedmiller, M. (2013). Playing atari with deep reinforcement learning.
 
