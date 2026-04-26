Запуск бэкенда (Django)
Откройте терминал и введите команды по очереди:
bash
# 1. Зайдите в папку с бэкэндом
```bash
cd Clinic_1/Clinic/backend-master/TRPO
```
# 2. Создайте виртуальное окружение
Для Linux/MACOS
```bash
python3 -m venv venv
```
для Windows
```bash
python -m venv venv
```
# 3. Активируйте его
Для Linux/MACOS
```bash
source venv/bin/activate
```
для Windows
```bash
source venv/Scripts/activate
```
# 4. Установите зависимости
```bash
pip install -r requirements.txt
```

# 5. Примените миграции базы данных
```bash
python manage.py migrate
```

# 6. Запустите сервер
```bash
python manage.py runserver
```
Бэкенд запустится по адресу: http://127.0.0.1:8000

Шаг 3. Запуск фронтенда (React)
Откройте второй терминал (не закрывая первый!) и введите:
bash
# 1. Зайдите в папку фронтенда
```bash
cd Clinic_1/Clinic/Психологическая клиника сайт
```
# 3. Установить вручную (если нет package.json)
```bash
npm install zod@3.22.4 @hookform/resolvers@3.3.2 libphonenumber-js
npm install react-hook-form zod @hookform/resolvers libphonenumber-js
npm install @hookform/resolvers
```
# 2. Установите зависимости
```bash
npm install
```
# 3. Запустите сайт
```bash
npm run dev
```
Сайт откроется по адресу: http://localhost:5173

Шаг 4. Доступ к панели администратора
Откройте в браузере: http://127.0.0.1:8000/admin/
