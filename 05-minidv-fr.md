---
layout: page
title: Transfert MiniDV
lang: fr
ref: minidv
permalink: /minidv-fr
---

## Liste d'équipement

1. Modèle de caméra vidéo numérique Sony HVR-M25AU (et cordon d'alimentation secteur)
![](../assets/img/minidv/video_deck.png)

2. Câble FireWire 800/400 à 9 broches / 6 broches
! [] (../ assets / img / minidv / firewire.png)

3. Adaptateur Apple Thunderbolt to FireWire
! [] (../ assets / img / minidv / firewire_adapter.png)
** Pour les réparations nécessaires sur bande (4-6): **

4. Ruban d'épissage 1/4 "
! [] (../ assets / img / minidv / splicing_tape.png)

5. Tournevis Phillips 1.4mm
! [] (../ assets / img / minidv / screwdriver.png)

6. Rasoir à un seul bord ou ciseau pointu
! [] (../ assets / img / minidv / razor.png)! [] (../ assets / img / minidv / scissor.png)
<br> ** Pour nettoyer les têtes vidéo lorsqu'elles sont bouchées (7-8): **

7. Des écouvillons sans peluches (pour nettoyer les têtes vidéo)
! [] (../ assets / img / minidv / swabs.png)

8. Alcool isopropylique (99%) (pour nettoyer les têtes vidéo)
! [] (../ assets / img / minidv / alcohol.png)

## MiniDV Background

MiniDV est un format vidéo introduit en 1995. Sa petite taille et sa qualité visuelle le rendent particulièrement populaire sur le marché des consommateurs et de l'éducation. Chaque bande contient environ 13 Go pendant environ une heure de vidéo. Le temps d'exécution est en moyenne d'environ 60 minutes si enregistré en mode standard (SP) ou 90 minutes en lecture prolongée (LP).

! [] (../ assets / img / minidv / tape.png)

Comme d'autres cassettes vidéo en format DV, la bande magnétique à l'intérieur d'une cassette MiniDV mesure 1/4 pouce de large, de sorte que toutes les réparations peuvent être réalisées avec une bande d'épissure de 1/4 pouce, généralement utilisée dans le travail audio. Bien que les réparations physiques soient rarement requises, les techniques de réparation seront brièvement revues à la fin de cette documentation.

! [] (../ assets / img / minidv / tape2.png)

Les cassettes MiniDV peuvent être jouées dans la plupart des ponts DVCAM. La plate-forme Sony que vous recevez (modèle HVR-M25AU) dispose d'un mécanisme à cassette double taille qui accepte les cassettes vidéo numériques et numériques de taille mini et standard, DVCAM et DV. Remarque: Certaines cassettes MiniDV de la marque Panasonic ne peuvent pas être lues sur les ponts Sony.

L'encodage stocké sur le ruban MiniDV peut être la vidéo numérique (DV), DVCAM ou HDV. Le signal vidéo de tous ces formats est compressé ou «perturbe». Le signal audio pour DV n'est cependant pas compressé. Le taux d'échantillonnage (nombre d'échantillons audio par seconde) et la profondeur du bit (nombre de bits utilisés pour transporter les données dans chaque échantillon d'audio) peuvent varier.

DV prend en charge les modes suivants d'audio à modulation de code impulsion linéaire (PCM):
4 canaux à 12 bits avec un taux d'échantillonnage de 32 kHz
2 canaux à 16 bits avec un taux d'échantillonnage de 48 kHz
2 canaux à 12 bits mode 32 kHz
2 canaux à 16 bits à 44.1 kHz (similaire aux CD)
Taux d'échantillonnage:

! [] (../ assets / img / minidv / sampling_rate.png)

DVCAM est une version semi-professionnelle de DV et peut être reproduit à un rythme plus rapide.
La vidéo HDV est codée avec un schéma de compression H.262 / MPEG-2 et son audio stéréo est codé avec le schéma de compression MPEG-1 Layer 2. L'audio et la vidéo compressés sont incorporés dans un flux de transport MPEG-2.
Le rapport d'aspect des flux vidéo MiniDV peut être standard (4: 3) ou grand écran (16: 9):

! [] (../ assets / img / minidv / ratio.png)

Pour ce projet, nous allons capturer le flux de données vidéo sur une connexion FireWire qui conservera les données sous sa forme plus précise, y compris ses métadonnées d'origine. FireWire est également appelé i.LINK. Le transfert du flux sur d'autres sorties vidéo traditionnelles telles que le composant ou la sortie S-vidéo modifierait les données.

! [] (../ assets / img / minidv / s-video.png)

## Transfert du contenu MiniDV

Le logiciel que vous utiliserez pour transférer le contenu DV et DVCAM s'appelle AVCVideoCap. C'est un outil dans Apple FireWire SDK Version 26, un kit de développement logiciel pour Mac OS. AVCVideoCap est un excellent candidat pour la conservation de MiniDV car il transmet les signaux de données brutes sans appliquer de modifications à l'image ou au son. Le fichier maître brut résultant peut être encodé sur n'importe quelle variété de fichiers dérivés.

Cependant, AVCVideoCap ne capture pas le contenu HDV. Pour les bandes contenant HDV, vous utiliserez DVHSCap. Les deux flux de travail seront démontrés ci-dessous.

! [] (../ assets / img / minidv / avcvideo.png)

** Raccorder les câbles et l'alimentation: **
  1. Branchez le cordon d'alimentation fourni dans le connecteur AC IN à l'arrière de la platine Sony HVR-M25AU DV. Branchez l'autre extrémité dans votre source d'alimentation.
  2. Branchez le câble FireWire 800/400 à 9 broches / 6 broches dans la prise i.LINK à l'arrière de la platine DV. La connexion à 6 broches se connecte à la platine DV.
  3. Connectez la connexion FireWire 9 broches à l'adaptateur Apple FireWire Thunderbolt.
  4. Branchez l'adaptateur Thunderbolt dans votre MacBook Pro.
  5. Allumez l'unité DV avant d'allumer votre ordinateur.
    * Retournez l'interrupteur d'alimentation à l'arrière de l'appareil sur "ON".
    * Appuyez sur le bouton d'alimentation à l'avant du pont.

** Préparez votre MiniDV pour le transfert: **
  1. Assurez-vous que votre MiniDV est réglé sur «Mode sans échec» afin qu'il ne puisse pas être enregistré accidentellement.
  ! [] (../ assets / img / minidv / mode.png)
  2. Insérez votre cassette MiniDV. Introduisez doucement mais fermement la bande dans la porte de la bande.
  3. Rebranchez votre bande si elle n'est pas déjà au début de l'enregistrement.
  4. Appuyez sur "Lire" et examinez brièvement le rapport d'aspect, la vidéo et les spécifications audio. L'écran LCD situé sur