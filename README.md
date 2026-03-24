# Практична робота — (верстка сайту)

> Автор: **Makarenko Tymur**

## Структура проєкту

```
📁 PRACTICE/
│
├── index.html               ← Головна сторінка
├── README.md                ← Документація проєкту
│
├── 📁 pages/                ← Внутрішні сторінки
│   ├── tomato_all.html      ← Сторінка гібридів томатів
│   └── not_ready.html       ← Заглушка (Under Development)
│
├── 📁 css/
│   ├── reset.css            ← Скидання стилів браузера
│   ├── variables.css        ← CSS змінні та @font-face
│   ├── header.css           ← Стилі шапки (у т.ч. білий варіант)
│   ├── middle.css           ← Спільні секції (Vision/Mission)
│   ├── footer.css           ← Стилі підвалу
│   └── tomato_all.css       ← Специфічні стилі для сторінки томатів
│
└── 📁 assets/
    ├── 📁 fonts/            ← Локальні шрифти (Roboto Slab)
    └── 📁 images/
        ├── 📁 icons/        ← SVG та растрові іконки
        ├── 📁 tomatoes/     ← Фотографії товарів (гібриди томатів)
        ├── bg-logo.png
        ├── hero-bg.jpg
        └── ... (інші медіафайли)
```

## Що реалізовано

- Використання article для карток товарів, blockquote для цитат.
- Реалізовано альтернативний варіант шапки з білим фоном та темним текстом для кращої читабельності на внутрішніх сторінках.
- Семантична HTML5-розмітка (`header`, `main`, `footer`, `section`, `article`, `nav`)
- CSS Custom Properties для кольорів, шрифтів та відступів
- Адаптивний дизайн (breakpoints: 1200 / 900 / 768 / 600 / 480px)
- Мобільне меню з `aria`-атрибутами
- CSS Grid для блоків Vision/Mission та Activities
- Flexbox для хедера, футера та іконок

---

<div align="center">
  <sub>Makarenko Tymur · Коледж · 2026</sub>
</div>
