Télécharger les dépendances:

pip install -r requirements.txt


éxecuter les tests:

pytest


Lancer l'application:

gunicorn --worker-tmp-dir /dev/shm --config gunicorn_config.py app:app
