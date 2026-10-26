# Portfolio de Jacob Essomba

Bienvenue sur le dépôt de mon portfolio personnel. Ce site web a été réalisé dans le cadre de ma formation à Epitech.

## 🌐 Site en ligne

Le portfolio est accessible à l'adresse suivante :
**👉 [https://jacob-essomba.github.io/Portfolio/]**

## 📁 Structure du projet

Portfolio/
├── .github/
│   └── workflows/
│       └── deploy.yml      # Configuration de GitHub Actions (déploiement automatisé)
├── assets/                 # Ressources (images, documents)
│   ├── cv.pdf              # Mon CV téléchargeable
│   └── profil.png          # Ma photo de profil
├── css/
│   └── style.css           # Feuille de style principale (Thème sombre, Responsive, BEM)
├── about.html              # Page "À propos" (Parcours, CV, Formulaire de contact)
├── projects.html           # Page principale (Présentation + Grille de projets)
└── README.md               # Documentation du projet


🛠️ Technologies et fonctionnalités utilisées

HTML5 sémantique : Structure claire et accessible (balises main, section, article, nav).

CSS3 :
Design 100% Responsive (adapté aux mobiles, tablettes et ordinateurs).
Thème sombre moderne utilisant des variables CSS (:root).
Respect de la convention de nommage BEM (Block, Element, Modifier).
Animations CSS (bandeau défilant, effets au survol).

JavaScript :
Gestion asynchrone du formulaire de contact avec l'API Fetch (évite le rechargement de la page).
Mise à jour automatique de l'année dans le pied de page.

Formspree : 
Intégration d'un service externe pour recevoir les messages du formulaire de contact par email, sans avoir besoin de créer un serveur backend (le projet est 100% front-end).

Accessibilité & SEO :
Balises alt, contrastes respectés, navigation au clavier, balises meta description (Score Lighthouse > 90).

🚀 Processus de publication (GitHub Actions)

Conformément aux consignes, la publication est entièrement automatisée.

Le fichier .github/workflows/deploy.yml utilise GitHub Actions. À chaque fois qu'une modification est poussée sur la branche main, GitHub construit et déploie automatiquement le site sur GitHub Pages, sans aucune intervention manuelle.

Pour mettre à jour le site :

Modifiez les fichiers en local.
Poussez vos changements :
bash
git add .
git commit -m "Description de la modification"
git push origin main
Attendez quelques secondes que l'onglet "Actions" de GitHub affiche une coche verte ✅. Le site est en ligne !

✍️ Auteur

Jacob Essomba
Étudiant à Epitech: Pré-MSc (3e année) puis MSc — Promo 2029

GitHub : @Jacob-Essomba
LinkedIn : Mon profil
Email : jacob.essombaekani@gmail.com

📄 Licence

Ce projet est un projet personnel et pédagogique. Le code est librement consultable à des fins d'apprentissage.

