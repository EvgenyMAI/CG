# Лабораторные работы по компьютерной графики и необходимые конфигурационные файлы к ним
Установка библиотеки `freeglut` для `ucrt64`:
```
pacman -S mingw-w64-ucrt-x86_64-freeglut
```

Способ выполнить компиляцию и запуск программы с помощью собственной комбинации клавиш
1. Откройте файл keybindings.json:
    - Нажмите Ctrl+Shift+P, введите Preferences: Open Keyboard Shortcuts (JSON) и выберите этот пункт.
2. Добавьте настройку для запуска задачи:
```
[
    {
        "key": "ctrl+shift+r", // или любое удобное сочетание
        "command": "workbench.action.tasks.runTask",
        "args": "Run"
    }
]
```