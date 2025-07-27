# IvoireFood

**IvoireFood** est une plateforme web de commande et de découverte de plats traditionnels ivoiriens et ouest-africains. Elle permet aux utilisateurs de parcourir un menu riche, d’ajouter des plats à leur panier, de passer commande et de découvrir la culture culinaire de la Côte d’Ivoire.

## Fonctionnalités principales

- Parcours du menu par régions et catégories (entrées, plats, desserts, boissons…)
- Ajout de plats au panier (stocké côté client via LocalStorage)
- Gestion du panier (ajout, suppression, validation)
- Authentification utilisateur (connexion/déconnexion)
- Page À propos, politique de confidentialité, contact, etc.
- Interface moderne avec Tailwind CSS et responsive design

## Structure du projet

```
Projet_ivoire_food/
│
├── ivoire_food.php           # Page d'accueil principale (menu, panier, etc.)
├── panier.html               # Page du panier
├── login.php                 # Page de connexion
├── A_propos/
│   └── about.php             # Page À propos
├── menu/
│   └── menu.html             # Menu détaillé (si présent)
├── politique/
│   └── index.html            # Politique de confidentialité
├── style/
│   ├── css/
│   │   └── about.css         # Styles personnalisés
│   └── js/
│       ├── panier.js         # Gestion du panier (JS)
│       ├── ivoire_food.js    # JS général
│       └── about.js          # JS pour la page À propos
├── ivoire_food/              # Images des plats
│   └── ...                   # (alloco.jpeg, escargot.jpeg, etc.)
└── logo.png                  # Logo du site
```

## Installation & Lancement

1. **Prérequis** :

   - Serveur web local (XAMPP, WAMP, MAMP, etc.)
   - PHP 7.x ou supérieur

2. **Installation** :

   - Placez le dossier `Projet_ivoire_food` dans le répertoire `htdocs` (pour XAMPP).
   - Démarrez Apache (et MySQL si besoin).

3. **Accès** :
   - Ouvrez votre navigateur et allez sur :  
     `http://localhost/Projet_ivoire_food/ivoire_food.php`

## Technologies utilisées

- **PHP** (gestion de session, authentification)
- **HTML5/CSS3**
- **Tailwind CSS** (via CDN)
- **JavaScript** (gestion du panier, interactions)
- **FontAwesome** (icônes)
- **LocalStorage** (stockage du panier côté client)

## Licence

Ce projet est sous licence MIT.  
Vous êtes libre de l’utiliser, le modifier et le distribuer, sous réserve de conserver la mention de copyright ci-dessous dans toutes les copies ou parties substantielles du projet.

```
MIT License

Copyright (c) 2024 IvoireFood

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Auteurs

- Jean-Pierre Yavo (Fondateur & CEO)
- Aïcha Touré (Chef Exécutif)
- David Konan (Responsable Marketing)


NB: je compte améliorer le site en ajoutant de nouvelle fonctionnalitées et d'autres pages ainsi que apporter des amélioration sur certaines pages. Si vous souhaitez  m'aide a le faire je vous serai reconnaissant 
    - Améliore le design de la page de confidentialité
    - Faire correspondre toutes les pages a la page principale 

## Contact

- Email : ivoirefood@email.com
- Téléphone : +225 07.08.00.00.00 / +225 07.07.99.00.01

---

\*\*© 2024 IvoireFood – Tous droits
