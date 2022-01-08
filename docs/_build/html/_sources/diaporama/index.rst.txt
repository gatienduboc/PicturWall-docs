.. _diaporama:

Présentation du diaporama
===============================

Le diaporama, c'est ce qui est disponible via la prise HDMI de PicturWall.
Il est totalement automatisé et personnalisable.

Une fois en place, le diaporama ressemblera à ceci :

.. figure:: _images/diaporama.jpg
   :alt: Diaporama de PicturWall.
   :align: center

Vous noterez les différentes parties du diaporama (entouré en rouge).


Visuellement, vous pourrez changer l'apparence :
 * Du :ref:`bandeau défilant <diaporama_bandeau>`
 * Des :ref:`commentaires <diaporama_commentaire>`
 * De :ref:`l'identité de l'invité <diaporama_invite>`
 * De :ref:`l'arrière-plan <diaporama_arriere_plan>`
 * Du :ref:`logo affiché <diaporama_logo>`
 * Des :ref:`transitions <diaporama_transition>`

Bien-sûr, tout est personnalisable sur le diaporama, vous le découvrirez par la suite.
Par exemple, vous pouvez personnaliser la vitesse de défilement des médias :

.. figure:: ../panel_animateur/_images/parametres/projecteur/parametres_projecteur_vitesse.PNG
   :alt: Paramètre: Vitesse de défilement des médias.
   :align: center

.. admonition:: Important

   La vitesse de défilement des médias s'applique uniquement aux photos. Pour les vidéos, elles sont entièrement lues.

À force de personnalisation, vous pouvez arriver sur des résultats très différents, en voici quelques exemples :

.. figure:: _images/diaporama_custom1.PNG
   :alt: Diaporama: Affichage custom
   :align: center

.. figure:: _images/diaporama_custom2.PNG
   :alt: Diaporama: Affichage custom
   :align: center

.. figure:: _images/diaporama_custom3.PNG
   :alt: Diaporama: Affichage custom
   :align: center


Mettre en place le diaporama
================================

Pour projeter le diaporama via un vidéoprojecteur ou via un écran, il vous suffit de brancher votre support vidéo sur la prise HDMI de la carte de PicturWall.
Ensuite, vous n'avez plus qu'à brancher PicturWall. Le diaporama va s'afficher sur l'écran dès que la carte sera opérationnelle.

Vous devez compter environ 30 secondes après le démarrage de la carte électronique avant de voir le diaporama s'afficher à l'écran.

.. admonition:: Mise en place du diaporama

    Pensez bien à relier votre support de projection à PicturWall avant d'allumer ce dernier.

.. _diaporama_modes:

Les différents modes de diffusion
==================================

