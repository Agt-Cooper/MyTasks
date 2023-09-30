# MyTasks

## How to build

Cloner ce repository dans un emplacement local de votre machine.

### Préparer l'environement de développement :

Ouvrez le terminal à la racine du projet et créer l'environnement virtuel ;

```
python -m venv .env
source .env/bin/activate
```

Note: Le script activate à exécuter peut différer selon votre shell.

Pour plus d'information, se référer à la documentation de venv.

### Installer les paquets Python requis :

```
pip install -r requirements.txt
```

### Lancer l'application
```
./manage.py runserver
```
Le site web est accessible à l'adresse http://127.0.0.1:8000/.

Pour plus d'information sur le script manage, consulter la documentation officielle de Django.
