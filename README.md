# Reservation-system-tkinter

<img width="630" alt="Reservation-System-Tkinter" src="https://github.com/khemisse-radwane/reservation-system-tkinter/blob/main/Screenshot%202024-04-26%20090254.png">


L'objectif de ce projet est de développer une application de gestion destinée à une agence spécialisée dans la location de maisons de vacances sur des îles. Actuellement, la gestion des données se fait manuellement, ce qui entrave la capacité à extraire rapidement et efficacement des informations importantes. Pour résoudre ce problème, nous mettrons en place une base de données ainsi que des interfaces graphiques pour améliorer le service client.

# Objectif du Projet
Le but principal est de créer et de mettre en place un système d'information qui permettra à l'agence de gérer ses réservations de maisons de vacances de manière efficace. Cela englobe la conception d'un modèle entité-association, d'un schéma relationnel, de contraintes d'intégrité, de tables de base de données, ainsi que le développement d'interfaces graphiques pour l'insertion, la recherche, la modification et la suppression des données.

# Contenu du Projet
## Modèle Entité-Association (E/A):
  - Identifie les entités telles que Maison, Client et Réservation, en les distinguant clairement.
  - Établit les liens entre ces entités, comme la relation entre Client et Réservation, pour une compréhension précise des interactions.
  - Précise les caractéristiques spécifiques à chaque entité, telles que le nom de la maison, l'adresse du client, etc., pour une description détaillée.
  - Définit les clés d'identification pour chaque entité, par exemple, en utilisant l'identifiant de la maison comme clé primaire, afin d'assurer une gestion efficace et unique des données.
## Schéma Relationnel:
- Crée une représentation du modèle E/A en termes de tables relationnelles.
- Identifie les clés primaires et étrangères pour chaque table.
- Contraintes d'Intégrité:
Spécifie les règles pour restreindre les valeurs possibles des attributs.
Exemples de contraintes incluent les numéros de semaine valides pour les réservations et le tarif minimum par chambre pour les loyers.
## Tables de Base de Données:
- Crée toutes les tables nécessaires en tenant compte des contraintes définies.
- Assurez-vous que la base de données rejette les opérations invalides, telles que l'introduction d'un numéro de semaine invalide.
## Interfaces Graphiques:
- Développe des interfaces conviviales pour l'insertion, la recherche, la modification et la suppression de données.
- Les interfaces permettent aux utilisateurs d'ajouter de nouveaux clients, maisons de vacances, de rechercher des informations pertinentes, etc.
# Technologies Utilisées
- Base de données: SQLite
- Langage de programmation: Python
- Bibliothèques: Pandas, NumPy, Tkinter
