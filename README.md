# créer un dossier  Projet_python

  gestion presence
  
## Installation

1. Clonez le dépôt : `git clone https://github.com/Liloufa224/Projet_django.git`
2. Accédez au répertoire du projet : `cd Projet_django`
3. Créez un environnement virtuel : `python -m venv env`
4. Activez l'environnement virtuel :
   - Sous Windows : `env\Scripts\activate`
   - Sous Unix ou Linux : `source env/bin/activate`
5. pip install django==4.2.7 (version 4.2.7)
6. django-admin startproject Projet_django
7. cd Projet_django
8. django-admin startapp gestion (ou gestion est le nom de l'application a creer )
9. python manage.py migrate
10. python manage.py createdsuperuser (creation de super user)
    Email address: exemplemail@gmail.com
    Password: 12345 (Ecrivez ça ne sera pa visible) il sortira(Password (again))
11. y
12. python manage.py runserver
13. ( il apparaitra dans la foulé un lien du genre htt://127.0.0.1:8000/) cliquer dessu
    il vous envera la page Django
    ou alors sur un navigateur tapper localhost/8000 tapper entrer.
ouvrez votre projet Projet_django dans vs code dépliez Project_django ,dépliez gestio
sur la branche gestionStock creer un dossier templetes dépliez creer un dossier gestion à 
nouveau (ça sera comme cela templetes\gestion)
dans gestion creer un fichier home.html (mettez quelque chose sur cette page)
en suite cous descender chercher le Settings.py ,A l'interieur vous cherchez INSTALLED_APPS=[
 en bas de 'Django.contrib.staticfile', vous mettez suivi de la virgule 'gestion', vous suivez la tendence en un mot


. Installez les dépendances : `pip install -r requirements.txt`

