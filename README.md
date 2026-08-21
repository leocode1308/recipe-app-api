
```markdown
# Recipe App API

A robust RESTful API for managing recipes, ingredients, and tags, built with Python, Django, and Django REST Framework using Test-Driven Development (TDD) and Docker.

---

## 🚀 Features

* **User Authentication:** Custom user model supporting email authentication and secure token-based authentication.
* **Recipe Management:** CRUD operations for recipes, including price, preparation time, tags, and ingredients.
* **Tag & Ingredient Filtering:** Endpoints to create, list, update, and filter tags and ingredients assigned to recipes.
* **Image Upload:** Dedicated endpoint to upload and manage recipe images.
* **Interactive Documentation:** Auto-generated API schema and interactive documentation powered by Swagger / OpenAPI (drf-spectacular).

---

## 🛠️ Tech Stack

* **Backend:** Python, Django, Django REST Framework (DRF)
* **Database:** PostgreSQL
* **Containerization:** Docker & Docker Compose
* **Testing & Quality:** `unittest` (TDD approach), Flake8 (linting)
* **API Documentation:** Swagger / OpenAPI UI

---

## ⚙️ Setup & Running with Docker

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/recipe-app-api.git
   cd recipe-app-api

```

2. **Build and start containers:**
```bash
docker-compose up --build

```


3. **Run tests:**
```bash
docker-compose run --rm app sh -c "python manage.py test"

```


4. **Run linting (Flake8):**
```bash
docker-compose run --rm app sh -c "flake8"

```



---

## 📖 API Documentation

Once the containers are running, access the interactive API docs:

* **Swagger UI:** `http://127.0.0.1:8000/api/docs/`
* **Schema:** `http://127.0.0.1:8000/api/schema/`

```

```
