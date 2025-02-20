# Реализация "cat" на C

Программа использует `stdin` для ввода и `stdout` для вывода текста. Если указать файл (например, `./program file.txt`), покажет его содержимое, как `cat`.

## Функции
- `main`: Обрабатывает аргументы (`argc`, `argv`).
- `filecopy`: Копирует данные из файла или `stdin` в `stdout`.

## Использование
- Без аргументов: `./program` (ввод через `stdin`).
- С файлом: `./program file.txt`.
- С перенаправлением: `./program < input.txt > output.txt`.

## Clone repo
git apt update git apt install make sudo make all cd .build/ chmod +x program ./program
