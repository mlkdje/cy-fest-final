 Gestion de Salles pour Festival
Ce projet est un système de gestion des salles pour les organisateurs de festivals. Il permet de créer, modifier, afficher et réserver des salles de concert, avec différentes catégories de sièges.
Fonctionnalités
- Mode Manager:
- Ajouter une nouvelle salle
- Modifier les détails d'une salle existante - Afficher les détails des salles
- Mode Festivalie :
- Afficher les détails des salles disponibles - Réserver un siège dans une salle
Structure du Code
Le projet est écrit en C et se compose des structures et fonctions suivantes :
Structures
-Siege : Représente un siège avec son état de réservation et son prix.
- Salle : Contient les détails d'une salle, y compris les sièges, le nombre de rangées, l'artiste et l'heure de fin du concert.
- GestionSalles : Gère un ensemble de salles et le nombre total de sièges.
Fonctions Principales
- afficherMenu : Affiche le menu principal.
- saisieDonneesSalle : Saisit les données pour une nouvelle salle.
- creerSalle : Crée une nouvelle salle.
- modifierdetailsalle : Modifie les détails d'une salle existante.
- afficherDetailSalle : Affiche les détails de toutes les salles.
- reserverSalle : Permet aux festivaliers de réserver des sièges.
- estConcertTermine : Vérifie si le concert est terminé.
- afficherPlanSalle : Affiche le plan de la salle avec l'état de chaque siège. - sauvegarderSalle : Sauvegarde les détails des salles dans un fichier.

 Installation
Pour compiler et exécuter ce projet, suivez ces étapes :
1. Clonez le dépôt : ```
git clone https://github.com/votre-utilisateur/votre-repo.git
```
2. Accédez au répertoire du projet :
```
cd votre-repo ```
3. Compilez le code : ```
gcc -o gestion_salles main.c
```
4. Exécutez le programme :
``` ./gestion_salles ```
Utilisation Mode Manager
1. Choisissez "1" dans le menu principal pour entrer en mode Manager. 2. Suivez les instructions pour ajouter, modifier ou afficher les salles.
Mode Festivalier
1. Choisissez "2" dans le menu principal pour entrer en mode Festivalier.
2. Suivez les instructions pour afficher les détails des salles ou réserver un siège.
Contributions
Les contributions sont les bienvenues ! Veuillez suivre ces étapes pour contribuer :
1. Forkez le dépôt.
2. Créez une branche de fonctionnalité (`git checkout -b feature/AmazingFeature`). 3. Commitez vos modifications (`git commit -m 'Add some AmazingFeature'`).
4. Poussez vers la branche (`git push origin feature/AmazingFeature`).
5. Ouvrez une Pull Request.
Licence
Distribué sous la licence MIT. Voir `LICENSE` pour plus d'informations.

 
