# Fraude detection for a transport company.
je suis en charge d’analyser un fichier source, reçu de la part d’un partenaire, dans l’objectif de détecter les potentiels fraudeurs.
l’employé a pour mission de s’assurer que le transport de marchandise d’un point d’escale jusqu’au client final s’est passé sans moindre souci.
Le processus de chargement de la marchandise par le transporteur  se déroule selon les étapes suivantes :
![image](https://user-images.githubusercontent.com/45856375/138857171-fab2d538-bb4b-4087-8543-cea82885aa4c.png)

Lors de son processus d’audit habituel, le recruteur a initié un contrôle en lot. Pour se faire, il a vérifié le poids total de la marchandise en provenance de l’import avec la somme de la marchandise chargée par camion. Il a constaté un écart important.

Afin de mener une enquête approfondie, votre recruteur a demandé les données saisies par son partenaire spécialisé dans l’exploitation des terminaux et des quais portuaires. En retour, Il a reçu un fichier contenant les champs suivant :
Num_escale : 	Numéro du navire chargé de marchandise,
Num_véhicule : 	Numéro du transporteur,
Num_Remorque : 	Numéro de la remorque accrochée au véhicule,
Num_client :		Numéro du client,
Date_entrée :	La date de l’entrée du transporteur au pont bascule,
Heure_entrée :	L’heure de la prise du poids (à vide) au niveau du pont bascule,
Pont_entrée :	Numéro du pont à l’entrée,
Pont_sortie :		Numéro du pont de bascule pour la prise du poids du camion chargée ,
Date_sortie :		La date de la prise du poids (chargé) au niveau du pont,
Heure_sortie :	L’heure de la prise du poids (chargé) au niveau du pont,
Poids_Vide :		Le poids du camion vide,
Poids_chargé :	Le poids du camion chargé de la marchandise,
Produit :		La marchandise,
Votre recruteur a identifié une liste de points de vigilance :
Le camion ne s’est pas correctement positionné 
Le transporteur se présente à un pont bascule pour la mesure de poids à vide et change de pont pour la mesure du poids chargé
Le transporteur  cache des objets lourds lors du premier pesage à vide et se débarrasse du poids ou objets sur le chemin de son chargement.


