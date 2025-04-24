# ai_recruitment_backend
# ai_recruitment_backend
## Folder Structure

```
.
├── app
│   ├── api
│   │   ├── __init__.py
│   │   └── v1
│   │       ├── endpoints
│   │       │   ├── candidates.py
│   │       │   ├── __init__.py
│   │       │   └── scraping.py
│   │       ├── __init__.py
│   │       └── router.py
│   ├── core
│   │   ├── config.py
│   │   ├── exceptions.py
│   │   ├── __init__.py
│   │   ├── logger.py
│   │   └── security.py
│   ├── __init__.py
│   ├── main.py
│   ├── models
│   │   ├── base.py
│   │   └── __init__.py
│   ├── repositories
│   │   ├── base.py
│   │   └── __init__.py
│   ├── schemas
│   │   └── __init__.py
│   ├── services
│   │   ├── candidate_service.py
│   │   ├── __init__.py
│   │   └── scraping_service.py
│   ├── tasks
│   │   ├── __init__.py
│   │   ├── processing_tasks.py
│   │   └── scraping_tasks.py
│   ├── tests
│   │   ├── fixtures
│   │   │   └── __init__.py
│   │   ├── __init__.py
│   │   ├── integration
│   │   │   └── __init__.py
│   │   └── unit
│   │       └── __init__.py
│   └── utils
│       ├── cv_parser.py
│       ├── data_processing.py
│       ├── __init__.py
│       └── linkedin_scraper.py
├── data
│   ├── models
│   ├── processed
│   └── raw
├── docs
│   ├── API.md
│   ├── ARCHITECTURE.md
│   └── DEVELOPMENT.md
├── README.md
├── requirements-dev.txt
├── requirements.txt
└── scripts
    ├── deploy.sh
    └── setup_db.py
```
