
## Bookmarks Проект Django с использованием Redis, Stripe и Celery

### Описание проекта

Это проект на Django, включающий множество функциональных возможностей, таких как социальная аутентификация, асинхронная обработка задач, работа с Redis и другие современные веб-технологии. Проект нацелен на создание полноценного веб-приложения с подписками, бесконечной прокруткой и системой рейтинга на основе просмотров изображений.

### Основные функции

- **Социальная аутентификация:** Включена возможность входа через Google с использованием Python Social Auth.
- **Запуск сервера через HTTPS:** Настроен безопасный сервер разработки с сертификатом SSL.
- **Взаимосвязи многие-ко-многим:** Реализованы отношения через промежуточную модель.
- **Работа с Redis:** Используется для хранения просмотров изображений и генерации рейтинга популярных изображений.
- **Асинхронные задачи:** Celery управляет асинхронными задачами для улучшения производительности.
- **JavaScript букмарклет:** Букмарклет для взаимодействия с другими сайтами с помощью JavaScript.
- **Генерация миниатюр:** Использование easy-thumbnails для создания миниатюр изображений.
- **Бесконечная прокрутка:** Реализована постраничная подгрузка контента на основе AJAX запросов.

### Запуск проекта

1. Запустите сервер разработки с поддержкой HTTPS:
   ```bash
   python manage.py runserver_plus --cert-file cert.crt
   ```
2. Запустите Redis через Docker:
   ```bash
   docker run -it --rm --name redis -p 6379:6379 redis
   ```
3. Перейдите по адресу:
   ```
   https://127.0.0.1:8000/account/
   ```

### Установленные зависимости

- **Django Extensions**: Для удобства разработки и отладки.
- **Stripe**: Для реализации системы оплаты и подписок.
- **Redis**: Для кэширования и хранения данных о просмотрах изображений.
- **Celery**: Для асинхронной обработки задач.

### Дополнительные функции

- Подсчет просмотров изображений и создание рейтинга популярных изображений.
- Асинхронные HTTP-запросы с использованием JavaScript и Django.
- Адаптация форм под конкретные задачи приложения.

---

Теперь на английском:

---

## Django Project with Redis, Stripe, and Celery

### Project Overview

This is a Django project that includes several features such as social authentication, asynchronous task processing, Redis integration, and other modern web technologies. The project aims to create a full-fledged web application with subscriptions, infinite scrolling, and an image view ranking system.

### Key Features

- **Social Authentication:** Google login integrated using Python Social Auth.
- **HTTPS Development Server:** A secure development server is set up with an SSL certificate.
- **Many-to-Many Relationships:** Implemented through an intermediary model.
- **Redis Integration:** Used for storing image views and generating a ranking of popular images.
- **Asynchronous Tasks:** Celery handles asynchronous tasks to improve performance.
- **JavaScript Bookmarklet:** Bookmarklet to interact with other websites using JavaScript.
- **Thumbnail Generation:** Using easy-thumbnails for creating image thumbnails.
- **Infinite Scrolling:** Implemented paginated content loading based on AJAX requests.

### Running the Project

1. Start the development server with HTTPS:
   ```bash
   python manage.py runserver_plus --cert-file cert.crt
   ```
2. Run Redis with Docker:
   ```bash
   docker run -it --rm --name redis -p 6379:6379 redis
   ```
3. Access the application at:
   ```
   https://127.0.0.1:8000/account/
   ```

### Installed Dependencies

- **Django Extensions**: For development and debugging ease.
- **Stripe**: For implementing a payment and subscription system.
- **Redis**: For caching and storing image view data.
- **Celery**: For asynchronous task handling.

### Additional Features

- Counting image views and creating a ranking of the most viewed images.
- Asynchronous HTTP requests using JavaScript and Django.
- Adapting forms for specific application tasks.

---
![Снимок экрана 2024-10-17 175130](https://github.com/user-attachments/assets/ba9732aa-8081-4800-8d13-10b3f5d4d56d)
![Снимок экрана 2024-10-17 175246](https://github.com/user-attachments/assets/3cd1d37d-1df3-4558-aab5-53c1786ec933)
![Снимок экрана 2024-10-17 175320](https://github.com/user-attachments/assets/3aae485c-ddde-43a9-b564-8670fd1d1233)
![Снимок экрана 2024-10-17 175345](https://github.com/user-attachments/assets/063b3044-ede8-4e29-89e3-85b2f839fe03)
![Снимок экрана 2024-10-17 175413](https://github.com/user-attachments/assets/0c86193a-c479-4072-a529-9a3a7e293c7a)
![Снимок экрана 2024-10-17 175508](https://github.com/user-attachments/assets/30530be0-36e8-4c3d-844b-062468908ed6)
![Снимок экрана 2024-10-17 175544](https://github.com/user-attachments/assets/1c34ae6e-4e38-4988-8929-96960f2a199d)
![Снимок экрана 2024-10-17 175615](https://github.com/user-attachments/assets/43ba129f-c57f-4149-aa7d-645b2cb95f3d)
![Снимок экрана 2024-10-17 175820](https://github.com/user-attachments/assets/2c8a86b7-1c62-4a3d-801a-0dad5f78c08c)
![Снимок экрана 2024-10-17 175856](https://github.com/user-attachments/assets/ee428709-42cb-48d8-b8bb-2f2a68c87c5b)
