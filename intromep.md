## Tutoriel des WebServices (REST)

REST est un style d’architecture qui repose sur le protocole HTTP. On accède à une ressource (par son URI unique) pour procéder à diverses opérations supportées nativement par HTTP.
Il y a principales opérations:

    - GET: pour lire l'élément.
    - POST: pour en créer un.
    - PUT: pour le modifier.
    - DELETE: pour le supprimer.


###  Mise en place - Création des accès dans le Back Office

Dans un premier temps nous allons créer un accès au service web.
Pour ce faire il suffit d'aller dans votre Back Office dans l'onglet "Outils/Service Web".
Sélectionnez "Activer le service web" et cliquez sur enregistrer afin d'activer le service.

Afin que le service web puisse fonctionner, vous devez générer/régénérer un fichier .htaccess.
Toujours dans le back-office, rendez vous dans l'onglet "Outils/Générateurs" puis cliquez sur "Générer le fichier .htaccess"

Retournez dans "Outils/Service Web"
Cliquez sur "Nouveau", vous accédez à la page de permission et de définition de la "Clé".
Cliquez sur "Générer", cela vous générera une clé d'authentification
C'est grâce à cette clé d'authentification qu'il sera possible d'accéder au service web.
Ensuite vous pouvez créer des droits pour chacunes des ressources auxquels vous souhaitez accéder.
Le bouton de gauche vous permet de définir l'ensemble des droits pour une ressource donnée.
```markdown