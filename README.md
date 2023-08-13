# Сборка для вебпака 5+
### Сразу подключены:

- dev server 
- работа с html 
- работа с css / scss их нужно подключить в index.js(import './main.scss';
import './style.css';) 
- для работы со статичными файлами папка static
- подключены лоадеры и оптимизаторы изображений (png|jpg|jpeg|gif|svg)
- работа с реактом (components) b добавлены зависимости в index.js

### Для работы с конфигурацией установить:

  `npm i`

### 3 режима сборки:
  - "serve": "webpack serve --open --mode development",
  - "dev": "webpack --mode development",
  - "build": "webpack --mode production",

## Проект собирается в папку dist
 