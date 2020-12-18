# Tracks

La partie Backend d'un lecteur multimédia Web capable de lire des Track avec des Lyrics. Ces
morceaux sont organisés en Albums dans une BD servis par une API en backoffice. 

## requirements.txt

Installer Django and Django REST framework

```
pip install django
pip install djangorestframework
```
lancer l'application

```
cd Test
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

```

créer un initial user 

```
python manage.py createsuperuser
```


1-a- Concevoir une API fournissant plusieurs Web services permettant de lister les Albums

http://127.0.0.1:8000/albums

1-b- Concevoir une API fournissant plusieurs Web services permettant de lister les Tracks et leurs fichiers audio ainsi que les Lyrics:

http://127.0.0.1:8000/tracks

2- la recherche du mot "yourself" dans les Lyrics.

http://127.0.0.1:8000/search/?q=yourself


