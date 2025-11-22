1. Charte graphique proposée
1.1. Positionnement

Tu es :
Développeur Full Stack Django + Développement IA, avec un background business.
Donc on veut quelque chose :

Tech / moderne

Pro (recruteurs, ESN, boîtes produit)

Lisible, pas “dark hacker illisible”

Je te propose un thème clair avec un accent bleu “tech”.

1.2. Palette de couleurs

Tu peux les mettre en variables CSS (:root { --color-primary: ... }).

Couleur principale (Primary) : #2563EB

Boutons, liens importants, accents

Couleur secondaire : #06B6D4

Badges, tags de techno, hover secondaire

Fond principal : #F9FAFB

Arrière-plan global

Fond des sections :

Section normale : #FFFFFF

Section “mise en avant IA” : #EFF6FF (légèrement bleuté)

Texte :

Texte principal : #0F172A

Texte secondaire / descriptions : #6B7280

Effets / bordures :

Bordure cartes : #E5E7EB

Ombre douce : 0 10px 30px rgba(15, 23, 42, 0.08)

Radius global : 12px

1.3. Typographie

Utilise des Google Fonts :

Titres : Poppins ou Montserrat

font-weight: 600 ou 700

Texte courant : Inter

font-weight: 400 / 500

Hiérarchie :

h1 : 32–40px, gras

h2 : 26–30px

h3 : 20–22px

Texte : 16px

Légendes / tags : 12–14px

1.4. Rythme / espacements

Définis une échelle d’espacement (en rem ou px) :

4px, 8px, 16px, 24px, 32px, 48px

Entre sections : 64px–80px

Dans une carte projet : 24px de padding

2. Nouvelle structure de page

On garde une Single Page mais mieux organisée.

2.1. Header / Navbar

Contenu :

Logo texte : Toufik Chaari

Sous-titre : Développeur Full Stack & IA

Menu avec ancres :

À propos

Compétences

Projets

Développement IA

Parcours

Contact

Specs :

Navbar fixe en haut (background blanc légèrement transparent)

Ombre légère

Scroll smooth vers les sections (scroll-behavior: smooth;)

2.2. Section Hero (Accueil)

Objectif : en 3 secondes, comprendre qui tu es.

Contenu :

Titre :
"Développeur Full Stack & IA"

Sous-texte :

"Spécialisé en Django, APIs REST et projets de Développement IA (8 projets), avec une double compétence technique & business."

Boutons :

[Voir mes projets] (ancre vers portfolio)

[Télécharger mon CV] (lien PDF GitHub)

Layout :

À gauche : texte

À droite : illustration simple / avatar / icône dev (même un simple SVG ou photo pro)

2.3. Section Compétences

Regrouper les compétences actuelles par bloc.

Blocs suggérés :

Backend & API

Python, PEP8, Django, Django REST Framework

Frontend

HTML5, CSS, JavaScript, React

Data & IA (nouvelle partie importante)

Python scientifique : NumPy, Pandas

Machine Learning : scikit-learn, éventuellement PyTorch / TensorFlow si tu les utilises

MLOps / pratiques : notebooks, expérimentation, versioning de modèles/données

Base de données

PostgreSQL, SQL

DevOps & Outils

Docker, CircleCI, GitHub Actions (si tu veux), Heroku

Outils / QA

Tests unitaires, intégration, Postman

UI :

Chaque bloc = carte avec :

Titre

Liste de techno sous forme de badges (petits pills colorés)

2.4. Section Projets (généraux)

On prend tes projets actuels (Webscrapping, JustStreamIt, Litrevu, Softdesk API, Oc Lettings, etc.).

Organisation recommandée :

Titre : "Projets de développement"

En dessous : filtres simples (optionnel) :

Tous | Web | Backend | API | Tests | Refactorisation

Layout : grille responsive (2 colonnes desktop, 1 colonne mobile)

Chaque carte projet :

Titre du projet

Tag(s) : Django, API, Tests, etc.

3–4 lignes max :

Contexte

Objectif

Résultat / valeur

Boutons :

[Code GitHub]

éventuellement [Démo]

2.5. Section Développement IA – 8 projets

C’est la nouvelle grosse partie à mettre en avant.

Structure

Titre : "Développement IA – 8 projets"

Sous-texte :

"Projets de Machine Learning et IA appliqués (modélisation, optimisation, data engineering et industrialisation)."

Puis une grille de 2x4 cartes (8 projets IA).

Pour chaque projet IA, tu peux suivre un format standard :

Titre (exemples de formats) :

Prédiction de [X] avec [technique]

Détection / classification de [X]

Optimisation de [X] via ML

Tags :

Python, scikit-learn, Classification, NLP, Time Series, etc.

En 3 lignes max :

Contexte / dataset

Technique principale

Ce que le modèle apporte (performance, automatisation, aide à la décision)

Liens :

[Notebook] / [Repo GitHub]

Exemple de carte (structure texte) :

Prédiction de churn clients d’un service SaaS
Tags : Python, scikit-learn, Classification, Pandas
Modèle supervisé entraîné sur un historique de clients pour prédire le risque de churn. Analyse exploratoire, feature engineering et évaluation (ROC AUC, matrice de confusion).
[Code GitHub]

Même si tes 8 projets n’existent pas encore tous, tu peux déjà prévoir la structure et remplir au fur et à mesure.

2.6. Section Parcours / Diplômes

Reprendre ce que tu as déjà, mais mis en forme :

Timeline verticale :

2024 — Développeur Concepteur Logiciel (RNCP niveau 6, OpenClassrooms)

2016 — Master of Science in International Business (Bac+5)

2012 — Licence en commerce international (Bac+3)

2.7. Section Contact

Simple mais pro :

Texte :

"Disponible pour des opportunités en développement Full Stack, API et IA."

Boutons :

[Email]

[GitHub]

éventuellement [LinkedIn]