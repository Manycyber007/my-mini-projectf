Partie 1:
Gestion d'une liste d'objets :
➢ Créez une classe ListePersonnes qui contient une liste d'objets de type
Personne.
➢ Ajoutez une méthode ajouter_personne(nom, age) pour ajouter une nouvelle
personne à la liste et enregistrer ces informations dans une table "Personnes" de
la base de données MySQL.
➢ Ajoutez une méthode afficher_personnes() pour afficher les détails de toutes les
personnes dans la liste en récupérant les données depuis la table "Personnes" de
la base de données MySQL.
Recherche dans une liste d'objets :
➢ Ajoutez une méthode rechercher_personne(nom) à la classe ListePersonnes qui
recherche une personne par son nom dans la table "Personnes" de la base de
données MySQL et affiche ses détails si elle est trouvée.
Filtrage des personnes par âge :
➢ Ajoutez une méthode filtrer_personnes_par_age(min_age, max_age) à la classe
ListePersonnes qui récupère les détails des personnes dont l'âge est compris
entre min_age et max_age depuis la table "Personnes" de la base de données
MySQL et les affiche.
Gestion d'une file d'attente :
➢ Créez une classe FileAttente pour gérer une file d'attente de personnes.
➢ Ajoutez une méthode ajouter_personne_en_attente(nom) pour ajouter une
personne à la file d'attente et enregistrer son nom dans une table "FileAttente"
de la base de données MySQL.
➢ Ajoutez une méthode supprimer_personne_de_attente() pour supprimer la
première personne de la file d'attente en récupérant son nom depuis la table
"FileAttente" de la base de données MySQL et l'afficher.
Priorisation dans la file d'attente :
➢ Modifiez la classe FileAttente pour qu'elle puisse gérer des personnes
prioritaires.
➢ Ajoutez une méthode ajouter_personne_prioritaire(nom) pour ajouter une
personne prioritaire à la file d'attente et enregistrer son nom dans la table
"FileAttente" de la base de données MySQL.
➢ Modifiez la méthode supprimer_personne_de_attente() pour supprimer en
priorité une personne prioritaire si elle existe dans la table "FileAttente" de la
base de données MySQL, sinon supprimer la première personne normale.
Simulation d'un système de réservation :
➢ Créez une classe SalleCinema pour gérer les réservations dans une salle de
cinéma.
➢ Ajoutez une méthode reserver_place(nom, place) pour réserver une place pour
une personne et enregistrer cette réservation dans une table "Reservations" de
la base de données MySQL.
➢ Ajoutez une méthode afficher_places_reservées() pour afficher les places
réservées en récupérant les données depuis la table "Reservations" de la base de
données MySQL.
Partie 2:
Gestion de la capacité de la salle :
➢ Ajoutez une méthode nombre_places_disponibles() à la classe SalleCinema
pour afficher le nombre de places disponibles en consultant la table
"Reservations" de la base de données MySQL et calculer les places
disponibles.
➢ Ajoutez une vérification dans la méthode reserver_place(nom, place) pour
s'assurer qu'il reste des places disponibles dans la salle en consultant la table
"Reservations" de la base de données MySQL avant de réserver.
Filtrage des réservations par personne :
➢ Ajoutez une méthode filtrer_reservations_par_personne(nom) à la classe
SalleCinema pour afficher les réservations faites par une personne spécifique
en récupérant les données depuis la table "Reservations" de la base de données
MySQL et en filtrant par nom.
Annulation des réservations :
➢ Ajoutez une méthode annuler_reservation(nom) à la classe SalleCinema pour
annuler toutes les réservations faites par une personne spécifique en supprimant
les données correspondantes dans la table "Reservations" de la base de données
MySQL.
Gestion des places spéciales :
➢ Modifiez la classe SalleCinema pour qu'elle puisse gérer des places spéciales
pour les personnes handicapées.
➢ Ajoutez une méthode reserver_place_speciale(nom) pour réserver une place
spéciale pour une personne handicapée et enregistrer cette réservation dans la
table "Reservations" de la base de données MySQL.
