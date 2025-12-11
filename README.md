# 🚗 LandRide - Plateforme de Mobilité Durable

Ce projet a été réalisé dans le cadre de la SAÉ 1.05 / 1.06 (IUT Informatique - Université de Lille). Il s'agit d'un prototype fonctionnel (Maquette HTML/CSS) d'un service de mobilité interne pour l'entreprise **Landfall**.

## 👥 Équipe

* **Romain Lefebvre** (Chef de projet)
* **Paul Rucelle**
* **Luca Magro**
* **Baptiste Morin**

## 📝 Contexte du Projet

L'objectif est de proposer une solution web pour réduire l'empreinte carbone des collaborateurs de l'entreprise **Landfall**. Le site permet de :
* Proposer et réserver des trajets en covoiturage.
* Louer des véhicules éco-responsables (vélos, trottinettes, voitures électriques).
* Gérer son profil et consulter ses "Eco-Points".

L'entreprise choisie étant un studio de jeux vidéo (**Landfall Games**), nous avons opté pour une charte graphique "Dark Mode" moderne, reprenant les codes visuels du gaming et de l'identité de l'entreprise.

## 🚀 Installation et Utilisation

Ce site est une maquette statique (**HTML5 / CSS3** uniquement). Il ne nécessite aucune installation de serveur ou de base de données.

1.  Téléchargez ou clonez le dossier du projet.
2.  Ouvrez le fichier **`index.html`** dans n'importe quel navigateur web récent (Firefox, Chrome, Edge).
3.  La navigation est entièrement simulée via des liens HTML.

### 🔐 Identifiants de test (Fictifs)

Pour simuler la connexion à l'espace membre, vous pouvez utiliser n'importe quelles données dans les formulaires, ou utiliser les identifiants de démonstration suivants :

* **Utilisateur** : `admin`
* **Mot de passe** : `admin`

## 🎨 Choix de Conception

* **Design** : Utilisation d'un fond sombre (`#050D17`) pour le confort visuel et pour coller à l'image "Tech/Gaming" de Landfall.
* **Simulation** : Des pages de confirmation (ex: `confirmation_trajet.html`) ont été créées pour simuler le retour visuel après la soumission des formulaires.

## 📂 Architecture du site

* `index.html` : Page d'accueil publique.
* `recherche.html` : Simulation des résultats de recherche de trajets.
* `location.html` : Page de location de véhicules.
* `/compte/` : Dossier contenant toutes les pages de l'espace connecté (Tableau de bord, Messagerie, Publication...).
* `/legal/` : Dossier contenant les pages juridiques (CGU, RGPD, Mentions légales).
* `/css/` : Feuilles de styles (`base.css` pour le layout, `style.css` pour le design).
* `/img/` : Images et ressources graphiques locales.

---
*Projet universitaire - Année 2025-2026*
