# Ecom Ops Dashboard

Production-grade React/Next.js pet-project для портфолио senior frontend developer.

## Идея проекта

- **Продукт:** операционная платформа для e-commerce команд.
- **Что решает:** помогает быстро находить просадки маржи и инциденты каталога, запускать промо и контролировать влияние на юнит-экономику.
- **Для кого:** operations manager, category manager, performance analyst.
- **Ключевая ценность:** меньше времени на ручной анализ и быстрее принятие решений по проблемным зонам продаж.

## MVP scope

- Dashboard KPI и тренды маржи
- Anomaly Explorer с drill-down
- Incident Management с optimistic updates
- Promotion Planner с валидацией
- Saved Views и shareable URL state

Стартовый фронтенд-проект на `Next.js 16` c `App Router`, `React 19`, `TypeScript` и `Tailwind CSS 4`.

## Стек проекта

- `next@16.2.1`
- `react@19.2.4`
- `typescript@5`
- `tailwindcss@4`
- `eslint@9` + `eslint-config-next`
- `prettier@3`
- `husky@9` + `lint-staged`

## Требования

- `Node.js >= 20.9.0`
- `npm` (в проекте используется `package-lock.json`)

## Быстрый старт

```bash
npm install
npm run dev
```

Приложение будет доступно по адресу: [http://localhost:3000](http://localhost:3000).

## Скрипты

- `npm run dev` — запуск dev-сервера
- `npm run build` — production-сборка
- `npm run start` — запуск production-сервера
- `npm run lint` — проверка ESLint (с `--max-warnings=0`)
- `npm run typecheck` — проверка TypeScript без эмита
- `npm run format` — автоформатирование Prettier
- `npm run format:check` — проверка форматирования

## Структура проекта

```text
src/
  app/
    layout.tsx
    page.tsx
    globals.css
```

- `src/app/layout.tsx` — корневой layout и метаданные приложения
- `src/app/page.tsx` — главная страница
- `src/app/globals.css` — глобальные стили и подключение Tailwind CSS

## Процесс разработки

1. Изменяйте страницы и компоненты внутри `src/`.
2. Запускайте `npm run lint` и `npm run typecheck` перед коммитом.
3. Форматируйте код через `npm run format`.
4. Husky и lint-staged выполнят проверки на этапе `pre-commit`.

## Полезные ссылки

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
