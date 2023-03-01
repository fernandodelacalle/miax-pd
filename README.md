# pd-mia

# Contenidos

## 1. Principios de desarrollo
- Introducción a GIT.
- Conceptos básicos de redes.
- Introducción a la Terminal.
- Python Virtual Enviroments.
- Desarrollo de APIs en python con Fast API.
- Logging en Python.

## 2. Principios de desarrollo: Docker
- Docker
- Desarrollo desde Docker en vscode.
- Kubernetes.

# Otros
- Para convertir las diapositivas de md a pdf usar el comando:
```bash
docker run --rm --init -v $PWD:/home/marp/app/ -e LANG=$LANG marpteam/marp-cli **/*.md  --pdf --allow-local-files
```