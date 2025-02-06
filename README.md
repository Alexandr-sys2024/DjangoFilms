# DjangoFilms

📽️ **DjangoFilms** — веб-приложение на Django для управления каталогом фильмов.

## 🚀 Возможности
- Просмотр списка фильмов
- Добавление отзывов и оценок
- Поиск фильмов
- Управление через админ-панель Django

## 🔧 Установка и настройка
1. **Клонируйте репозиторий:**  
   ```bash
   git clone https://github.com/Alexandr-sys2024/DjangoFilms.git
   cd DjangoFilms
   ```
2. **Создайте виртуальное окружение:**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate  # Windows
   ```
3. **Установите зависимости:**  
   ```bash
   pip install -r requirements.txt
   ```
4. **Выполните миграции:**  
   ```bash
   python manage.py migrate
   ```
5. **Создайте суперпользователя:**  
   ```bash
   python manage.py createsuperuser
   ```
6. **Запустите сервер:**  
   ```bash
   python manage.py runserver
   ```
7. **Откройте в браузере:**  
   - Главная страница: `http://127.0.0.1:8000/`
   - Админ-панель: `http://127.0.0.1:8000/admin/`

## 📡 API Endpoints
> _Пример API-запросов (если проект поддерживает API)_
```bash
GET /api/films/  # Получить список фильмов
POST /api/films/  # Добавить новый фильм
GET /api/films/{id}/  # Получить фильм по ID
```

## 📸 Скриншоты
*(Добавьте скриншоты работы приложения)*

## 📜 Лицензия
Проект распространяется под лицензией MIT.

## ✍️ Автор
- **Alexandr-sys2024**  
  📧 Свяжитесь через GitHub!