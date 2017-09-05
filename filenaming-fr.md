---
layout: page
title: Filenaming et organisation
lang: fr
ref: filenaming
order: 100
---

Des structures bien organisées et des noms de fichiers cohérents facilitent le suivi et l'organisation des fichiers et sont nécessaires aux flux de travail IDEP. Lors de la nomination et de l'organisation des fichiers, vous devez être cohérent et ordonné pour que les fichiers soient facilement identifiés et triés correctement. Configurez une structure de répertoire claire et une convention de dénomination de fichier qui suit un modèle comme `identificateur de projet + regroupement (comme date ou volume) + un type d'identifiant unique`.

### Structurer les données
Pensez soigneusement à la meilleure façon de structurer vos données dès les premiers stades de votre projet. Essayez de garder une hiérarchie peu profonde (pas de nidification profonde des dossiers). Les répertoires individuels peuvent être regroupés selon un certain nombre de critères différents, y compris la date, le format, la sous-collection ou les catégories qui ont le sens le mieux pour votre projet.

Quelques exemples de structures de données comprennent l'organisation par:

* format (texte, images, fichiers son, etc.)
* genre (interviews, affiches, journaux, cartes postales, etc.)
* unité (journal année / volume, boîte d'archives)

### Noms de fichiers
Les noms de fichiers devraient vous permettre d'identifier les fichiers avec précision à partir du nom. Choisissez un format pour nommer vos fichiers et l'utiliser de manière cohérente. Incluez dans le nom les informations qui vous permettront de distinguer vos fichiers les uns des autres, en suivant un modèle comme `identificateur de projet + regroupement (comme date ou volume) + un type d'identifiant d'élément '. Notez comment les éléments passent du général au spécifique. Parmi les éléments à considérer, mentionnons:

* Identificateur de projet ou de collection: nom, acronyme, numéro de collection, etc.
* Groupement: année, volume (journal), série d'archives ou boîte, etc.
* Identificateur d'article: page, numéro (journal), séquence, identifiant unique (ISBN, OCLC, marque d'étagère)

** Quelques bonnes pratiques: **

* Tous les caractères spéciaux tels que `~! @ - # $% ^ & * (); <>? , [] {} '"| |` doit être évité. Respectez les chiffres, les lettres romaines (de préférence les minuscules) et les sous-titres `_`.
* N'utilisez pas d'espaces ou de tirets. Certains logiciels ne reconnaissent pas les noms de fichiers avec des espaces, et les noms de fichiers avec des espaces doivent être placés entre guillemets lors de l'utilisation de la ligne de commande.
* Les alternatives aux espaces incluent:
  * Des soulignements, p.ex. `file_name.xxx`
  * Pas de séparation, par ex. `filename.xxx`
  * Étui de chameau, où la première lettre de chaque section de texte est en majuscule, p. `fileName.xxx`
* Un bon format pour les désignations de date est `YYYY_MM_DD` ou` YYYY_MM`. Ce format garantit que tous vos fichiers restent dans l'ordre chronologique, même pendant de longues années.
* Gardez les noms de fichiers aussi courts que possible car les noms de fichiers longs ne fonctionnent pas bien avec tous les types de logiciels. Inclure uniquement les informations nécessaires pour trouver et comprendre le fichier. Viser à être significatif et bref. Rappelez-vous: le nom du fichier n'est pas l'endroit où enregistrer les métadonnées descriptives!
* Lorsque vous utilisez un système de numérotation séquentielle, utilisez un nombre suffisant de zéros avancés pour plus de clarté et assurez-vous que les fichiers trient dans l'ordre séquentiel. Par exemple, utilisez `0001, 0002, ... 0010, 0011 ... 0100, 0101, etc. au lieu de `1, 2, ... 10, 11 ... 100, 101, etc.

### Autres astuces

Inclure un fichier `README.txt` dans le répertoire qui explique votre format de dénomination ainsi que les abréviations ou codes que vous avez utilisés. Cette documentation sera utile pendant le projet ou l'expérience, et aussi dans le futur.