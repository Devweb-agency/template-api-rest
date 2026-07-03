# template-api-rest
Production-ready REST API template with  FastAPI, JWT auth, PostgreSQL and Docker
# Template API REST — FastAPI + JWT + PostgreSQL



![Python](https://img.shields.io/badge/Python-3.11-blue)




![FastAPI](https://img.shields.io/badge/FastAPI-0.109-green)




![Docker](https://img.shields.io/badge/Docker-ready-blue)




![License](https://img.shields.io/badge/License-MIT-yellow)



Production-ready REST API template with JWT 
authentication, PostgreSQL and Docker.

## 🛠 Stack
- FastAPI + Uvicorn
- PostgreSQL + SQLAlchemy
- Redis (rate limiting)
- JWT Authentication
- Docker + Docker Compose
- Pytest (tests unitaires)

## ✅ Fonctionnalités
- [ ] Register / Login / Logout / Refresh token
- [ ] CRUD générique
- [ ] Pagination + filtres
- [ ] Validation Pydantic
- [ ] Rate limiting Redis
- [ ] Documentation Swagger auto
- [ ] Tests unitaires
- [ ] Docker Compose complet

## 📁 Structure
\```
template-api-rest/
├── app/
│   ├── api/
│   │   └── routes/
│   ├── core/
│   │   ├── config.py
│   │   ├── security.py
│   │   └── deps.py
│   ├── models/
│   ├── schemas/
│   └── services/
├── tests/
├── docker-compose.yml
├── Dockerfile
├── .env.example
└── README.md
\```

## ⚙️ Installation
\```bash
git clone [repo-url]
cd template-api-rest
cp .env.example .env
docker compose up -d
\```

## 📌 Règles
- Commits en anglais
- Une branche par fonctionnalité
- PR obligatoire avant merge sur main

## 👤 Assigné à
Membre Backend (solide)

## 📅 Deadline
Vendredi 10 juillet

## 📞 Support
Telegram : #tech-support
