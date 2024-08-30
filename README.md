# Guess the Number Game

Ця гра ["Вгадай число"](https://number-game-orpin.vercel.app) є міні-додатком для [Telegram бота](https://t.me/MyGuessingBot), реалізованим за допомогою WebView-2. Проект використовує React та Vite для [фронтенду](https://github.com/IhorZolot/numberGame) і Node.js з Express для [бекенду](https://github.com/IhorZolot/backEndNumberGame).

## Вміст

- [Огляд проекту](#oгляд-проекту)
- [Технології](#технології)
- [Інструкції для запуску](#інструкції-для-запуску)
- [Інструкції для деплою](#інструкції-для-деплою)
- [Запуск бота](#запуск-бота)

## Огляд проекту

Цей проект складається з двох частин:
- **Фронтенд:** Реалізовано з використанням React і Vite. Гра дозволяє користувачеві вводити число і перевіряти, чи є його вгадане число правильним.
- **Бекенд:** Реалізовано з використанням Node.js і Express. Він генерує випадкове число, зберігає його і обробляє запити на перевірку вгаданого числа.

## Технології

- **Фронтенд:** React, Vite
- **Бекенд:** Node.js, Express.js
- **База даних:** Немає (все зберігається в оперативній пам'яті)

## Інструкції для запуску

### 1. Запуск бекенду
1. Встановлення:
   ```bash
   git clone https://github.com/your-repository/backEndNumberGame
   cd backEndNumberGame
   ```

2. Встановіть залежності:
  ```bash
   npm install
   ```
3. Запуск бекенд проекту 
  ```bash
   npm start
   ```


### 2. Запуск фронтенду
1. Встановлення:
   ```bash
   git clone https://github.com/your-repository/numberGame
   cd numberGame
   ```
2. Встановіть залежності:
  ```bash
   npm install
  ```
3. Запуск бекенд проекту 
  ```bash
   npm run dev
  ```
---
## Інструкції для деплою

### Деплой бекенду
Виберіть платформу для деплою (наприклад, Render, Heroku).
Склонуйте репозиторій на платформу.
Налаштуйте середовище та запустіть сервер відповідно до інструкцій платформи.

### Деплой фронтенду
Налаштуйте платформу для деплою фронтенду (наприклад, Netlify, Vercel).
Склонуйте репозиторій або підключіть його до платформи.
Налаштуйте середовище та запустіть фронтенд відповідно до інструкцій платформи.
---
## Запуск бота

1. Запуск бота в Telegram
Відкрийте Telegram та знайдіть бот [@MyGuessingBot](https://t.me/MyGuessingBot) та запустіть гру.
**⚠️ Важливо:** Гра може не відразу запуститись, у зв'язку з тим що бекенд на Vercel має властивість засипати. Тому іноді потрібний час для запуску гри.


[Ihor Zolotoverkh](www.linkedin.com/in/ihor-zolotoverkh)