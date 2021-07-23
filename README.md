# Créer une application web avec django et react.js
Ce projet est une initiation à django et react en utilisant le service REST.

Comment créer une application de gestion de tâche avec Django et React?

# Introduction

Dans ce tutoriel, vous allez créer une application Tde gestion de tâche en utilisant Django et React.
React est un framework JavaScript pour développer des SPA (applications monopage). Il dispose d'une documentation solide et d'un écosystème dynamique qui l'entoure.
Django est un framework Web Python qui simplifie les pratiques courantes dans le développement Web. Django est fiable et dispose également d'un écosystème dynamique de bibliothèques stables prenant en charge les besoins de développement communs.

Pour cette application, React sert de frontal ou de framework côté client, gérant l'interface utilisateur et obtenant et définissant des données via des requêtes au backend Django, qui est une API construite à l'aide du framework Django REST (DRF).
Cette application permettra aux utilisateurs de créer des tâches et de les marquer comme terminées ou incomplètes.

# Conditions préalables

Pour suivre ce tutoriel, vous devrez :

    # Installer et configurer un environnement de programmation local pour Python 3
    
    1) Installation de python 3
    sudo apt-get update
    sudo apt-get install python3.8
    python --version
    python3 --version

    2) Installation de pip pour python 3
    sudo apt update
    sudo apt-get install python3-pip
    pip3 --version
    
    sudo apt install python3-pip
    sudo apt install python3-venv
    
    python3.6 -m venv my_env
    source my_env/bin/activate
    pip install django

    
    # Installez Node.js et créez un environnement de développement local
    
    sudo apt-get install -y curl
    curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
    sudo apt-get install -y nodejs

    création de projet react:
    npx create-react-app frontend
    cd frontend
    npm start
    npm install bootstrap@4.6.0 reactstrap@8.9.0 --legacy-peer-deps
    npm install axios@0.21.1
  
  Sources:
  https://www.django-rest-framework.org/
  
  A propos de l'auteur:
        A.Marc Debazi
        Developpeur full Stack
        backend: Python -java -PHP
        frontend: React.js et Vue.js
  
  
    

 

