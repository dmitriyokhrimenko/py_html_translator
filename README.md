# py_html_translator

```Алгоритм работы```

В настройках указываем путь к директории шаблонов и путь к директории переводов

Согласно внутренней структуре фреймворка и логике работы приложения, скрипт получает все шаблоны и парсит их. Находит не переведенный текст и пытается его перевести. 

`Поиск перевода происходит в следующем порядке:`
  1. Поиск в файлах переводов фреймворка (laravel)
  2. Поиск перевода в локальном хранилище - словаре приложения
  3. Перевод слова или предложения через АПИ google translate
  
  ![alt text](https://i.imgur.com/8lqDlns.png)