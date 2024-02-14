
# Django 5.x.x with TailwindCSS Boilerplate

This project is a boilerplate for Django 5.x.x, featuring a simple Class-Based View (CBV) for displaying a page. It's designed as a quick starting point for Django projects needing a foundational structure with a CBV.

## Features

- Django 5.x.x compatibility
- TailwindCSS 3.x.x
- Class-Based View for displaying a page
- Basic Django project setup
- Example HTML template

## Prerequisites

Before you begin, ensure you have Python 3.8 or later installed on your system. Django 5 requires Python 3.8 or higher.

## Installation

Follow these steps to set up the project on your local machine.

1. **Clone the Git repository:**

2. **Create a virtual environment:**
   ```bash
   python3 -m venv .venv
   ```

3. **Activate the virtual environment:**
   - On Windows:
     ```cmd
     .\venv\Scripts\activate
     ```
   - On Unix or MacOS:
     ```bash
     source .venv/bin/activate
     ```

4. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Environment Setup

Before running the project, you need to set up the environment variables.

1. Create a `.env` file in the core project directory.
2. Add the following lines with your Django secret key and any other necessary environment variables:
   ```
   SECRET_KEY=your_secret_key_here
   DEBUG=True
   ALLOWED_HOSTS=127.0.0.1
   ```

3. **Start the development server:**
   ```bash
   python manage.py runserver
   ```

4. Open a browser and navigate to `http://127.0.0.1:8000/` to see the page served by the Class-Based View.




## Version Française :


# Modèle Django 5.x.x avec TailwindCSS

Ce projet est un modèle pour Django 5.x.x, présentant une vue basée sur une classe (CBV) simple pour l'affichage d'une page. Il est conçu comme un point de départ rapide pour les projets Django nécessitant une structure de base avec une CBV.

## Caractéristiques

- Compatibilité Django 5.x.x
- TailwindCSS 3.x.x
- Vue Basée sur une Classe pour l'affichage d'une page
- Configuration de projet Django de base
- Exemple de template HTML

## Prérequis

Avant de commencer, assurez-vous d'avoir Python 3.8 ou une version ultérieure installée sur votre système. Django 5 nécessite Python 3.8 ou supérieur.

## Installation

Suivez ces étapes pour configurer le projet sur votre machine locale.

1. **Clonez le dépôt Git :**

2. **Créez un environnement virtuel :**
   ```bash
   python3 -m venv .venv
   ```

3. **Activez l'environnement virtuel :**
   - Sur Windows :
     ```cmd
     .\venv\Scripts\activate
     ```
   - Sur Unix ou MacOS :
     ```bash
     source .venv/bin/activate
     ```

4. **Installez les dépendances :**
   ```bash
   pip install -r requirements.txt
   ```

## Configuration de l'environnement

Avant d'exécuter le projet, vous devez configurer les variables d'environnement.

1. Créez un fichier `.env` dans le répertoire du projet principal.
2. Ajoutez les lignes suivantes avec votre clé secrète Django et toute autre variable d'environnement nécessaire :
   ```
   SECRET_KEY=votre_clé_secrète_ici
   DEBUG=True
   ALLOWED_HOSTS=127.0.0.1
   ```

3. **Démarrez le serveur de développement :**
   ```bash
   python manage.py runserver
   ```

4. Ouvrez un navigateur et naviguez jusqu'à `http://127.0.0.1:8000/` pour voir la page servie par la Vue Basée sur une Classe.
