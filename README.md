# Blogicum

**Blogicum** — это блог-платформа на Django, позволяющая пользователям просматривать записи в различных категориях. Проект включает в себя:

- Главную страницу со списком всех записей
- Детальные страницы для каждой записи
- Страницы категорий для фильтрации записей
- Дополнительные страницы: **О проекте** и **Правила**

---

## 🚀 Установка и запуск

1. **Клонируйте репозиторий:**

```bash
git clone <адрес_репозитория>
cd blogicum
```

2. **Создайте и активируйте виртуальное окружение**:
```bash
python -m venv venv
source venv/bin/activate      # для Linux/MacOS
venv\Scripts\activate         # для Windows
```

3. **Установите зависимости**:
```bash
pip install -r requirements.txt
```

4. **Примените миграции**:
```bash
python manage.py migrate
```

5. **Запустите сервер разработки**:
```bash
python manage.py runserver
```

Откройте в браузере:
http://127.0.0.1:8000/

### Основные приложения

- **blog** — приложение с записями блога  
  - Главная страница: `/`  
  - Детальный просмотр записи: `/posts/<id>/`  
  - Просмотр записей по категориям: `/category/<slug>/`

- **pages** — статические страницы  
  - О проекте: `/about/`  
  - Правила: `/rules/`
