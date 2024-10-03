# Kittygram
Kittygram - учебный проект, написанный на Django, DRF.
Добро пожаловать в Kittygram – платформу для всех любителей котов и кошек! Здесь вы можете зарегистрироваться, делиться фотографиями своих пушистых друзей и выставлять на показ их достижения.

## Запуск проекта локально

### Установка зависимостей

1. Убедитесь, что у вас установлен Python версии 3.9 и Node.js версии 18.
2. Склонируйте этот репозиторий:

    ```bash
    git clone git@github.com:MikhailSavenko/kittygram_final.git
    ```

3. Перейдите в директорию backend:

    ```bash
    cd backend
    ```

4. Установите зависимости:

    ```bash
    pip install -r requirements.txt
    ```

5. Перейдите в директорию frontend:

    ```bash
    cd ../frontend
    ```

6. Установите зависимости для фронтенда:

    ```bash
    npm ci
    ```

### Запуск проекта

1. Запустите сервер backend:

    ```bash
    cd ../backend
    python manage.py runserver
    ```

2. Запустите сервер frontend:

    ```bash
    cd ../frontend
    npm run start
    ```

3. Откройте веб-браузер и перейдите по адресу [http://localhost:3000](http://localhost:3000), чтобы увидеть приложение в действии.
