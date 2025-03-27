python -m venv venv
venv\Scripts\activate

uvicorn main:app --reload
uvicorn main:app --reload --port 8080
