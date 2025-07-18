# Film_Filter

Веб-приложение для каталогизации фильмов с возможностью поиска, фильтрации и добавления в избранное

## 1. Возможности

- Просмотр каталога фильмов с детальной информацией
- Фильтрация по жанру, году выпуска и рейтингу
- Поиск фильмов по названию и другим параметрам
- Добавление фильмов в избранное с возможностью оценки
- Сохранение избранного и пользовательских рейтингов между сеансами


## 2. Структура проекта

| Путь | Назначение |
|------|------------|
| `docs/` | Документация проекта |
| └── `демо-версия.fig` | Макет интерфейса в Figma |
| `src/` | Исходный код |
| ├── `css/` | Стили приложения |
| │   ├── `styles.css` | Стили главной страницы |
| │   └── `styles2.css` | Стили страницы фильма |
| ├── `js/` | Логика приложения |
| │   ├── `1.js` | Основная логика главной страницы |
| │   ├── `2.js` | Логика страницы фильма |
| │   └── `2.json` | База данных фильмов |
| ├── `index.html` | Главная страница (каталог фильмов) |
| └── `index_2.html` | Страница фильма (детальная информация) |
| `README.md` | Информация о проекте и инструкции |

## 3. Установка и запуск

1. git clone 
2. start index.html

## 4. Использование
Главная страница
- Используйте фильтры в левой панели для поиска нужных фильмов
- Нажмите на карточку фильма для просмотра детальной информации
- Нажмите ♡ для добавления в избранное

Страница фильма
- Просматривайте полную информацию о фильме
- Оценивайте фильм с помощью звезд
- Возвращайтесь в каталог с помощью кнопки в шапке

Избранное
- Открывается через кнопку в шапке
- Позволяет просматривать и оценивать избранные фильмы
- Сохраняется между сеансами

## 5. Дополнительно

Проект соответствует требованиям:
- Работа с JSON (загрузка и сохранение данных)
- Использование AJAX (Fetch API)
- Динамическое обновление DOM
- Интерактивные элементы (фильтры, модальные окна, рейтинги)
