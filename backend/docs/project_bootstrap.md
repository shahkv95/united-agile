# Bootstrapping Python FastAPI project for backend

## Steps

1. Go to the root directory of the project and create a directory called as backend.

```
mkdir backend && cd backend
```

2. Setup virtual environment

```
PIPENV_VENV_IN_PROJECT=true pipenv shell
```

3. Install fastapi and uvicorn

```
pipenv install fastapi 'uvicorn[standard]'
```

4. Create a main.py and follow the steps from here https://fastapi.tiangolo.com/#create-it
5. Setup rest of the other directories

```
mkdir src && touch src/README.md
mkdir tests && touch tests/README.md
mkdir docs && touch docs/README.md
touch setup.py
```

The FastAPI project is bootstrapped.
