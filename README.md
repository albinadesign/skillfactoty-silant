# Skillfactory Silant

## Описание проекта

Проект "Skillfactory Silant" включает в себя две основные части: backend и frontend. Backend реализован с использованием Django и Django REST framework, а frontend построен на React.

## Требования

- Python 3.8 или выше
- Node.js 14 или выше
- npm (Node Package Manager)
- Git

## Установка и запуск проекта

### Шаг 1: Клонирование репозитория

Сначала клонируйте репозиторий на свой локальный компьютер:

```bash
git clone https://github.com/albinadesign/skillfactoty-silant.git
cd skillfactoty-silant

Шаг 2: Настройка backend
Перейдите в папку backend:

cd backend

Создайте и активируйте виртуальное окружение:

Для Windows:

python -m venv venv
venv\Scripts\activate

Для macOS и Linux:

python3 -m venv venv
source venv/bin/activate

Установите зависимости:

pip install -r requirements.txt

Выполните миграции базы данных:

python manage.py migrate

Создайте суперпользователя:

python manage.py createsuperuser

Запустите сервер разработки:

python manage.py runserver

Шаг 3: Настройка frontend

Перейдите в папку frontend:

cd ../frontend

Установите зависимости:

npm install

Для разработки запустите сервер разработки:

npm start

Для продакшн-среды создайте оптимизированную сборку:

npm run build

Шаг 4: Открытие приложения

Откройте браузер и перейдите по адресу http://localhost:3000, чтобы увидеть фронтенд часть приложения. Для доступа к админке Django, перейдите по адресу http://localhost:8000/admin и используйте учетные данные, созданные на шаге 2


API Документация

Документация по API доступна по адресу http://localhost:8000/api/swagger/ после запуска сервера backend.


Структура проекта

backend/ - папка с кодом backend.

frontend/ - папка с кодом frontend.
