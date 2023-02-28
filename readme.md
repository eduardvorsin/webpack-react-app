# Сборка Webpack(v5)
## ✨ Возможности сборки:
- Минимизация и транспиляция .js и jsx файлов
- Поддержка расширений .ts и .tsx
- Проверка синтаксиса кода в режиме разработчика с помощью ESLint и StyleLint
- Оптимизация картинок
- Поддержка SVGR
- Поддержка CSS modules и .scss/sass файлов
- Обработка файлов со стилями PostCSS плагином
- Поддержка Jest, Testing Library
- Поддержка историй Storybook'а
- Копирование статических ресурсов в папку dist
- Анализирование размера бандла через Webpack Bundle Analyzer

## 📑 Список плагинов
### babel плагины
- @babel/core - ядро компилятора Babel
- @babel/eslint-parser - позволяет анализировать babel код ESLint'ом
- @babel/preset-env - пресет для транспиляции современного js кода
- @babel/preset-react - пресет для транспиляции react кода
- @babel/preset-typescript - для транспиляции typescript кода
- @babel/runtime - runtime хелперы для babel

### storybook плагины
- @storybook/addon-actions
- @storybook/addon-essentials
- @storybook/addon-interactions 
- @storybook/addon-links
- @storybook/builder-webpack5
- @storybook/manager-webpack5
- @storybook/react
- @storybook/testing-library

### Webpack плагины
- compression-webpack-plugin - gzip сжатие файлов
- copy-webpack-plugin - плагин для копирования файлов и директорий
- css-minimizer-webpack-plugin - минификатор css файлов
- fork-ts-checker-webpack-plugin - запуск TypeScript тайп чекера в отдельном процессе
- html-webpack-plugin - поддержка html файлов
- image-minimizer-webpack-plugin - минификатор изображений
- stylelint-webpack-plugin - поддержка StyleLint
- terser-webpack-plugin - минификатор js файлов
- webpack-bundle-analyzer - анализ размера бандла
- mini-css-extract-plugin - разделение CSS на отдельные файлы 
- eslint-webpack-plugin - поддержка ESLint

### Сам webpack
- webpack 
- webpack-cli - работа с webpack через консольные команды
- webpack-dev-server - сервера для разработки, обновляется при изменении файлов

### Лоадеры
- css-loader - обработка css файлов
- postcss-loader - пост обработка css файлов
- sass-loader - обработка sass/scss файлов
- style-loader - обработка css файлов в dev моде
- babel-loader - обработка js/jsx/ts/tsx файлов
- resolve-url-loader - правильное разрешение url() в scss/sass файлах
- thread-loader - обрабатывает дорогостоящие лоадеры в другом потоке

### ESLint
- eslint - js линтер
- eslint-config-airbnb-base - airbnb конфиг для линтера
- eslint-import-resolver-webpack - плагин для разрешения импортов через webpack
- eslint-plugin-import - правила для импортов
- eslint-plugin-jest - правила для jest тестов
- eslint-plugin-jest-dom - правила для матчеров jest-dom
- eslint-plugin-react - правила для кода на реакте
- eslint-plugin-storybook - правила для историй Storybook
- eslint-plugin-testing-library - правила для Testing Library


### оптимизация изображений
- imagemin - плагин для оптимизации картинок
- imagemin-gifsicle - плагин для оптимизации gif через imagemin
- imagemin-mozjpeg - плагин для оптимизации jpg через imagemin
- imagemin-pngquant - плагин для оптимизации png через imagemin
- imagemin-svgo - плагин для оптимизации svg через imagemin
- imagemin-webp - плагин для оптимизации webp через imagemin
- svgo - оптимизатор svg

### Тесты
- babel-jest - jest плагин чтобы использовать babel для транспиляции в тестах
- jest - тест раннер
- jest-environment-jsdom - симулирует DOM окружение при тестировании
- jest-watch-typeahead - фильтрация тестов по имени файла или имени теста
- @testing-library/react - библиотека с утилитами для тестирования в react
- @testing-library/jest-dom - jest матчеры для работы с DOM

### Стили
- postcss-import - импорт css файлов через директиву @import
- postcss-preset-env - поддержка современного css для старых браузеров
- sass - css препроцессор 

### Stylelint
- stylelint - линтинг стилей
- stylelint-config-standard-scss - базовый конфиг для линтинга стилей

### Тайпскрипт
- typescript
- typescript-plugin-css-modules - плагин для правильного распознавания содержимого css модулей ts'ом

### Типы
- @types/react  
- @types/react-dom
- @typescript-eslint/eslint-plugin
- @typescript-eslint/parser
- @types/jest
- @types/webpack-bundle-analyzer

### React
- react
- react-dom

### Другое
- cross-env - устанавливает env переменные которые могут использоваться на разных платформах
- browserslist - список браузеров которые поддерживаются проектом
- @svgr/webpack - плагин для поддержки SVGR синтаксиса

## 🚀 Установка и запуск
1. Копируем репозиторий через `$ git clone https://github.com/eduardvorsin/webpack-react-app.git`
2. Устанавливаем зависимости через `$ npm i`
3. Запускаем саму сборку

Чтобы запустить сборку в режиме разработки нужно вызвать команду `$ npm start`
Для запуска сборки в режиме продакшена нужно вызвать команду `$ npm build`


