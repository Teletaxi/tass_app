# v1.241230.2
Corrections:
  - Dans la génération des factures PDF, s'il y a plus qu'un trajet aller - retour, c'est le premier trajet et le dernier trajet qui sont prit en compte dans le détail de la facture.

# v1.241230.1
Corrections:
  - La regénération des annexes PDF comprend bien tous les trajets facturés.
    
# v1.241227.1
Fonctionnalités:
  - Il est maintenant possible de dupliquer une prescription.

# v1.241226.1
Corrections:
  - Génération des annexes ce fait correctement.

# v1.241223.1
Corrections:
  - Les générations de factures / annexes vierge sont à présent corrigées.
  - Certaines factures pdf ne présentent pas les bonnes données, ceci est à présent corrigé.

# v1.241220.1
Fonctionnalités:
  - Il est possible de faire basculer une nature de trajet Aller/Retour, tout en supprimant la prestation tarifaire, tant que le trajet n'est pas facturé.
  - Il est maintenant possible de regénérer en groupe les PDF factures et annexes.

# v1.241218.1
Correction de bug:
  - Les dates dans les annexes et les factures correspondent bien au premier transport et au dernier transport.

Fonctionnalités:
  - Il n'est pas nécessaire d'enregistrer manuellement les AMOs et de les compléter. C'est automatique.

# v1.241216.1
Correction de bug:
  - Génération des tarifs sur les trajets retour seulement.

# v1.241212.1 
Fonctionnalités:
  - Impléménetation de protection, d'avertissement et d'information sur les destinataires des remboursements de la Sécurité Sociale.

# v1.241210.2
Correction de bug:
  - Génération de la géolocalisation, couvertures AMO et AMC des tarifications des trajets en serie.

# v1.241210.1
Correction de bug:
  - Le service acquerir prescription ne renvoi plus la prescription de test. 

# v1.241207.1
Correction de bug:
  - Lors de la génération des tarifications en série, la complétion des information de géolocalisation se réalise correctement.
  - La génération des majorations de nuit se font correctement.

# v1.241206.1
Correction de bug:
  - Les partages pour les factures et les pjs se font correctement.

# v1.241204.1
Correction de bug:
  - Déterminer les tiers payants pour l'AMO/AMC quand on génère les tarifications pour les séries.

Fonctionnalités:
  - Ajout du partage des prescriptions et des factures par mail.

# v1.241127.1
Correction de bug:
  - Correcion de la génération des tarifications pour les prestations en serie.

# v1.241125.2
Fonctionnalités:
  - Les trajets importés sont ignorés pour la vérification des chevauchements.

# v1.241125.1
Correction de bug:
  - Correction de la vérification des chevauchements.
  - La répartition du temps lors du calcul de la tarification ce fait correctement.

# v1.241122.1
Correction de bug:
  - Affichaage des trajets commanditaire dans la feuille de route.
  - Les trajets importé ne sont plus prient en compte pour le test des chevauchements.

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
