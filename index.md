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
Dans un premier temps sélectionnez "Activer le service web" et cliquez sur enregistrer afin d'activer le service.

Afin que le service web puisse fonctionner, vous devez générer/régénérer un fichier .htaccess.
Toujours dans le back-office, rendez vous dans l'onglet "Outils/Générateurs" puis cliquez sur "Générer le fichier .htaccess"

Retournez dans "Outils/Service Web"
Cliquez sur "Nouveau", vous accédez à la page de permission et de définition de la "Clé".
Cliquez sur "Générer", cela vous générera une clé d'authentification
C'est grâce à cette clé d'authentification qu'il sera possible d'accéder au service web.
Ensuite vous pouvez créer des droits pour chacunes des ressources auxquels vous souhaitez accéder.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/auction-online/webservice/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
