# Elevator Resting Floor Data Collector

## 🚀 Objetivo
Registrar eventos de uso de elevador para alimentar um futuro modelo preditivo de "resting floor" ideal.

## 📦 Como executar

### Ambiente local

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
```

### Com Docker

```bash
docker build -t elevator-api .
docker run -p 8000:8000 --env-file .env elevator-api
```

## 🧪 Testes

```bash
pytest
```
