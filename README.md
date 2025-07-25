# 🏗️ MVP-платформа аренды спецтехники

> Коммерческий проект, не вышедший в релиз. Зато у вас есть шанс купить рабочую основу под площадку объявлений/аренды/услуг.

## 🚀 Что это вообще такое

Одностраничное веб-приложение (Nuxt 3 + Django REST), разрабатываемое под заказ — но заказчик слился.
Тем не менее, MVP готов, протестирован и вполне может стать основой для классифайда, аренды, биржи услуг или b2b-сервиса.

## 🔧 Реализовано в MVP:

### 🧑‍💼 Пользовательская часть:
- Регистрация по номеру телефона и подтверждение через SMS
- Авторизация по email/телефону с хранением токена в HTTP-only куках
- Профиль пользователя: редактирование, хранение данных
- CRUD объявлений: публикация, редактирование, деактивация
- Система отзывов и рейтингов + модерирование через админку
- Поисковая фильтрация по:
  - названию
  - региону
  - ценовому диапазону
  - категории спецтехники
- Рекомендательная система (по частотным критериям)

### 🛠️ Техническое:
- SSR-приложение на **Nuxt 3 + Vue 3**
- Бэкенд на **Django REST Framework**
- Авторизация через Token в HTTP-only cookie
- Контейнеризация (Docker + docker-compose)
- Настроен CI/CD через GitHub Actions
- Адаптировано под деплой на VPS/облако

## 🔌 Технологии

- **Frontend**: Nuxt 3, Vue 3, Tailwind CSS, Pinia, Composition API
- **Backend**: Django, Django REST Framework, JWT, PostgreSQL
- **DevOps**: Docker, GitHub Actions, .env, nginx-ready конфигурации

## 📸 Скриншоты

### Главная страница

<img width="526" height="1080" alt="iPhone 15 Pro Black Titanium" src="https://github.com/user-attachments/assets/8c6117e1-baa1-4496-89de-131a404d98d3" />

---

### Редактирование объявления

<img width="526" height="1080" alt="iPhone 15 Pro Black Titanium 4" src="https://github.com/user-attachments/assets/b69e0f26-5730-4c60-978c-69852c6206eb" />

---

### Регистрация

|<img width="526" height="1080" alt="iPhone 15 Pro Black Titanium 6" src="https://github.com/user-attachments/assets/49b9d19f-3514-4a95-9c77-80cf41565838" /> |  <img width="526" height="1080" alt="iPhone 15 Pro Black Titanium 7" src="https://github.com/user-attachments/assets/45a11576-adb4-4399-9c0a-db8f37015ddf" />|<img width="526" height="1080" alt="iPhone 15 Pro Black Titanium 8" src="https://github.com/user-attachments/assets/1c1c8b8d-ba82-401f-99d6-ff044876e6aa" />|
|:-------------------------:|:-------------------------:|:-------------------------:|

## 👀 Для кого

- Разработчики, которым нужен **шаблон сложного SPA/SSR** проекта с готовой архитектурой
- Студии, кто делает маркетплейсы и хочет **сократить время до первого релиза**
- Все, кто **хочет запустить классифайд** с объявами/арендой/услугами, но не хочет писать с нуля

## 💬 Контакты

Пишите в Telegram: [@antonioMargherete](https://t.me/antonioMargherete)
Покажу демо, скину билд или дам доступ к Git.

---

> Если вы дочитали до этого места, значит, проект неплох 😉
