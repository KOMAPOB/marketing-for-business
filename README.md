# ПроДвижение

Одностраничный сайт маркетингового агентства на Astro для публикации на Netlify.

## Локальный запуск

```bash
npm install
npm run dev
```

## Сборка

```bash
npm run build
npm run preview
```

## Netlify

- Build command: `npm run build`
- Publish directory: `dist`
- Forms: форма `lead` использует Netlify Forms
- Домен: `marketing-for-business.ru`

## Аналитика

Добавьте переменные окружения в Netlify:

- `PUBLIC_GA_ID` для Google Analytics
- `PUBLIC_YANDEX_METRIKA_ID` для Яндекс Метрики

Если значения пустые, скрипты аналитики не подключаются.
