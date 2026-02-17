# v1.260217.1
Corrections:
 - Lors de la mise en correction d'une facture et qui est demandé de recopier les prestations cela ce fait correctement.
 - La prise en compte des péages et des simultanés depuis le détail des trajets sont correctements reportés dans la facturation.
 - La convertion automatique des PDF non-couleur n'est plus systématique si le PDF original est deja en noir et blanc ou en nuance de gris.

Fonctionnalités:
 - On peut maintenant demander l'itinéraie depuis Google Maps, comme pour ViaMichelin.
 - Un nouvel écran pour les factures du jour par défaut (ou par période aussi) est maintenant disponible.

# v1.260203.1
Corrections:
 - Modification de l'url qui permet le géocodage des adresses.

# v1.260129.1
Corrections:
 - L'affinage des trajets tient bien compte des trajets "retour", en inversant le départ et l'arrivée.

# v1.260128.1
Corrections:
 - Le PDF de facture ce génère correctement s'il n'y a pas de géolocalisation.

# v1.260127.1
Corrections:
 - Tentative de correction des noemie qui ne sont pas traités.

# v1.260123.1
Fonctionnalités:
 - Ajout, le péage peut être renseigné au niveau des détails des trajets (Dates, heures, équipages) et ainsi être utilisé dans la tarification lors de la génération des tarifs.

# v1.260122.1
Corrections:
 - Dans les retours NOEMIE une erreur était remontée du à un traitement de certaines parts AMC et provoquaient un arrêt des traitements du NOEMIE en question et des suivants, cela est maintenant corrigé.
 - Dans les pages des factures des impayées et des factures non envoyées, tout les liens sont fonctionnelles. Ils redirigent bien vers les prescriptions, prestations, bénéficiaires et les différentes AMO/AMC.

Fonctionnalités:
 - Lors de la saissie des kilomètres, une nouvelle fonctionnalité est présente, un boutton d'affinage des périodes des trajets de façon visuel (avec une carte) améliore l'expérience de recherche des différentes positions GPS.

# v1.260108.1
Corrections:
 - Affichage immédiat du bénéficiaire dans la prescription papier.

# v1.260106.1
Corrections:
 - En tant que société certifiée (GPS - tarification majorée), lorsque la facture est établie en mode B2, le calcul du montant de la courte distance est en phase avec la distance renseignée et non avec la distance GPS.
 - Amélioration des chargements des pages du planning.

# v1.251221.1
Fonctionnalités:
 - Ajout de pages pour la comptabilités.

# v1.251219.1
Corrections:
 - Le traitement des importations de transport depuis TELAMBU ou TELETAXI ce passe correctement.
 - Ignorer les positions GPS pour la facturations des trajets, ce fait correctement.

# v1.251210.1
Fonctionnalités:
 - Il est maintenant possible d'ignorer les positions GPS pour les trajets dans la facturation.
 - Dans le détails des trajets, là où sont renseignés les dates et horaires des trajets, un double clique dans la zone de l distance parcourue pour le renseigner directement avec la distance GPS.
 - Un filtrage par lettre à été ajouté dans la liste des bénéficiaires.

# v1.251118.1
Corrections:
 - Mise en standby de la recherche bénéficiaires depuis la page d'edition d'une prescription, il y a de fort ralentissement pour certains clients.

# v1.251103.1
Corrections:
 - Report des km GPS dans le service "valider".

# v1.251031.1
Corrections:
 - Dans calculer montant prestation et controler recevabilité, il y a une correction sur la détermination de l'utilisation des KM GPS.

# v1.251029.1
Corrections:
 - Correction de l'indicateur jour/nuit/dimanche/ferié.

# v1.251027.1
Corrections:
 - L'affichage reporte correctement les Km GPS.
   
# v1.251024.1
Corrections:
 - Le test de géolocalisation qui empêche la facturation en tarification socle est corrigé.

# v1.251021.1
Fonctionnalités:
 - Externalisations des positions GPS, ce qui permet une grande amélioration des délais de réponse pour les calculs des prestations (Générer les tarifs).

