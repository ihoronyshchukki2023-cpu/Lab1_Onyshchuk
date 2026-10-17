# Skill: build-and-test

## Description
Налаштування системи тестування та скриптів запуску.

## Actions
1. Створи каталог `tests/` та файл `tests/test_main.py`.
2. У `test_main.py` імпортуй функцію `add` з `src.main` і напиши щонайменше один юніт-тест використовуючи `pytest`.
3. Створи кросплатформні скрипти запуску в корені проєкту:
   - `run.sh` (для Linux/macOS): створює `venv` (якщо немає), активує його, встановлює залежності з `requirements.txt` та запускає `pytest`.
   - `run.bat` (для Windows): робить те ж саме, але у синтаксисі Windows Batch.

## Expected Output
Файли `tests/test_main.py`, `run.sh`, `run.bat` успішно створені. Тести повинні запускатися через фреймворк `pytest`.