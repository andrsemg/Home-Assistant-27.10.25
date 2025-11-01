# Home-Assistant-27.10.25

Описание

Этот репозиторий содержит конфигурацию Home Assistant (снимок на 27.10.2025). Включает configuration.yaml, automations, scripts, scenes, templates, blueprints и custom_components.

Требования

- Home Assistant Core (указать поддерживаемую версию) — проверьте совместимость с компонентами.
- Docker + docker-compose (если используете docker-compose.yml)

Установка

1. Склонируйте репозиторий
2. Создайте .env на основе .env.example и заполните секреты
3. Запустите docker-compose up -d (или следуйте инструкциям Home Assistant для локальной установки)

Структура репозитория

- configuration.yaml — основной файл конфигурации
- automations.yaml, scripts.yaml, scenes.yaml, templates.yaml — выделённые файлы
- blueprints/ — blueprints для автоматизаций
- custom_components/ — кастомные компоненты
- docker-compose.yml — пример запуска в Docker
- old_configs/ — архив старых конфигураций (проверьте перед использованием)

Безопасность

- Ни в коем случае не храните секреты (токены, пароли, .storage) в публичном репозитории. Используйте .env и GitHub Secrets.

Контрибьютинг

1. Откройте issue перед большим изменением
2. Создавайте PR в отдельной ветке

License: MIT (см. LICENSE)

Контакты

Автор: andrsemg
