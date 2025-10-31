motion-tracker-api/
├─ app/
│  ├─ main.py
│  ├─ auth.py
│  ├─ models.py
│  ├─ schemas.py
│  ├─ pipeline/
│  │  ├─ __init__.py
│  │  ├─ tracker.py
│  │  ├─ detectors.py
│  │  ├─ filters.py
│  │  ├─ utils.py
│  │  └─ ae_export.py
│  ├─ storage/
│  │  ├─ __init__.py
│  │  └─ filesystem.py
│  ├─ workers.py
│  ├─ config.py
│  └─ version.py
├─ public/
│  ├─ samples/
│  │  └─ sample.mp4
│  └─ expressions/
│     ├─ expression.txt
│     └─ ae_import.jsx
├─ .env.sample
├─ requirements.txt
├─ README.md
├─ openapi.yaml
├─ postman_collection.json
└─ Makefile
# Fuco-Tracker-API
Tracker per AE
