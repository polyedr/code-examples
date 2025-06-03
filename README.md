# Senior Python Developer — Портфолио

## О себе

Я — Python-разработчик уровня Senior, с опытом проектирования и поддержки production-систем. Умею разрабатывать архитектурные решения для веб-сервисов, API, фоновых задач, интеграций и бизнес-логики. Регулярно решаю задачи повышения надежности, тестируемости и расширяемости кода. Владею практиками CI/CD, Docker, мониторинга и командной разработки.

---

## Примеры кода и инженерных решений

Здесь собраны выдержки кода из разных production-проектов. Каждый фрагмент снабжен кратким описанием контекста, роли и выбранных решений.

### Содержание

- [**models.py**](https://gist.github.com/polyedr/c7783f00c20839c7c1233f2aacfe510a#file-models-py)  
  SQLAlchemy-модели для сервиса дедубликации торговых точек: пользователи, API-ключи, базовые методы ORM.  
  [README](https://gist.github.com/polyedr/c7783f00c20839c7c1233f2aacfe510a#file-readme-md)  
- [**task_sd_work.py**](https://gist.github.com/polyedr/a4584e832709eae77d4f439f077b1e07#file-task_sd_work)  
  FSM-логика для Telegram-бота поддержки: обработка тикетов с изменением статусов задач (aiogram, intradesk).  
  [README](https://gist.github.com/polyedr/a4584e832709eae77d4f439f077b1e07#file-readme-md)  
- [**categories.py**](https://gist.github.com/polyedr/5f291d5137cf0e8ce67b1d454c064db6#file-readme-md)  
  Реализация сортировки категорий через bulk_update в Django REST API (adevi).  
  [README](https://gist.github.com/polyedr/5f291d5137cf0e8ce67b1d454c064db6#file-readme-md)  
- [**serializers.py**](https://gist.github.com/polyedr/178e06d9a767b8475bf85035802b4485#file-serializers-py)  
  DRF-сериализаторы с вложенными объектами, безопасным обновлением пароля, интеграцией профилей (adevi).  
  [README](https://gist.github.com/polyedr/178e06d9a767b8475bf85035802b4485#file-readme-md)  
- [**local.py**](https://gist.github.com/polyedr/5655eb1b5347e18375503f1ab5ae6094#file-local-py)  
  Локальные настройки Django для изолированной разработки (adevi).  
  [README](https://gist.github.com/polyedr/5655eb1b5347e18375503f1ab5ae6094#file-readme-md)  
- [**tasks.py**](https://gist.github.com/polyedr/72e6c40d94349d94b82a093b645c307e#file-tasks-py)  
  Фоновые задачи по email-рассылке через Mailgun, реализация retry и управления ключами (hubnexa).  
  [README](https://gist.github.com/polyedr/72e6c40d94349d94b82a093b645c307e#file-readme-md)  
- [**make_request.py**](https://gist.github.com/polyedr/f2d94180139518850f6c65be465a5063#file-make_request-py)  
  Email-уведомление после заявки на курс, Flask + SQLAlchemy + Celery (enrichme).  
  [README](https://gist.github.com/polyedr/f2d94180139518850f6c65be465a5063#file-readme-md)  

---

## Используемый стек

- Python 3.x
- Django / Django REST Framework / Flask
- SQLAlchemy / PostgreSQL / Redis
- Celery / Mailgun API
- Aiogram (Telegram-боты)
- Docker, docker-compose
- CI/CD: GitHub Actions, pytest, pre-commit

---

## Мои подходы и приоритеты

- **Проектирование архитектуры:** Использую слои, DI, сервис-объекты для изоляции бизнес-логики.
- **Тестирование:** Покрываю ключевые точки unit/integration-тестами.
- **Документирование:** Добавляю README, описания к API и техническим решениям.
- **Безопасность:** Реализую защищённую работу с паролями, API-ключами, обрабатываю edge-cases.
- **Автоматизация:** Применяю Docker, автоматические пайплайны, линтеры, pre-commit.
- **Менторинг:** Могу вести ревью, разбирать чужой код, объяснять архитектурные решения.

---

## Контакты

- [Email](mailto:ivan.ishchukov@gmail.com)
- [Telegram](@iishchukov)

---

### Ниже — подробности по каждому фрагменту кода (перейдите по ссылке "README" для контекста и инженерных решений).
