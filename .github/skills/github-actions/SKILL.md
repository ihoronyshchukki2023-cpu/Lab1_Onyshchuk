# Skill: github-actions

## Description
Створення конфігурації CI/CD для GitHub Actions.

## Actions
1. Створи файл `.github/workflows/ci.yml`.
2. Налаштуй тригер на `push` та `pull_request` у гілки `develop` та `master`.
3. Використай одну job із `matrix` для трьох ОС: `ubuntu-latest`, `windows-latest`, `macos-latest`.
4. Кроки у workflow:
   - Checkout коду.
   - Налаштування Python.
   - Запуск відповідного скрипта складання/тестування (`run.sh` для Linux/macOS, `run.bat` для Windows).

## Expected Output
Коректний YAML файл CI workflow без секретів та токенів.