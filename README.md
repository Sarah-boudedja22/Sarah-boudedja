#  Projet : Site E-Commerce "Azrar — Trésors Berbères"

---

##  Informations du Projet

| **Nom & Prénom** | Boudedja Sarah |
| **Groupe** | Groupe 2|
| **Date** | Novembre 2025 |

---

## Thème et Objectif du Site

### Thème choisi

Le site "Azrar — Trésors Berbères" a été conçu comme une vitrine e-commerce pour une marque fictive spécialisée dans la vente de bijoux traditionnels et artisanaux kabyles et amazighs.

L'objectif principal est de valoriser le savoir-faire ancestral, l'héritage culturel de ces pièces, et d'offrir une expérience utilisateur (UX) simple et élégante, tout en utilisant des couleurs et des motifs inspirés du désert et de la culture berbère (tons de beige, marron, or et émail).

### Structure du Site

Le projet est organisé autour de 4 pages HTML principales ,pour une navigation claire et complète :

1.  `index.html` (Accueil) : Présentation de la marque, vidéo de l'héritage culturel, produits "Coups de Cœur" et valeurs de l'entreprise.
2.  `produits.html` (Boutique) : Catalogue complet des bijoux. Chaque article permet de sélectionner la quantité via un formulaire simple.
3.  `accessoires.html` (Catalogue secondaire) : Présentation des accessoires liés aux bijoux (boîtes, pochettes, chiffons, etc.).
4.  `contact.html` (Contact) : Formulaire de contact et coordonnées de la marque.

---

##  Défis et Solutions Techniques

| Difficulté Rencontrée | Solution Mise en Œuvre |
| :--- | :--- |
| **Uniformité des Images** | **Problème :** Les images des produits n'avaient pas toutes le même format, ce qui déséquilibrait les cartes sur la page Boutique (`produits.html`). |
| | **Solution :** Utilisation d'un sélecteur CSS fort (`.page-catalogue .gallery img`) avec une hauteur fixe (`height: 180px;`) et la propriété `object-fit: cover;`. Cette combinaison force toutes les images à une taille uniforme en recadrant intelligemment le contenu, garantissant la cohérence visuelle demandée. |
| **Fonctionnalité E-commerce (Sans JavaScript)** | **Problème :** Implémenter la sélection de quantité dans le panier sans utiliser de code dynamique (JavaScript). |
| | **Solution :** Utilisation de la balise `<form action="#">` avec un bouton `type="button"` sur la page Boutique. L'utilisateur peut sélectionner la quantité, mais le bouton ne recharge pas la page (comme demandé) et ne fait pas de calcul dynamique (simulant une fonction qui serait traitée côté serveur ou par JavaScript). |
| **Gestion des Chemins de Fichiers** | **Problème :** Utilisation de majuscules ou de caractères accentués dans les chemins des dossiers/fichiers (`vidéo/présentation.mp4`), ce qui peut entraîner des erreurs sur les serveurs web. |
| | **Solution :** Renommage de tous les dossiers en minuscules et sans accent (`img/`, `video/`) pour garantir une compatibilité universelle (best practice). |

---

## Conclusion

Ce projet a permis d'appliquer les bases du HTML pour la structure sémantique et du CSS pour une mise en page. Le résultat est une vitrine numérique propre, esthétique et fonctionnelle pour la marque "Trésors Berbères".