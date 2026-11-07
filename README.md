# Контрольная работа №2 (Войнов М.О., ЭФБО-14-25)

Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

## Описание
Проект представляет собой учебную версию сайта онлайн-школы английского языка SpeakUp, разработанную с использованием CSS-фреймворка Bootstrap.

## Используемый фреймворк
Bootstrap 5.3.3.

## Способ подключения
Bootstrap подключён локально из папки vendor/bootstrap/ (без CDN).
Используются файлы:
- vendor/bootstrap/css/bootstrap.min.css
- vendor/bootstrap/js/bootstrap.bundle.min.js

## Реализованные компоненты
- navbar (с выпадающим меню dropdown);
- card (карточки курсов);
- btn (кнопки);
- badge (метки «Хит», «Новинка», «Скидка»);
- alert (информационные сообщения);
- modal (модальное окно быстрой записи);
- form-control, form-select, input-group, form-check;
- accordion (частые вопросы на странице курса);
- carousel (отзывы учеников на главной);
- breadcrumb (хлебные крошки);
- table (характеристики курса).

## Структура проекта
kr2-bootstrap-shop/
├── vendor/
│   └── bootstrap/
│       ├── css/
│       │   └── bootstrap.min.css
│       └── js/
│           └── bootstrap.bundle.min.js
├── css/
│   └── custom.css
├── images/
├── index.html
├── catalog.html
├── product.html
├── order.html
├── contacts.html
├── README.md
└── .gitignore

## Страницы проекта
- index.html — главная страница (hero-блок, карусель отзывов, преимущества, популярные курсы).
- catalog.html — каталог курсов (карточки, бейджи, модальное окно).
- product.html — страница курса (характеристики, таблица, accordion).
- order.html — форма записи на урок (Bootstrap-формы).
- contacts.html — контакты и обратная связь (дополнительная страница).

## Самостоятельные доработки
- Локальное подключение Bootstrap (без CDN) — файлы в vendor/bootstrap/.
- Добавлена дополнительная страница contacts.html.
- Использован дополнительный компонент carousel для отзывов.
- Использован дополнительный компонент accordion для частых вопросов.
- Настроены кастомные цвета через CSS-переменные в custom.css.
- Все страницы имеют уникальные title и meta description.
- Использованы хлебные крошки (breadcrumb) на внутренних страницах.

## Используемые технологии
- HTML5;
- Bootstrap 5.3.3;
- CSS3;
- Git;
- GitHub.

## Ссылка на репозиторий
https://github.com/player48021/kr2-bootstrap-shop

## Ссылка на опубликованный сайт (GitHub Pages)
https://player48021.github.io/kr2-bootstrap-shop/