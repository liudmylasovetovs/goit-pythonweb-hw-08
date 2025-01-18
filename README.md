pip install uvicorn
pip install fastapi
pip install pydantic
pip install pydantic[email]

alembic revision --autogenerate -m "Update models"

Можливі команди для ініціалізації або міграції бази даних (залежить від вашого стеку):

alembic upgrade head

python main.py
