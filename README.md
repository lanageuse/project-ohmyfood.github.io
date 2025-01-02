# Projet OhMyFood Paris

OhMyFood est un site de présentation et de réservation de restaurants à Paris, mettant en avant des menus raffinés et des établissements d'exception. Ce projet utilise **Sass** pour la gestion des styles et inclut des dépendances externes pour les icônes et les polices.

## Structure du Projet

```plaintext
├── assets
│   ├── images         # Contient les images utilisées dans le projet
│   └── css            # Fichiers CSS générés par Sass
├── restaurants        # Pages HTML pour chaque restaurant
├── sass               # Structure des fichiers Sass
│   ├── abstracts      # Variables, mixins et fonctions globales
│   ├── base           # Styles de base (reset, typographie, etc.)
│   ├── components     # Composants réutilisables (boutons, formulaires, etc.)
│   ├── layouts        # Dispositions générales (header, footer, etc.)
│   └── main.scss      # Fichier Sass principal qui importe tous les autres
├── index.html         # Page d'accueil
├── README.md          # Documentation du projet
└── .gitignore         # Fichiers et dossiers ignorés par Git
```

## Technologies Utilisées

- HTML5 : Structure des pages.
- Sass : Préprocesseur CSS pour une gestion optimisée et modulaire des styles.
- FontAwesome : Pour les icônes utilisées dans l'interface.
- Google Fonts : Shrikhand et Roboto

## Installation et Configuration

### 1. Cloner le dépôt 
```plaintext
git clone https://github.com/lanageuse/project-ohmyfood.github.io.git
cd ohmyfood
```

### 2. Installer Sass : Si Sass n'est pas installé sur votre machine, installez-le avec npm ou gem :

```plaintext
npm install -g sass
```
### 3. Compiler les Styles :

```plaintext
sass --watch sass/main.scss assets/css/main.css
```


