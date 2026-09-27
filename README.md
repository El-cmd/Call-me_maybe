*This project has been created as part of the 42 curriculum by vloth.*

# Call Me Maybe

Call Me Maybe est un projet Python consacré au *function calling* contraint
avec un petit modèle de langage.

## Environnement Python avec uv

Le projet nécessite Python 3.12 ou une version ultérieure. Il utilise
[`uv`](https://docs.astral.sh/uv/) pour gérer l'environnement et les
dépendances.

Installer `uv` s'il n'est pas déjà disponible :

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Créer ou synchroniser l'environnement virtuel à partir de `pyproject.toml` et
`uv.lock` :

```bash
uv sync
```

Exécuter le point d'entrée actuel du projet dans l'environnement géré :

```bash
uv run python -m src
```

L'activation manuelle de `.venv` est facultative. Si nécessaire :

```bash
source .venv/bin/activate
```

Ajouter une dépendance et mettre à jour le fichier de verrouillage :

```bash
uv add <package-name>
```