Vous avez 4 modes de diffusion sur PicturWall :
 * Le mode ":ref:`Normal <diaporama_mode_normal>`" : permettant la diffusion des médias envoyés par les invités
 * Le mode de ":ref:`Présentation <diaporama_mode_presentation>`" : forçant la diffusion du média de présentation de PicturWall même si les invités ont envoyé des médias
 * Le mode ":ref:`Explication <diaporama_mode_explication>`" : forçant la diffusion d'un média d'explication (exemple: média permettant de ce connecter au Wifi PicturWall
 * Le mode ":ref:`Mise en avant <diaporama_mode_mise_en_avant>`": forçant la diffusion des médias sélectionnés par l'animateur 


.. _diaporama_mode_normal:

Mode "Normal"
-----------------

Ce que l'on appelle **"Mode Normal"**, c'est la diffusion classique des médias.

Vous pouvez faire passer les médias dans deux ordres :
 * **Ordre chronologique** : Les médias défilent de l'envoi le plus ancien au plus récent.
 * **Ordre aléatoire** : Les médias défilent de manière aléatoire (un média ne peut pas être diffusé deux fois à la suite).

 L'ordre des médias est défini sur la page paramètre (rubrique Générales).

.. _diaporama_mode_presentation:

Mode "Présentation"
------------------------

Ce que l'on appelle **"Mode Présentation"** c'est la diffusion d'une image particulière dite "de présentation".

Le mode de présentation s'active via la page de paramètres (rubrique Générales), voici le paramètre en question :

.. figure:: ../panel_animateur/_images/parametres/general/parametres_general_mode_presentation.PNG
   :alt: Paramètre: mode de présentation.
   :align: center

Si vous l'activez, vous devriez voir ceci sur le diaporama :

.. figure:: _images/diaporama_presentation.PNG
   :alt: Diaporama, Mode de présentation de PicturWall.
   :align: center

Le média de présentation reste affiché sur l'écran jusqu'à temps que vous désactiviez le mode de présentation pour revenir sur le mode :ref:`"Normal" <diaporama_mode_normal>`.

Vous pouvez personnaliser le média de présentation sur la page de paramètre, rubrique "Projecteur" :

.. figure:: ../panel_animateur/_images/parametres/projecteur/parametres_projecteur_presentation.PNG
   :alt: Paramètre: mode de présentation, choix de l'image.
   :align: center

Vous pouvez également personnaliser les QRCode de connexion au Wifi et connexion au panel invité sur la page de paramètre, rubrique "Projecteur" :

.. figure:: ../panel_animateur/_images/parametres/projecteur/parametres_projecteur_qrcode_wifi.PNG
   :alt: Paramètre: mode de présentation, définir le QRCode de connexion wifi.
   :align: center   

.. figure:: ../panel_animateur/_images/parametres/projecteur/parametres_projecteur_qrcode_panel_invite.PNG
   :alt: Paramètre: mode de présentation, définir le QRCode de connexion au panel invité.
   :align: center 


.. _diaporama_mode_explication:

Mode "Explication"
---------------------

Ce que l'on appelle **"Mode Explication"** c'est la diffusion d'une image particulière dite "d'explication".

Le mode d'explication s'active via la page de paramètres (rubrique Générales), voici le paramètre en question :

.. figure:: ../panel_animateur/_images/parametres/general/parametres_general_mode_explication.PNG
   :alt: Paramètre: mode d'explication.
   :align: center

Si vous l'activez, vous devriez voir ceci sur le diaporama :

.. figure:: _images/diaporama_tuto.PNG
   :alt: Diaporama, Mode d'explication de PicturWall.
   :align: center

Le média d'explication reste affiché sur l'écran jusqu'à temps que vous désactiviez le mode d'explication pour revenir sur le mode :ref:`"Normal" <diaporama_mode_normal>`.

Vous pouvez personnaliser le média d'explication sur la page de paramètre, rubrique "Projecteur" :

.. figure:: ../panel_animateur/_images/parametres/projecteur/parametres_projecteur_explication.PNG
   :alt: Paramètre: mode d'explication, choix de l'image.
   :align: center


.. _diaporama_mode_mise_en_avant:

Mode "Mise en Avant"
---------------------

Ce que l'on appelle **"Mode Mise en Avant"** c'est la diffusion d'un ou plusieurs médias sélectionnés par l'animateur.

Le mode mise en avant s'active via la :ref:`page de gestion des médias <animateur_gestion_medias>`, voici le paramètre en question :

.. figure:: ../panel_animateur/_images/gestion_medias/gestion_medias_avant.PNG
   :alt: Gestion des médias: Médias mis en avant.
   :align: center

Dans le cas où vous avez une imprimante reliée à picturWall, le paramètre se trouvera dans la rubrique "Mise en avant & Médias en OR" :

.. figure:: ../panel_animateur/_images/gestion_medias/gestion_medias_avant_or.PNG
   :alt: Gestion des médias: Médias mis en avant & médias en OR.
   :align: center

Si vous l'activez, seuls les médias choisis comme Médias en Or" seront affichés à l'écran. La démarche à suivre pour gérer les médias se trouve ici : :ref:`gestion des médias <animateur_gestion_medias_or>`.



.. figure:: ../panel_animateur/_images/parametres/projecteur/parametres_projecteur_explication.PNG
   :alt: Paramètre: mode d'explication, choix de l'image.
   :align: center


.. _diaporama_bandeau:

Le bandeau défilant
======================

Sur le diaporama de PicturWall, vous avez la possibilité de faire défiler un texte en haut de l'écran, dans notre cas, il ressemble à cela :

.. figure:: _images/diaporama_bandeau.PNG
   :alt: Paramètre: mode d'explication, choix de l'image.
   :align: center

Bien sûr, tout est personnalisable sur ce bandeau, vous pouvez :ref:`contrôler ceci <animateur_parametres_section_bandeau>`:
 * Activation du bandeau
 * Sa position
 * Son texte
 * Son encadrement
 * Son fond
 * Son opacité
 * Sa taille
 * Sa vitesse de défilement

Tout ceci est contrôlable depuis la page de paramètres de PicturWall, :ref:`Section bandeau défilant <animateur_parametres_section_bandeau>`

Voici à quoi ressemble la rubrique de réglage du bandeau défilant :

.. figure:: ../panel_animateur/_images/parametres/bandeau/parametres_bandeau.PNG
   :alt: Paramètre: Rubrique bandeau défilant.
   :align: center

Pour avoir plus d'informations sur chacun des paramètres, veuillez vous rendre sur la :ref:`Section bandeau défilant <animateur_parametres_section_bandeau>`


.. _diaporama_commentaire:

Les commentaires
======================

Lorsque les invités envoient des médias, ils ont la possibilité d'envoyer des commentaires afin de les afficher sur l'écran. Vous pouvez personnaliser l'affichage des commentaires !

Voici à quoi ressemble un commentaire :

.. figure:: _images/diaporama_commentaire.PNG
   :alt: Exemple de commentaire sur PicturWall
   :align: center

Bien sûr, tout est personnalisable, par exemple, vous pouvez changer :ref:`ceci <animateur_parametres_section_commentaires>` :
 * Activation des commentaires avec l'envoi des médias
 * Sa couleur
 * Son encadrement
 * Son fond
 * Son opacité
 * Sa taille

Tout ceci est contrôlable depuis la page de paramètres de PicturWall, :ref:`section commentaires <animateur_parametres_section_commentaires>`:

Voici à quoi ressemble la rubrique de réglage des commentaires :

.. figure:: ../panel_animateur/_images/parametres/commentaires/parametres_commentaires.PNG
   :alt: Paramètre: Rubrique commentaires.
   :align: center

.. note:: Pour avoir plus d'informations sur chacun des paramètres, veuillez vous rendre sur la :ref:`section commentaires <animateur_parametres_section_commentaires>`.


.. _diaporama_invite:

L'identité de l'invité
========================

Lorsque qu'un invité envoie un média, son nom et prénom est affiché en bas à droite de l'écran.

Une fois de plus, vous pouvez personnaliser :ref:`l'affichage de l'identité <animateur_parametres_projecteur_invite>` :
 * Affichage de l'identité
 * Sa couleur
 * Sa taille

Tout ceci est contrôlable depuis la page de paramètres de PicturWall, :ref:`Section projecteur <animateur_parametres_section_projecteur>`.

Voici à quoi ressemble la rubrique projecteur :

.. figure:: ../panel_animateur/_images/parametres/projecteur/parametres_projecteur.PNG
   :alt: Paramètre: Rubrique projecteur.
   :align: center

.. note:: Pour avoir plus d'informations sur chacun des paramètres, veuillez vous rendre sur la :ref:`Section projecteur <animateur_parametres_section_projecteur>`


.. _diaporama_arriere_plan:

L'arrière-plan
========================

Selon les dimensions des médias, un arrière-plan, plus ou moins grand, fait son apparition !

L'arrière-plan peut se personnaliser, par exemple, vous pouvez mettre :ref:`en arrière-plan <animateur_parametres_projecteur_transition_type>` :
 * Un flou d'image
 * Une couleur
 * Une image

Tout ceci est contrôlable depuis la page de paramètres de PicturWall, :ref:`Section projecteur <animateur_parametres_section_projecteur>`

Voici à quoi ressemble la rubrique projecteur :

.. figure:: ../panel_animateur/_images/parametres/projecteur/parametres_projecteur.PNG
   :alt: Paramètre: Rubrique projecteur.
   :align: center

.. note:: Pour avoir plus d'informations sur chacun des paramètres, veuillez vous rendre sur la :ref:`Section projecteur <animateur_parametres_section_projecteur>`


.. _diaporama_logo:

Le logo
============

Vous pouvez choisir d'afficher un logo sur l'écran de projection.

Voilà ce que vous pouvez :ref:`personnaliser <animateur_parametres_projecteur_logo>`
 * Son affichage
 * Son image
 * Son opacité

Tout ceci est contrôlable depuis la page de paramètres de PicturWall, :ref:`Section projecteur <animateur_parametres_section_projecteur>`

Voici à quoi ressemble la rubrique projecteur:

.. figure:: ../panel_animateur/_images/parametres/projecteur/parametres_projecteur.PNG
   :alt: Paramètre: Rubrique projecteur.
   :align: center

.. note:: Pour avoir plus d'informations sur chacun des paramètres, veuillez vous rendre sur la :ref:`Section projecteur <animateur_parametres_section_projecteur>`


.. _diaporama_transition:

Les transitions
=================

Entre les médias, il y a des transitions, que vous pouvez :ref:`personnaliser <animateur_parametres_section_projecteur>` :
 * Leur type
 * Leur durée

Tout ceci est contrôlable depuis la page de paramètres de PicturWall, :ref:`Section projecteur <animateur_parametres_section_projecteur>`

Voici à quoi ressemble la rubrique projecteur :

.. figure:: ../panel_animateur/_images/parametres/projecteur/parametres_projecteur.PNG
   :alt: Paramètre: Rubrique projecteur.
   :align: center

.. note:: Pour avoir plus d'informations sur chacun des paramètres, veuillez vous rendre sur la rubrique associée :ref:`personnaliser <animateur_parametres_section_projecteur>`


.. _picturwall.tv: http://picturwall.tv/
