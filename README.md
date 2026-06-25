# digital-board-system
## Быстрый старт
1. Установите зависимости: `cd backend && pip install -r requirements.txt`
2. Поднимите БД: `docker-compose up -d`
3. Запустите бэкенд: `uvicorn app.main:app --reload`
4. Откройте в браузере `http://127.0.0.1:8000` — увидите приветствие.