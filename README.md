# docker-fastapi-test

---

## Prerequisites
- Python 3.10 or later
- `pip` (Python package manager)
- Docker (for containerization)

---

## Install Dependencies
- python3 -m venv venv
- source venv/bin/activate    # On Windows: venv\Scripts\activate
- pip install -r requirements.txt

---

## Start the FastAPI Application
- uvicorn app.main:app --reload

---

##  Access the Application
- API Base URL: http://127.0.0.1:8000/
- Swagger UI: http://127.0.0.1:8000/docs

---
##  Build the Docker Image
- docker build -f Dockerfile.yaml -t fastapi-app .


---
##  Run the Docker Container
- docker run -d -p 8000:8000 fastapi-app


---
##  Access the Application
- API Base URL: http://127.0.0.1:8000/
- Swagger UI: http://127.0.0.1:8000/docs
---
