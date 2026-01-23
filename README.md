# 🎶 O Sol Sound

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

> **O Sol Sound** est un blog musical dynamique dédié à l'univers chaleureux et rythmé de la **Bossa Nova**.

## 🎯 Contexte du Projet

Ce projet a été réalisé dans le cadre du **Marathon Web de 36 heures**.
Le défi : concevoir et développer une application complète en équipe de **7 étudiants**, en mêlant développement backend/frontend, gestion de projet et création de contenu, le tout sous une forte contrainte de temps.

**Objectifs atteints :**
* Déploiement d'une architecture MVC propre.
* Gestion d'une base de données relationnelle.
* Intégration d'une interface utilisateur responsive.

---

## 🛠️ Stack Technique

* **Backend** : Laravel 10, PHP 8.2
* **Base de données** : SQLite (pour la légèreté et la rapidité de déploiement)
* **Frontend** : HTML5, CSS3, Blade Templating
* **Outils** : Git & GitHub (Workflow collaboratif), Trello (Gestion de projet)

---

## ✨ Fonctionnalités Principales

* 🎵 **Catalogue d'articles** : Présentation d'artistes, d'albums et d'histoires de la Bossa Nova.
* 🔍 **Navigation par catégories** : Filtrage dynamique des contenus.
* 📱 **Interface Responsive** : Adapté aux mobiles et desktops.
* 🛠️ **Back-Office (Admin)** : Gestion des articles (CRUD) *[Optionnel : retire si pas fait]*.

---

## 🚀 Installation et Lancement

Si vous souhaitez lancer le projet localement :

1.  **Cloner le dépôt**
    ```bash
    git clone [https://github.com/ton-pseudo/o-sol-sound.git](https://github.com/ton-pseudo/o-sol-sound.git)
    cd o-sol-sound
    ```

2.  **Installer les dépendances PHP**
    ```bash
    composer install
    ```

3.  **Configurer l'environnement**
    ```bash
    cp .env.example .env
    php artisan key:generate
    ```

4.  **Préparer la base de données (SQLite)**
    * Sur Linux/Mac : `touch database/database.sqlite`
    * Sur Windows : Créez manuellement un fichier vide nommé `database.sqlite` dans le dossier `database`.

5.  **Lancer les migrations**
    ```bash
    php artisan migrate
    ```

6.  **Démarrer le serveur**
    ```bash
    php artisan serve
    ```

Rendez-vous sur `http://localhost:8000` !

---

## 👥 L'Équipe

Projet réalisé par une équipe de 7 étudiants passionnés, incluant :
* **Shun Debrez** - *Développeur Backend & Chef de Projet* [BUT INFORMATIQUE]
* **Lou Debeare** - *Développeuse Backend* [BUT INFORMATIQUE]
* **Romain Thibaut** - *Développeur Backend* [BUT INFORMATIQUE]
* **Lucas Ternel** - *Développeur Front-End* [BUT MMI]
* **Clément Desbuisson** - *Développeur Front-End* [BUT MMI]
* **Léonie Dahin** - *Développeuse Front-End & Direction Artistique* [BUT MMI]
* **Laurine Bross** - *Communication, Direction Artistique & Anglais* [BUT MMI]

---

## 📸 Aperçu

*(Ajoute ici une ou deux captures d'écran de la page d'accueil ou d'un article pour donner envie)*
