/project-name/               ← Корневая папка проекта
├── public/                  ← Статичные файлы
│   └── index.html           ← HTML-файл
│
├── src/                     ← Вся логика
│   ├── main.jsx             ← Точка входа
│   ├── App.jsx              ← Главный компонент
│   ├── App.css              ← Глобальные стили
│   └── components/          ← Компоненты
│       ├── Header.jsx       ← Шапка
│       ├── Header.css       ← Стили для Header
│       ├── Main.jsx         ← Основной контент
│       ├── Main.css         ← Стили для Main
│       ├── Footer.jsx       ← Подвал
│       └── Footer.css       ← Стили для Footer
│
├── package.json             ← Зависимости проекта
└── vite.config.js           ← Конфигурация сборщика (если Vite)
