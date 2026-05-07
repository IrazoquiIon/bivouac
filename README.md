# Bivouac Pyrénées & Pays Basque

Une page web statique présentant une sélection de 9 circuits de randonnée et bivouac dans les Pyrénées et le Pays Basque. Le projet est conçu comme un guide interactif pour les randonneurs, du débutant au confirmé.

## 🏕️ Concept

L'objectif de ce projet est de centraliser des idées de randonnées en boucle sur 2 à 5 jours, avec un focus sur le bivouac. Tous les itinéraires proposés partent et arrivent au même point, simplifiant la logistique pour les randonneurs.

La page est conçue pour être visuellement agréable, facile à utiliser et informative, avec toutes les données nécessaires pour préparer une sortie.

## ✨ Fonctionnalités

- **Liste de 9 circuits** : Chaque circuit est présenté sous forme de carte avec les informations essentielles (durée, distance, dénivelé).
- **Filtres dynamiques** : Filtrez les circuits par niveau (débutant, modéré, difficile), région (Pyrénées, Pays Basque) ou durée.
- **Vue détaillée** : Cliquez sur une carte pour ouvrir une modale avec toutes les informations pratiques :
    - Itinéraire détaillé jour par jour.
    - Suggestions de spots de bivouac.
    - Informations sur l'accès, le balisage, les points d'eau.
    - Conseils pratiques et liens externes (traces GPS, météo, refuges).
- **Checklist Matériel** : Une section dédiée à l'équipement indispensable pour un bivouac, avec des priorités (indispensable, très utile, utile).
- **Règles du Bivouac** : Un rappel des règles de base du bivouac en France et dans les parcs nationaux.
- **Numéros d'urgence** : Un bandeau avec les numéros essentiels en cas de problème en montagne.

## 🛠️ Stack Technique

Ce projet est volontairement simple et performant, sans dépendances à des frameworks lourds.

- **HTML5** : Structure sémantique.
- **CSS3** : Design moderne avec variables CSS, Flexbox, Grid et animations.
- **JavaScript (Vanilla)** : Toute la logique est gérée en JavaScript natif (ES6+).
    - Les données (circuits, matériel, règles) sont stockées dans des tableaux d'objets directement dans le fichier `index.html`.
    - Le rendu de l'interface (cartes, modales) est généré dynamiquement à partir de ces données.

## 🚀 Utilisation

Aucune installation n'est requise. Il suffit de cloner le dépôt et d'ouvrir le fichier `index.html` dans votre navigateur web.

## ✏️ Contribution

Pour ajouter ou modifier du contenu (un circuit, un item de matériel, etc.), il suffit de modifier les constantes JavaScript (`CIRCUITS`, `MATERIEL`, `REGLES`) situées dans la balise `<script>` à la fin du fichier `index.html`.

Les contributions pour améliorer le code, le design ou ajouter de nouvelles fonctionnalités sont les bienvenues via des Pull Requests.
