# Интернет-магазин PcMarket

**Тема:** Контрольная работа №2. CSS-фреймворки: разработка интерфейса на Tailwind 4.

## Описание проекта
Многостраничный HTML/CSS-сайт магазина компьютерной техники и услуг. 

## Структура проекта

```
pc-market
│
├── assets
│   ├── fonts
│   │   ├── space-grotesk-v22-latin-500.woff2
│   │   ├── space-grotesk-v22-latin-700.woff2
│   │   └── space-grotesk-v22-latin-regular.woff2
│   ├── icons
│   │   └── monitor-pc.svg
│   └── img
│       ├── clean.jpeg
│       ├── gaming-pc.jpg
│       ├── rtx4070.jpeg
│       └── sborka.jpg
├── assets
│   └── src
|       └── input.css
├── css
│   └── input.css
├── index.html
├── js
│   └── main.js
├── package.json
├── bun.lock
├── tsconfig.json
├── pages
│   ├── aboutUs.html
│   ├── catalog.html
│   ├── contacts.html
│   ├── order.html
│   ├── product.html
│   ├── reviews.html
│   └── services.html
└── README.md

```

## Используемые технологии

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Ссылка на опубликованный проект
GitHub Pages: 

## Инструкция по просмотру
Склонинруйте репозиторий, перейдите в директорию и откройте файл `index.html` в любом браузере или перейдите по ссылке на GitHub Pages.

## Обязательные страницы проекта
В рамках базового задания были реализованы следующие HTML-страницы:
1. **Главная страница (`index.html`)** — витрина магазина, содержащая общую информацию о компании, промо-блоки и навигацию по сайту.
2. **Каталог товаров (`pages/catalog.html`)** — список доступной компьютерной техники с кратким описанием, ценами и кнопками для перехода к покупке.
3. **Карточка товара (`pages/product.html`)** — детальная страница отдельного товара с подробными характеристиками, фотографиями и информацией о наличии.
4. **Контакты (`pages/contacts.html`)** — страница с контактными данными, режимом работы и формой обратной связи.

## Самостоятельные доработки 
1. **Пользовательский сценарий покупки:** Создана отдельная страница оформления заказа (`pages/order.html`). Теперь кнопки «Купить» из каталога и со страницы товара логически завершают путь пользователя, ведя на форму заказа.
2. **Расширенная структура сайта:** Добавлены дополнительные контентные страницы, делающие сайт более полноценным:
   - `pages/services.html` (Услуги по сборке и чистке ПК)
   - `pages/aboutUs.html` (О нас)
   - `pages/reviews.html` (Отзывы клиентов)
3. **Подключение Tailwind локально:** Инициализирован bun проект и был подключен Tailwind 4 по документации с оффициального сайте.



**Студент:** Петров Артём Александрович

**Группа:** ЭФБО-01-25


