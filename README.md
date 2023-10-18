# Test Technique : Création d'une Application Web de Nouvelles

Créer une application web qui affiche les dernières nouvelles provenant de l'API News API.
L'application doit permettre aux utilisateurs de voir les titres, les descriptions et les liens vers les articles complets.

## Tâches :

- Configuration du Projet :

  - Créez un nouveau projet React avec TypeScript.
  - Installez les dépendances nécessaires pour effectuer des requêtes API.

- Intégration de l'API :

  - Utilisez l'[endpoint](https://newsapi.org/v2/top-headlines) pour récupérer les dernières nouvelles.
  - Utilisez votre propre clé API. (Inscrivez-vous sur [News API](https://newsapi.org/) pour obtenir une clé gratuite.)

- Conception de l'Interface Utilisateur :

  - Affichez les nouvelles sous forme de liste.
  - L'information se charge au fur et à mesure que l'utilisateur scroll la page ou créez un système de pagination
  - Chaque élément de la liste doit afficher l’image, le titre, la description et un lien vers l'article complet.

- Gestion des Erreurs :

  - Gérez les erreurs qui peuvent survenir lors de l'appel à l'API.
  - Affichez un message d'erreur convivial si les données ne peuvent pas être récupérées.

- Styles et Mises en Page :

  - Ajoutez des styles CSS pour rendre l'application agréable à regarder et facile à utiliser.
  - Assurez-vous que l'application est responsive et fonctionne bien sur les appareils mobiles.
  - Indication pour inspiration :
    - <https://edition.cnn.com/>
    - <https://meatpacking-district.com/>
  - Bonus: utilisation d’un préprocesseur css

- Tests unitaires :
  - Écrivez des tests unitaires pour les composants de votre application.
