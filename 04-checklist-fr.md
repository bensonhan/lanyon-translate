---
layout: page
title: Liste de contrôle de session (impression / image)
lang: fr
ref: checklist
permalink: /checklist-fr
---

### Les paramètres de la caméra

Assure-toi:
* La mise au point est réglée sur ** A ** sur la lentille
* L'ISO est réglé sur ** 100 **
* MODE est réglé sur ** M **
* L'ouverture est définie entre f8 et f11 (commencez par f8)
* La vitesse d'obturation est réglée entre 1 / 60ème et 1 / 125e (affichage de 60 à 125) (commencez par 60)
* Balance des blancs (WB) est réglé sur 5000K
* La qualité d'image (QUAL) est définie sur RAW

### Configuration de l'appareil photo

* Fixez l'appareil photo au trépied
* Attachez la télécommande à l'appareil photo
* Attachez la télécommande TTL en haut de la caméra
* Retirer le cache de l'objectif de la caméra
* Lien caméra vers ordinateur portable
* Ouvrir et configurer Lightroom
  * Assurez-vous que Lightroom s'ouvre avec le catalogue avec lequel vous travaillez (ex. "Soviet_posters" ou "film_posters")
  * Dans le menu Fichier, choisissez Tâches, puis Démarrez le Tethered Shooting
  * Paramètres:
    * Donnez un nom à la session (ex soviet02, film03, etc.)
    * À côté de Template, choisissez Edit dans le menu déroulant
      * Dans la zone de texte, supprimez le motif qui existe
      * Tapez le préfixe de nom de fichier suivi d'un trait de soulignement "_" (ex soviet_)
      * Dans la section Numéro, choisissez Séquence # (00001) et Insérer
      * Le modèle devrait aimer quelque chose comme: "soviet_ Sequence # (00001)
      * Cliquez sur Terminé
      * Cliquez sur OK

### Installation de la batterie légère et de la télécommande TTL Flash

Sur batterie:
* Vérifiez que les lumières sont branchées dans le pack de batterie
* Allumez le bloc batterie
* Mettre le canal sur le pack de batterie sur 1
* Appuyez sur SYNC jusqu'à ce que vous réglez AIR
* Réglez les niveaux d'éclairage à 8 (commencez par 8, puis déplacez-vous vers le haut ou vers le bas pour régler au besoin)

Sur TTL Flash Remote:
* Tournez TTL Flash Remote ON
* Réglez le canal sur 1 (ou le même canal sur le pack de batterie)
* Régler MODE à MAN

### Prendre des photos

* D'abord, prenez une photo avec le Passeport ColorChecker
* Commencez à filmer chaque affiche
  * Mont poster
  * Prendre une photo
  * Enregistrez le LAN local (numéro à l'arrière de l'affiche) dans le champ "Copier le nom" dans la section Metadonnées
  * Répétez jusqu'à ce que toutes les affiches soient photographiées

### Fin de la prise de vue

* Mettre le capuchon d'objectif sur l'objectif de la caméra
* Supprimer la caméra du trépied
* Vérifiez les batteries sur la caméra et TTL Flash Remote - doivent-elles être chargées?
* Éteignez l'appareil photo et TTL Flash Remote
* Retirer et charger (caméra) ou remplacer (TTL Flash Remote) des piles si nécessaire
* Éteignez le pack de batterie légère
* Appuyez sur le bouton blanc sur la batterie légère pour décharger la puissance restante
* Débranchez les câbles lumineux de la batterie légère
* Retirez la batterie de la batterie légère et chargez

### Post-traitement (dans Lightroom)

Dans l'onglet Développer, recadrer les images et redresser

Créer un profil de contrôle couleur pour la session
* Exporter l'image avec Color Checker to Desktop en tant que DNG
  * Sélectionnez l'image
  * Dans le menu Fichier, choisissez Exporter
  * Paramètres:
    * Exporter vers: Bureau
    * Format de l'image: DNG
  * Cliquez sur le bouton Exporter (cela sauvegardera l'image de référence sur votre bureau)
* Logiciel de passeport OpenCheck ColorChecker
* Faites glisser et déposez l'image dans la fenêtre Passport de ColorChecker
  * Attendez que le profil soit chargé
  * Cliquez sur le bouton "Créer un profil"
  * Nommez le nouveau profil avec le nom de la session (ex soviet001)
* Fermer le passeport ColorChecker
* Fermer et réouvrir Lightroom pour charger le nouveau profil

Appliquer le profil ColorChecker à toutes les images en session
* Open Lightroom, sélectionnez l'onglet Développer
* Sélectionnez toutes les images en session
* Dans la section Calibration de l'appareil photo, choisissez le profil que vous venez de créer dans le menu déroulant pour appliquer à toutes les images sélectionnées (par ex. Soviet001)

Exporter le lot d'images en TIFF
* Sélectionnez toutes les images dans la session en cours
* Dans le menu Fichier, choisissez Exporter
* Paramètres:
  * Sous Exporter l'emplacement, choisissez la destination pour exporter des fichiers (Bureau ou un lecteur externe), cochez "Mettre dans un sous-dossier" et donnez un nouveau dossier à un nom
  * Sous Attribution de fichier, cochez "Renommer vers:" et choisissez Modifier dans le menu déroulant
  * Dans la fenêtre de l'Éditeur de modèle de nom de fichier, ajoutez "Nom de fichier_Copy Name" à l'éditeur de modèle à l'aide des boutons Insertion (voir l'image ci-dessous), puis sélectionnez Terminé
  * Dans la section Paramètres du fichier, définissez l'extension de fichier sur TIFF
  * Exportation

Donner au lecteur externe le nouveau lot d'images à l'équipe de métadonnées
Terminé!