# v1.250928.1
Fonctionnalités:
 - A partir du 01/10/2025 avec la nouvelle convention, oblige d'utiliser les km GPS remontés par les boîtiers GPS comme km de facturation. Cette modification est appliquée lorsque le niveau de certification de géolocalisaion est comprit de 3 à 5.

# v1.250916.1
Corrections:
 - Traitement correct sur les prestations SEFi/B2/SECU qui ont été générées par une correction de facture, ce chargent correctement.
 - Apres avoir sauvegarder une prestation LIBRE, les informations sont correctement remontées pour facturer ces prestations.

# v1.250907.1
Corrections:
 - Prise charge des factures "libre" dans le chiffre d'affaire.

# v1.250830.1
Corrections:
 - Le blocage qui empéchait la facturation en SEFi et B2 des prestations d'une prescription est maintenant corrigé.
 - Il y a une amélioration lors de la génération des calculs.

# v1.250827.1
Corrections:
 - Le libellé de commanditaire dans la page du détail du transport commanditaire est correctement restitué.
 - La facturation B2 n'est plus bloquée pour les prestations d'une prescription, ce bug est appararu lors de l'implémentation de la facturation des transports commanditaires.

# v1.250826.1
Fonctionnalités:
 - Listing des commanditaires, pour ainsi récupérer le commanditaire du transport en création.
 - Inversion possible entre les adresses de départ et d'arrivée.

Corrections:
 - Lors de la sauvegarde, les tests des champs sont maintenant corrigés.

# v1.250824.2
Fonctionnalités:
 - Implementation complète des commanditaires et de la facturation des commanditaires.
 - Ajout de nouveaux tableaux de facture pour l'éditeur de lettre.
 - Pour la page des détails des trajets, les équipages n'apparaissement plus après la date d'inactivité. Sélection de date multiples pour la génération des dates plus les multiples transports.

Corrections:
 - Dans le détail des trajets, il est possible de sauvegarder une plus grande partie des données en une fois. Un message erreur lors du test des chevauchements peut apparaitre, mais cela ne bloque plus le processus de sauvegarde des données. Cette erreur sera corrigée dans une prochaine version du logiciel.

# v1.250527.1
Fonctionnalités:
 - Mise à jours des informations pour le recueil d'activité (RMG).

# v1.250507.2
Corrections:
 - Le test du triplet de l'AMO n'empêche plus la sauvegarde de la prescription s'il n'y a aucune donnée pour la couverture AMO.

# v1.250507.1
Corrections:
 - Dans les factures PDF sécu ne reprennez pas la couverture AMO par défaut de la prescription.

# v1.250506.2
Corrections:
 - Le test du triplet (les numéros régime, caisse, centre) de l'AMO sont maintenant correctement prit en compte lors de l'importation des trajets depuis TELEAMBU/TELETAXI. 
 
# v1.250506.1
Corrections:
 - Amelioration du test de l'equipage de la voiture lors des importations des trajets depuis les trajets de TELEAMBU/TELETAXI.
 - Isolement du code qui met en erreur la page du personnels de la société lors de son affichage.

# v1.250505.1
Corrections:
 - Feuille de route ne reste plus bloqué lors du chargement de la page.

# v1.250502.1
Corrections:
 - Répartition des parts AMO, AMC et RAC corrigées.

# v1.250430.1
Corrections:
 - Rétablissement de la facturation à 100% sur l'assuré (reste à charge à 100%).

# v1.250429.2
Corrections:
  - N'autorise plus la sauvegarde d'une AMO si le triplet n'est pas complet.

# v1.250429.1
Corrections:
  - Réaffichage du libellé de l'AMO dans les factures PDF.

# v1.250428.1
Corrections:
  - Le passage de la tarification majorée à la tarification socle conserve maintenant la majoration nuit/férié pour la courte distance.

Fonctionnalités:
  - Ajouts dans les variables des lettres, le numéro d'adhérent AMC du bénéficiaire, dans les taleaux des factures on y retrouve une colonne pour les dates des trajets.

# v1.250427.1
Corrections:
  - L'indicateur de période dans la norme B2 pour le dimanche apparait bien en férié (valeur F).
    
