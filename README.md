# Зачетное задание по проектированию и развёртыванию распределенных хранилищ данных
1 этап: Сбор данных нефтегазовых компаний с выручкой более $5 млрд, генерация на их базе 
2 этап: Построение модели в Orange и проведение её валидации 
3 этап: Валидация модели (понять, какая модель лучше) 
4 этап: Формирование pickle файла


Важные команды при работе в VS Code:

python3 -m venv .venv - создание виртуального окружения
source venv\Scripts\activate - активация виртуальной среды

pip install apache-airflow -скачивание airflow
pip install --upgrade pip -апгрейдинг, если нужен
docker compose up airflow-init - инициализация докер-компоуз: 
docker compose up - запуск докер компоуз

git add . - добавление всех изменений
git commit - фиксация изменений, коммитинг
git push origin - отправка изменений в удаленный репозиторий


