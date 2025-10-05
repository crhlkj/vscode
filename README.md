## Config

```json
{
    // ==================== АВТОСОХРАНЕНИЕ И ФАЙЛЫ ====================
    "files.autoSave": "afterDelay",
    "files.trimTrailingWhitespace": true, // Удалять пробелы в конце строк при сохранении
    "files.insertFinalNewline": true, // Добавляет пустую строку в конец файла


    // ==================== ШРИФТ И ТЕКСТ ====================
    "editor.fontFamily": "'Fira Code', monospace", // FiraCode
    "editor.fontSize": 15,
    "editor.tabSize": 5,
    "editor.fontLigatures": true, // Включает лигатуры для Fira Code (стрелки → вместо =>)


    // ==================== АНИМАЦИИ И ПОВЕДЕНИЕ КУРСОРА ====================
    "editor.cursorSmoothCaretAnimation": "on", // Плавное движение курсора
    "editor.cursorBlinking": "phase", // Плавное мигание курсора
    "editor.smoothScrolling": true, // Плавная прокрутка
    "editor.mouseWheelZoom": true, // Zoom колесиком мыши (Ctrl+колесо)
    "editor.cursorStyle": "line", // Стиль курсора (line, block, underline)


    // ==================== НУМЕРАЦИЯ СТРОК И СВОРАЧИВАНИЕ ====================
    "editor.lineNumbers": "relative", // Относительные номера строк (очень удобно!)
    "editor.foldingHighlight": true, // Подсвечивать свернутые регионы
    "editor.lineHighlightBackground": "#1073cf2d", // Цвет подсветки текущей строки
    "editor.lineHighlightBorder": "#1073cf0d", // Граница подсветки строки
    "editor.renderLineHighlight": "all", // Подсвечивает всю строку, а не только текст



    // ==================== ПОДСКАЗКИ И ИНТЕЛЛЕКТУАЛЬНАЯ ПОМОЩЬ ====================
    "editor.parameterHints.enabled": true, // Подсказки параметров функций
    "editor.hover.above": false, // Показывать ховер под элементом
    "editor.inlayHints.enabled": "on", // Встроенные подсказки в коде
    "editor.quickSuggestions": { // Умные подсказки для разных контекстов
        "strings": true,
        "comments": true,
        "other": true
    },


    // ==================== ТЕРМИНАЛ ====================
    "terminal.integrated.fontSize": 14, // Размер шрифта в терминале
    "terminal.integrated.defaultProfile.windows": "PowerShell", // Профиль терминала по умолчанию (Windows)
    "terminal.integrated.cursorBlinking": true, // Мигающий курсор в терминале


    // ==================== ФОРМАТИРОВАНИЕ И СКОБКИ ====================
    "editor.formatOnSave": true, // Автоматически форматировать код при сохранении
    "editor.guides.indentation": true, // Показывает направляющие для отступов
    "editor.bracketPairColorization.enabled": true, // Подсвечивать парные скобки разными цветами
    "editor.bracketPairColorization.independentColorPoolPerBracketType": true, // Цвета для парных скобок
    "editor.guides.bracketPairs": true, // Показывать направляющие для парных скобок


    // ==================== ПОДСВЕТКА И НАВИГАЦИЯ ====================
    "editor.occurrencesHighlight": "singleFile", // Подсвечивать вхождения слова
    "editor.selectionHighlight": true, // Подсвечивать другие вхождения выделенного текста
    "editor.wordBasedSuggestions": "allDocuments", // Умные подсказки на основе слов
    "editor.links": false, // Отключает кликабельные ссылки в коде (меньше мусора)


    // ==================== ИНТЕРФЕЙС ====================
    "editor.minimap.enabled": true, // Отключить мини-карту
    "workbench.editor.highlightModifiedTabs": true, // Подсвечивает измененные вкладки
    "workbench.startupEditor": "none", // Не открывает ничего при запуске


    // ==================== GIGACODE РАСШИРЕНИЕ ====================
    "gigacode.lookupPriority": true,
    "gigacode.common.wholeLineReplacement": true,


    // ==================== СИНХРОНИЗАЦИЯ ====================
    "settingsSync.ignoredSettings": [],


    // ==================== ЧАТ И AI ====================
    "chat.disableAIFeatures": true,


    // ==================== C++ НАСТРОЙКИ ====================
    "C_Cpp.default.intelliSenseMode": "windows-gcc-x64",
    "C_Cpp.default.compilerPath": "D:/msys64/ucrt64/bin/gcc.exe",
    "C_Cpp.autocomplete": "default",
    "C_Cpp.errorSquiggles": "enabled",


    // ==================== ДЛЯ ERROR LENS ====================
    "errorLens.enabled": true,
    "errorLens.fontSize": "0.85em",
}
```
