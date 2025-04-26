## Telechargement du projet sous Linux.

Pour telecharger le projet on a simplement besoin d'utiliser la commande:
```bash
git clone --depth=1 https://github.com/Elkatra2/Hashiwokakero_Projet_INF402
```

## Mettre en place l'environnement du traivaille.

Initialisation de l'environnement par défaut:
```bash
python3 -m venv .venv
```

Entrée dans l'environnement du python
```bash
source .venv/bin/activate
```

Telechargement de modules/bibliotheques utilisée dans le projet:
```bash
pip install -r requirements.txt
```

Si pendant le travaille on avez telecharger des nouvelle bibliotheques
```bash
pip install nom_lib # telechargement
pip freeze > requirements.txt
```

Sortie et suppression de l'environnement (optionel)
```bash
deactivate
rm -r .venv # optionel
```