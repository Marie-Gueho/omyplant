# O'My Plant! (front)
https://o-my-plant.surge.sh

## Projet de fin de formation

### Application web destinée à la gestion des plantes d'intérieur et de balcon.

Base de données participative, l'utilisateur peut choisir dans la BDD les plantes qu'il possède et les ajouter à son jardin. 
Si la plante recherchée n'existe pas encore, il peut la rajouter dans la BDD  en renseignant son nom commun, en ajoutant une photo et une description.
Lors de l'ajout d'une plante dans son espace 'Mon jardin", il récupère les informations de base (nom commun, photo, description) de la plante et de nouveaux champs sont débloqués afin de personnaliser les informations liés à sa plante (surnom, photo, fréquence d'arrosage, emplacement, exposition, taille, rempotage). Ces informations lui sont personnelles et n'impactent pas la BDD. La table plante liée à l'utilisateur héritant des informations de la table plante de la BDD, cette dernière n'est pas modifiée.
Cette première version permet à l'utilisateur enregistrer ses plantes dans son espace 'Mon jardin', il peut ainsi gérer l'ensemble de ses plantes et l'entretien propre à chacune.

Dans une version ultérieure, nous souhaitons impléter:
- un **espace admin** qui permettrait entre autre de **modérer** la BDD en supprimant ou modifiant une plante si les informations renseignées ou la photo choisie ne sont pas correctes.
- un **système de rappel** pour les arrosages avec l'implémentation de l'**API Google Calendar** afin de permettre à l'utilisateur, s'il le souhaite, d'ajouter des rappels sur son calendrier.
- **gagner en niveau**: à chaque ajout d’un certain nombre de plantes dans la BDD du site, il atteint un palier qui lui délivre un badge: planteur débutant, ami des plantes : 20, main verte : 50


Projet réalisé en équipe de 5 (3 front et 2 back) pendant 1 mois.
- 
- **semaine 1** : Réalisation du cahier des charges
              - MVP
              - User stories
              - Liste des technos
              - MCD/MLD
              - Maquette (avec Figma)

- **semaine 2 et 3** : Développement
- **semaine 4** : Débug et présentation du projet

### TECHNOS côté front:
- React (-dom, -player, -redux, -router-dom, -scripts)
- Axios
- Prop-types
- Cloudinary
- Redux
- Material UI
- Sass
- Surge

![o'my plant](https://res.cloudinary.com/piaeonia/image/upload/v1644741334/portfolio/xiwvqvuddql0r58uevpz.png)
