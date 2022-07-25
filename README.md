# Aviasales clone

Проект, реализующий логику и представление выбора билетов для авиаперелетов. Возможны выбор аэропортов вылета и приземления, дат отправления и прибытия, фильтрация по параметрам количества пересадок и авиакомпании, сортировка по длительности или стоимости полета.

Стилизация компонентов осуществляется с помощью библиотеки React Material UI, бизнес-логика вынесена в отдельное внешнее хранилище, реализованное с Redux Toolkit. Данные по билетам приложение получает через API запросы. Сборка прозводилась с поомщью Webpack (конфиг от CRA).

Стек технологий:

- HTML
- CSS (SASS)
- React
- React Material UI
- Redux Toolkit
- TypeScript
- Webpack

## Локальный запуск

Скопируйте репозиторий локально, после чего в корневой папке с проектом введите:

### `npm install`

Установит все требуемые для проекта зависимости.

### `npm run start`

Запустит проект в режиме разработки.\
Откройте [http://localhost:3000](http://localhost:3000) для просмотра в браузере.

Страница будет перезагружаться при любых изменениях.

### `npm run build`

Соберет проект в папке `build`.\
Бандл будет собран в продакшн-режиме и оптимизирован для лучшей производительности, код минифицирован, а названия файлов включают в себя хэш.