Fonctionnalités:
  - Mise à jour majeur pour les lettres, maintenant il est possible d'editer des lettres comme sur un éditeur de texte.
  - Les tableaux prescriptions, factures, chiffre d'affaire et journal des ventes proposent une exportation plus poussée de leurs données. Prise en charge de différent formats CSV, XML, JSON et voir PDF par l'impression PDF. De plus le partage par mail est proposé directement.

# v1.250407.1
Fonctionnalités:
  - Implémentation des annuaires des prescripteurs et établissements de santé.

# v1.250318.1
Corrections:
  - Amélioration de la récupération de l'annuaire des établissements de santé.

# v1.250317.1
Fonctionnalités:
  - Implémentation d'un annuaire des établissements de santé.

Corrections:
  - Mise à jour du calcul des chiffres d'affaire des sociétés.

# v1.250311.1
Corrections:
  - Après avoir fait l'appel au service Calculer montant prestation, le service ne renvoi pas la ligne de KM si elle vaut 0 euros, donc le logiciel la rajoute pour faire une comparaison correcte.

# v1.250309.3
Corrections:
  - Lors de la génération des tarifications pour les séries, les péages sont maintenant conservés. De plus lors de l'appel au service 'Calculer montant prestation' la comparaison avec les différents péages s'effectue correctement. 

# v1.250309.2
Corrections:
  - Remplacement des '.' par des ',' pour les montants des prix dans l'export CSV.

# v1.250309.1
Fonctionnalités:
  - Export du journal des ventes au format Excel CSV.

# v1.250305.1
Corrections:
  - Amélioration du calcul des numéros de lots.
  - Lors de la génération du bordereau de télétransmission, une facture non créée en amont pouvez être vierge à ce moment là, ceci est corrigé.

Fonctionnalités:
  - Les personnels et les véhicules inactif, ce statut est maintenant remplacé par une date à partir de laquelle ce dernier est inactif. Celà permet de proposer ce véhicule/personnel ou non à dans une sélection.

# v1.250225.1
Corrections:
  - Récupération correct des AMC dans les trajets.
  - Amelioration des calculs des lots B2, SEFI pour la singularité des lots SCOR.

# v1.250220.1
Fonctionnalités:
  - Calcul des CA automatique à interval régulier pour un gain de rapidité significatif lors de la récupération du chiffre d'affaire.

# v1.250205.1
Fonctionnalités:
  - Ajout des dates des transports pour les factures.

# v1.250131.1
Corrections: 
  - Lors de calculer montants prestation avec la MSA, il y a un retrait de l'abattement à 0.
  - Dans la fiche bénéficiaire, la récupération des informations bénéficiaire depuis le service de la sécurité sociale ce fait correctement.
  - Quand un nouveau bénéficiaire est créé depuis la page des prescriptions, la liste des bénéficiaires se mets à jours.

# v1.250128.1
Corrections:
  - Lors de la recherche de factures par numéro de lot, le filtrage ce fait correctement.
  - Si l'on créer un bénéficiaire depuis une création de prescription, le bénéficiaire est correctement renseigné dans la prescription en cours de création.

# v1.250127.1
Fonctionnalités:
  - Implémentation d'une recharche par numéro de lot.

# v1.250124.1
Fonctionnalités:
  - Il est maintenant possible de charger plusieurs fichiers NOEMIE en même temps pour les traiter.

# v1.250122.2
Fonctionnalités:
  - Ajout des totaux des facturés et perçus dans les factures.
  - Ajout d'une configuration pour les anciennes boites mail RSP de Téléambu.

# v1.250121.1
Fonctionnalités:
  - Amélioration de la lisibilité des factures non émises et non payées.

# v1.250120.1
Correction:
  - Le nombre de malade dans un transport est correctement défini lors d'un transport simultané en VSL.

Fonctionnalités:
  - Prise en charge d'une date de facture ou de transport pour le chiffre d'affaire.

# v1.250116.1
Corrections:
  - Indication des périodes Jour, Nuit, Férié fontionnement correctement dans la norme B2.

Fonctionnalités:
  - Ajout de détail dans la feuille de route au sujet des trajets. Exemeple affichage du prix du trajet.

# v1.250105.2
Corrections:
  - Sur les factures PDF TS report des montants AMC et RAC sur la part assuré.

Fonctionnalités:
  - Les lettres AMC sont complétées par les numéros AMC et adhérent.

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
