.. _animateur_overlays_edition:

Page gestion avancée des Overlays
==========================================

La page de gestion avancée des overlays ressemble à ceci :

.. figure:: _images/overlays_edition/overlays_edition_modification.PNG
   :alt: Panel animateur de PicturWall, page gestion avancée des overlays.
   :align: center

.. danger:: Attention, cette page est à manipuler avec précaution. Vous pouvez complètement planter un overlay depuis cette dernière. Néanmoins, vous avez la possibilité de réinitialiser un overlay édité.


Cette page vous permet de gérer chaque paramètre de chaque overlay de PicturWall :
 * :ref:`Gestion de l'image affiché <animateur_overlays_edition_image>` : taille
 * :ref:`Gestion du cadre <animateur_overlays_edition_cadre>` : (l'image de fond) : position de l'image incorporé
 * :ref:`Gestion du logo <animateur_overlays_edition_logo>` : position
 * :ref:`Gestion du commentaire <animateur_overlays_edition_commentaire>` : position, taille, police, couleur
 * :ref:`Gestion du texte principal <animateur_overlays_edition_texte_principal>` : position, taille, police, couleur
 * :ref:`Gestion du texte secondaire <animateur_overlays_edition_texte_secondaire>` : position, taille, police, couleur
 * :ref:`Gestion de la "date de l'évènement" <animateur_overlays_edition_texte_date>` : position, taille, police, couleur


.. note:: Une vidéo sera faite pour expliquer les paramètres modifiables. Le lien se trouvera directement ici.

Généralités sur les paramètres :
 * Les paramètres sont modifiables pour la version paysage et pour la version portrait.
 * Les positions sont en deux dimensions : X pour l'axe des abscisse, Y pour l'axe des ordonnées (repère cartésien). Les valeurs sont en pixel.
 * Les taille de police sont exprimés en pixel.
 * Les couleurs de polices sont définies en héxadécimal (mais vous avez une matrice de choix disponible selon votre navigateur)
 * Une couleur de fond par "thème" : gestion de l'image, du cadre, du logo...


Image explicative sur les positions X, Y : Repère cartésien, sources:  `Warmaths.fr <https://warmaths.fr/MATH/REPERAGE/reperagepoint%20dansrepere%20cartesien.htm>`_

.. figure:: _images/overlays_edition/overlays_edition_repere_cartesien.PNG
   :alt: Image explicative sur les positions X, Y : Repère cartésien, sources Warmaths.fr
   :align: center

.. note:: Les overlays font 1800*1200 pixels, en format paysage. 1200*1800 pour le portrait.


.. _animateur_overlays_edition_selection:

Sélection d'un overlay à modifier
------------------------------------------

Pour modifier un overlay, vous devez déjà le sélectionner. Pour cela, utilisez la liste déroulante sous "Overlay à modifier" et sélectionnez celui qui vous intéresse :


.. figure:: _images/overlays_edition/overlays_edition_a_modifier_2.PNG
   :alt: Panel animateur de PicturWall, page gestion avancée des overlays, overlays à modifier.
   :align: center

.. note:: L'overlay sélectionné par défaut est celui que vous avez paramétré comme étant utilisé dans :ref:`Choix de l'overlay <animateur_parametres_impression_overlays_choix>` . Il aparait en rouge dans la liste des overlays à modifier.

Cliquez ensuite sur "*Modifier cet overlay*" pour l'éditer.

Votre page ressemblera maintenant à ceci :

.. figure:: _images/overlays_edition/overlays_edition_modification.PNG
   :alt: Panel animateur de PicturWall, page gestion avancée des overlays, modification des paramètres.
   :align: center


A gauche : L'ensemble des paramètres de l'overlay
Au milieu : Une prévisualisation de l'overlay choisi en mode paysage
Au milieu : Une prévisualisation de l'overlay choisi en mode portrait

.. important:: L'actualisation de la prévisualisation se fait uniquement lorsque vous :ref:`sauvegardez vos modifications <animateur_overlays_edition_modification>`.

.. _animateur_overlays_edition_modification:

Modifier un paramètre et le sauvegarder
------------------------------------------

Une fois que vous avez :ref:`sélectionné votre overlay <animateur_overlays_edition_selection>`, vous pouvez éditer ses paramètres.

Pour cela, cliquez sur la paramètre que vous voulez éditer :

.. figure:: _images/overlays_edition/overlays_edition_modification_parametre.PNG
   :alt: Panel animateur de PicturWall, page gestion avancée des overlays, modification d'un paramètre.
   :align: center

Puis cliquez sur le bouton "Sauvegarder les modifications".

.. note::  L'actualisation de la prévisualisation se fait uniquement lorsque vous sauvegardez vos modifications.

.. important:: Si vous voulez revenir à la configuration d'origine de cet overlay, il vous suffit de cliquer sur le bouton "Restaurer les paramètres usines pour cet overlay"



.. _animateur_overlays_edition_image:

Gestion de l'image affiché
------------------------------------------

.. figure:: _images/overlays_edition/overlays_edition_image.PNG
   :alt: Panel animateur de PicturWall, page gestion avancée des overlays, modification paramètre de l'image.
   :align: center

Voici les paramètres modifiables par rapport à l'image incorporé :
 * Sa taille (X,Y) mode portrait et paysage.

.. _animateur_overlays_edition_cadre:

Gestion du cadre
------------------------------------------

.. figure:: _images/overlays_edition/overlays_edition_cadre.PNG
   :alt: Panel animateur de PicturWall, page gestion avancée des overlays, modification paramètre du cadre.
   :align: center

Voici les paramètres modifiables par rapport au cadre :
 * La Position (X,Y) de l'image à incorporer.

.. _animateur_overlays_edition_logo:

Gestion du logo
------------------------------------------

.. note:: L'envoi du logo se fait sur la :ref:`page paramètre, section impression, choisir le logo à imprimer <animateur_parametres_impression_logo_fichier>` !
.. important:: Veuillez activer :ref:`Imprimer le logo sur les photos <animateur_parametres_impression_logo_activer>` pour apposer votre logo sur chaque photo imprimé !

.. figure:: _images/overlays_edition/overlays_edition_logo.PNG
   :alt: Panel animateur de PicturWall, page gestion avancée des overlays, modification paramètre du logo.
   :align: center

Voici les paramètres modifiables par rapport au logo :
 * Sa position (X,Y) mode portrait et paysage.

.. _animateur_overlays_edition_commentaire:

Gestion du commentaire
------------------------------------------

.. important:: Veuillez activer :ref:`l'impression des commentaires <animateur_parametres_impression_overlays_commentaire>` si vous voulez que les invités puissent imprimer leur commentaire !


.. figure:: _images/overlays_edition/overlays_edition_commentaire.PNG
   :alt: Panel animateur de PicturWall, page gestion avancée des overlays, modification paramètre du commentaire.
   :align: center

Voici les paramètres modifiables par rapport au commentaire :
 * Sa position (X,Y) mode portrait et paysage.
 * Sa taille (X,Y) mode portrait et paysage.
 * Sa police.
 * Sa couleur.

.. _animateur_overlays_edition_texte_principal:

Gestion du texte principal
------------------------------------------

.. important:: L'écriture du texte principale se fait sur la :ref:`page paramètre, section impression <animateur_parametres_impression_overlays_texte_principal>` !

.. figure:: _images/overlays_edition/overlays_edition_texte_principal.PNG
   :alt: Panel animateur de PicturWall, page gestion avancée des overlays, modification paramètre du texte pricipal.
   :align: center

Voici les paramètres modifiables par rapport au texte principal :
 * Sa position (X,Y) mode portrait et paysage.
 * Sa taille (X,Y) mode portrait et paysage.
 * Sa police.
 * Sa couleur.

.. _animateur_overlays_edition_texte_secondaire:

Gestion du texte secondaire
------------------------------------------

.. note:: Selon l'overlay modifié, il n'y a pas de texte secondaire associé !
.. important:: L'écriture du texte secondaire se fait sur la :ref:`page paramètre, section impression <animateur_parametres_impression_overlays_texte_secondaire>` !


.. figure:: _images/overlays_edition/overlays_edition_texte_secondaire.PNG
   :alt: Panel animateur de PicturWall, page gestion avancée des overlays, modification paramètre du texte secondaire.
   :align: center

Voici les paramètres modifiables par rapport au texte secondaire :
 * Sa position (X,Y) mode portrait et paysage.
 * Sa taille (X,Y) mode portrait et paysage.
 * Sa police.
 * Sa couleur.

.. _animateur_overlays_edition_texte_date:

Gestion de la "date de l'évènement"
------------------------------------------

.. important:: L'écriture de la date de l'évènement se fait sur la :ref:`page paramètre, section impression <animateur_parametres_impression_overlays_texte_date>` !

.. figure:: _images/overlays_edition/overlays_edition_texte_date.PNG
   :alt: Panel animateur de PicturWall, page gestion avancée des overlays, modification paramètre de la date de l'évènement.
   :align: center

Voici les paramètres modifiables par rapport à la date de l'évènement :
 * Sa position (X,Y) mode portrait et paysage.
 * Sa taille (X,Y) mode portrait et paysage.
 * Sa police.
 * Sa couleur.

