# Проект "lad-vue"

Этот проект - шаблон Vue.js с использованием Vite для разработки современных веб-приложений. Проект интегрирует Vuetify для стилизации и добавляет поддержку состояния с использованием Pinia.

## Требования

Убедитесь, что у вас установлены Node.js и npm. Этот проект предназначен для работы с Node.js версии 18 и выше.

## Установка зависимостей

Откройте терминал и выполните следующую команду в корневой директории проекта:

```bash
npm install
```

## Запуск проекта в режиме разработки

Для запуска проекта в режиме разработки выполните:

```bash
npm run dev
```

Откройте браузер и перейдите по адресу [http://localhost:5173](http://localhost:5173) для просмотра вашего приложения.

## Сборка проекта

Для создания оптимизированной сборки проекта используйте команду:

```bash
npm run build
```

## Предпросмотр собранного проекта

Вы можете предварительно просмотреть собранный проект с помощью следующей команды:

```bash
npm run preview
```

## Линтинг и форматирование

Для проверки и исправления стиля кода используйте следующие команды:

```bash
npm run lint  # Линтинг
npm run format  # Форматирование кода
```

## Используемые библиотеки

- Vue.js: ^3.3.4
- Vue Router: ^4.2.5
- Vuetify: ^3.4.0
- Pinia: ^2.1.7

## Структура проекта

- Исходный код находится в директории `src/`.
- Конфигурация TypeScript - `tsconfig.app.json`.
- Конфигурация линтеров - `.eslintrc.js`.
- Конфигурация Vite - `vite.config.js`.

Для получения дополнительной информации о проекте, обратитесь к документации соответствующих инструментов и библиотек.
