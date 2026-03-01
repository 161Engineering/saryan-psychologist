# saryan-psychologist.github.io

Одностраничный сайт психолога на чистом HTML5 + CSS3 без фреймворков.

## Структура проекта

- `index.html` — основная страница
- `style.css` — стили
- `robots.txt` — инструкции для поисковых роботов
- `sitemap.xml` — карта сайта
- `assets/favicon.svg` — favicon-заглушка
- `assets/images/photo-placeholder.svg` — заглушка фото

## Деплой на GitHub Pages

1. Создайте репозиторий с именем `saryan-psychologist.github.io`.
2. Загрузите все файлы этого проекта в ветку `main`.
3. Откройте `Settings` → `Pages`.
4. В разделе `Build and deployment` выберите:
   - `Source`: `Deploy from a branch`
   - `Branch`: `main` / `/ (root)`
5. Сохраните настройки и дождитесь публикации.
6. Сайт будет доступен по адресу: `https://saryan-psychologist.github.io/`.

## Что нужно заменить перед запуском

- В `index.html` замените ID в Formspree endpoint:
  - `https://formspree.io/f/your-id`
- В `index.html` замените ID Яндекс Метрики:
  - `ym(00000000, "init", ... )`
  - `https://mc.yandex.ru/watch/00000000`
- При необходимости замените `assets/images/photo-placeholder.svg` на реальное фото.

## Проверка

Откройте `index.html` в браузере и убедитесь, что:

- Все секции отображаются корректно на мобильном и десктопе.
- Форма отправляется в Formspree.
- После отправки появляется сообщение об успешной отправке.
