# Module 10 Assignment

## Running Project 

---

### 1. Clone the Repository

```bash
git clone git@github.com:8epu3/mod_10_assignment.git
cd mod_10_assignment
```

---

### 2. Create Virtual Environment


```bash
python -m venv venv
source .venv/bin/activate
```

### 3. Install Dependencies


```bash
pip install -r requirements.txt
```

### 4. Running the Project


```bash
docker-compose up
```

---

## Running Tests


```bash
pytest --cov=app tests/ --cov-report=term-missing
```

---

## Docker hub image

[Mod_10_assignment](https://hub.docker.com/r/8epe3/mod_10_assignmnet)
