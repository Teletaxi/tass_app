# v1.241121.1
Fonctionnalités:
  - Ajoute un bouton pour avoir un détail des bénéficiaire dans les prescriptions papier et électronique.
  - Une colonne détail du trajet à été ajouté dans la liste des prestations des trajets.
  
Correction de bug:
  - Calcul des lots pour les factures B2 et Sefi.

# v1.241120.1
Correction de bug:
  - L'annulation/correction de facture, se réalise sans erreur.

# v1.241115.1
Ajout de fonctionnalités:
  - Implémentation des note au niveau des prescriptions, trajets, prestations et factures.
  - Lors de la fermeture du logiciel TASS, une requête de déconnexion de l'utilisateur est automatiquement envoyé, évitant ainsi les sessions ouvertes d'utilisateurs ayant leur logiciel TASS fermé.

# v1.241113.1
Ajout de fonctionnalités:
  - Génération de tarification pour les prestations en groupe.
  - Possibilité de modifier les trajets en groupe depuis la page manager prestation.

Correction de bug:
  - Les dates et identifiants ATMP s'effacent correctement lors de la sauvegarde de la prescription.
  - La génération des bordereaux de télétransmission est réparée.

# v1.241031.3
Correction du menu de l'application et ajout du "Note de mise à jour".

# v1.241031.2
Correction de l'affichage de la liste des trajets/prestations pour les prescriptions. Elle s'affiche de nouveau correctement.

# v1.241031.1
Correction sur la construction des factures B2 à télétransmettre. 
Les dates AT et les dates de naissance lunaire sont correctement formatées pour les requêtes des webservices.
