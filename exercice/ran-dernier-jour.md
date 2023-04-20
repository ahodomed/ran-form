## Consignes

Vous allez devoir intégrer trois maquettes :

- `formulaire.png`
- `cv-bleu.png`
- `cv-rouge.png`

Vous allez devoir réaliser l'intégration de ces trois maquettes dans deux (et seulement deux)  fichiers séparés :

- `formulaire.phtml`
- `cv.phtml`

Vous allez devoir remplir les champs dynamiques de la page `cv.phtml` avec des données récoltées dans le formulaire de la page `formulaire.phtml`.

Le formulaire de `formulaire.phtml` contient un choix de couleur pour votre CV, vous allez devoir utiliser une condition pour changer le thème couleur de votre page.

Pour afficher les listes, vous allez devoir utiliser des boucles.

## Informations

### Police de caractère

```HTML
<link rel="preconnect" href="https://fonts.googleapis.com">  
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>  
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400;600;800&display=swap" rel="stylesheet">
```

```CSS
font-family: 'Montserrat', sans-serif;
```

### Couleurs

```CSS
/*  
  
rouge : #b50604;  
bleu : #24527c;  
blanc fond : #fefefe;  
blanc : white;  
gris : #bababa;  
  
*/
```

### Listes

Il existe 3 types de listes en HTML, `<ul>`, `<ol>` et `<dl>` . N'oubliez pas les `<dl>`.