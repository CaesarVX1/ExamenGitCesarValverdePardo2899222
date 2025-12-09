# Backend del Proyecto – FastAPI

## Instalación
pip install -r requirements.txt

## Ejecución
python -m uvicorn main:app --reload

## Endpoints disponibles
- GET /students
- GET /students/{id}

## Testing 
python -m pytest

## Docker
docker build -t daw-backend .
docker run -p 8000:8000 daw-backend

## CI/CD – GitHub Actions
Workflows ubicados en backend/.github/workflows/
- backend-test.yml
- backend-docker.yml

Requiere secrets:
- DOCKERHUB_USERNAME
- DOCKERHUB_TOKEN

# Ejercicio 8 del Examen - César Valverde Pardo
Resultado del log --graph --oneline: 930638e

# Logs ejercicio 10 César
* d516b45 (HEAD -> main, rama1_CesarValverde) Commit Ejercicio 8 cambios en MD
* f806deb Ejercicio 8
* 930638e (origin/main, origin/HEAD, rama2_CesarValverde) Primer Commit BackEnd
* 7867224 first commit

