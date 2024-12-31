# DIO_LAB_AI900_OCR

[FR]

Ce dépôt est un laboratoire faisant partie du cours de préparation pour l'examen AI-900 de Microsoft, organisé par Digital Innovation One.  
Ici, la technologie d'IA a été utilisée pour la reconnaissance de texte dans les images, connue sous le nom d'OCR, ainsi que la fonctionnalité Image Caption, disponible sur le site [Azure AI Vision Studio](https://portal.vision.cognitive.azure.com/demo/image-captioning).  
Le dépôt contient deux dossiers : **Inputs** et **Outputs**.

## _Inputs_
Contient les images utilisées pour les tests.  
La première image, _cmd.png_, est une capture d'écran d'un terminal de commande. L'objectif pour cette image est de reconnaître tous les textes et codes (le cas échéant) présents dans l'image.  
La deuxième image, _arquitetura.png_, est un brouillon d'un cours de troisième cycle. L'objectif ici est d'identifier les textes et esquisses écrits par le professeur dans une modélisation d'architecture réseau.

## _Outputs_
Contient les fichiers `.json` générés par le **Vision Studio**, divisés en _caption_ et _ocr_.

## Résultats
### OCR
La reconnaissance de texte dans l'image _cmd.png_ a été exécutée avec succès, car l'IA a réussi à identifier toutes les zones contenant des caractères. Cependant, pour l'image _arquitetura.png_, certaines zones n'ont pas pu identifier les textes écrits par le professeur en raison d'une mauvaise écriture, ce qui, à mon avis, est tout à fait compréhensible.

### Caption
Pour les deux images, des descriptions concises ont été générées, parfaitement conformes à leur contenu.

[EN]

This repository is a laboratory that is part of the preparation course for Microsoft's AI-900, promoted by Digital Innovation One.  
Here, AI technology was used for text recognition in images, known as OCR, as well as the Image Caption feature, available on the [Azure AI Vision Studio](https://portal.vision.cognitive.azure.com/demo/image-captioning).  
There are two folders inside the repository: **Inputs** and **Outputs**.

## _Inputs_
Contains the images used for testing.  
The first image, _cmd.png_, is of a command prompt. The goal with this image is to recognize all the text and code (if applicable) within the image.  
The second image, _arquitetura.png_, is a draft from a postgraduate lecture. The goal here is to identify the texts and drafts written by the professor in a network architecture modeling.

## _Outputs_
Contains the `.json` files generated by **Vision Studio**, divided into _caption_ and _ocr_.

## Results
### OCR
The text recognition in the _cmd.png_ image was successfully executed, as the AI was able to identify all the areas containing characters in the image. However, for the _arquitetura.png_ image, some areas failed to recognize the text written by the professor due to poor handwriting, which, in my opinion, is entirely understandable.

### Caption
For both images, concise captions were generated, perfectly aligned with their content.
