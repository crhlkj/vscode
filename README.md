{
  // ┌──────────────────────────────────────────────┐
  // │                Ш Р И Ф Т Ы                   │
  // └──────────────────────────────────────────────┘
  "editor.fontSize": 16,                           // Размер шрифта в редакторе
  "editor.lineHeight": 24,                         // Высота строки
  "editor.letterSpacing": 0.5,                     // Расстояние между символами
  "editor.fontFamily": "'Fira Code', monospace",   // Тип шрифта
  "editor.fontLigatures": true,                    // Включение лигатур (соединений символов)

  // ┌──────────────────────────────────────────────┐
  // │        Т А Б У Л Я Ц И Я   И   Ф О Р М А Т   │
  // └──────────────────────────────────────────────┘
  "editor.tabSize": 4,                             // Количество пробелов в табуляции
  "editor.insertSpaces": true,                     // Заменяет табуляцию на пробелы
  "editor.renderWhitespace": "boundary",           // Отображает пробелы только на границах
  "editor.guides.indentation": true,               // Показывает линии отступов
  "editor.guides.bracketPairs": true,              // Подсвечивает пары скобок
  "editor.guides.highlightActiveIndentation": true,// Подсветка активного уровня отступа
  "editor.autoIndent": "advanced",                 // Автоматическая индентация
  "editor.detectIndentation": true,                // Автоматическое определение отступов
  "editor.autoClosingBrackets": "always",          // Автоматическое закрытие скобок
  "editor.autoClosingQuotes": "always",            // Автоматическое закрытие кавычек
  "editor.autoClosingDelete": "always",            // Удаление парных символов при удалении одного
  "editor.autoSurround": "languageDefined",        // Автоматическое окружение выражений

  // ┌──────────────────────────────────────────────┐
  // │           В И Д   И   П О В Е Д Е Н И Е      │
  // └──────────────────────────────────────────────┘
  "editor.lineNumbers": "relative",                // Относительная нумерация строк
  "editor.renderLineHighlight": "all",             // Подсветка текущей строки
  "editor.occurrencesHighlight": "singleFile",     // Подсветка совпадений в файле
  "editor.matchBrackets": "always",                // Подсветка пар скобок
  "editor.bracketPairColorization.enabled": true,  // Различение скобок цветом
  "editor.folding": true,                          // Возможность сворачивания кода
  "editor.glyphMargin": true,                      // Маржа для иконок (например, глюков)
  "editor.tabCompletion": "on",                    // Автозавершение через Tab
  "editor.acceptSuggestionOnEnter": "on",          // Принятие подсказки при Enter
  "editor.hover.enabled": true,                    // Подсказки при наведении
  "editor.suggestOnTriggerCharacters": true,       // Подсказки при вводе триггерных символов
  "editor.parameterHints.enabled": true,           // Подсказки параметров функций
  "editor.inlineSuggest.enabled": true,            // Инлайновые подсказки
  "editor.quickSuggestions": {
    "other": true,                                 // Быстрые подсказки для кода
    "comments": true,                              // Для комментариев
    "strings": true                                // Для строк
  },
  "editor.suggest.localityBonus": true,            // Приоритет локальных подсказок

  // ┌──────────────────────────────────────────────┐
  // │                Н А В И Г А Ц И Я             │
  // └──────────────────────────────────────────────┘
  "editor.minimap.enabled": true,                  // Миникарта кода
  "editor.minimap.renderCharacters": true,         // Не отображать символы на миникарте
  "editor.stickyScroll.enabled": true,             // Липкий скролл для сайдбара
  "editor.overviewRulerBorder": true,              // Отключение границы у overview ruler
  "editor.scrollBeyondLastLine": true,             // Не прокручивать за последнюю строку
  "editor.cursorSurroundingLines": 5,              // Количество строк вокруг курсора
  "editor.cursorSurroundingLinesStyle": "all",
  "editor.wordWrap": "on",                         // Перенос строк

  // ┌──────────────────────────────────────────────┐
  // │                И Н Т Е Р Ф Е Й С             │
  // └──────────────────────────────────────────────┘
  "workbench.startupEditor": "welcomePage",        // Стартовая страница
  "workbench.colorTheme": "Monokai",               // Тема интерфейса
  "workbench.iconTheme": "material-icon-theme",    // Тема иконок
  "workbench.productIconTheme": "material-product-icons", // Тема продуктовых иконок
  "editor.cursorStyle": "line-thin",               // Стиль курсора (тонкая линия)
  "editor.cursorBlinking": "expand",               // Режим мигания курсора
  "editor.smoothScrolling": true,                  // Плавная прокрутка
  "editor.cursorSmoothCaretAnimation": "on",       // Плавная анимация курсора
  "editor.foldingStrategy": "auto",                // Стратегия сворачивания кода
  "window.zoomLevel": 0,                           // Уровень масштабирования
  "workbench.editor.highlightModifiedTabs": false, // Подсветка изменённых вкладок

  // ┌──────────────────────────────────────────────┐
  // │        С О Х Р А Н Е Н И Е   И   Ф О Р М А Т │
  // └──────────────────────────────────────────────┘
  "editor.formatOnSave": true,                     // Форматировать при сохранении
  "editor.formatOnPaste": true,                    // При вставке
  "editor.formatOnType": true,                     // Автосохранение после задержки
  "editor.trimAutoWhitespace": true,               // Удалять лишние пробелы
  "files.insertFinalNewline": true,                // Добавлять пустую строку в конце файла

  // ┌──────────────────────────────────────────────┐
  // │                Т Е Р М И Н А Л               │
  // └──────────────────────────────────────────────┘
  "terminal.integrated.fontSize": 15,                         // Размер шрифта терминала
  "terminal.integrated.shellIntegration.enabled": true,       // Интеграция shell
  "terminal.integrated.cursorBlinking": true,                 // Мигание курсора
  "terminal.integrated.gpuAcceleration": "on",                // GPU-ускорение
  "terminal.integrated.defaultProfile.windows": "PowerShell", // Профиль для Windows
  "terminal.integrated.defaultProfile.linux": "bash",         // Для Linux
  "terminal.integrated.defaultProfile.osx": "zsh",            // Для macOS

  // ┌──────────────────────────────────────────────┐
  // │                О Т Л А Д К А                 │
  // └──────────────────────────────────────────────┘
  "debug.console.fontSize": 15,                    // Размер шрифта в консоли отладки
  "debug.onTaskErrors": "showErrors",              // Отображать ошибки задач

  // ┌──────────────────────────────────────────────┐
  // │                И И - Ф У Н К Ц И И           │
  // └──────────────────────────────────────────────┘
  "chat.disableAIFeatures": true,                  // Отключено для совместимости с gigacode
  "gigacode.common.wholeLineReplacement": true,    // Замена целой строки
  "gigacode.inlineHints": true,                    // Инлайновые подсказки
  "gigacode.inlineCompletionColor": "blue",        // Цвет подсказок
  "gigacode.lookupPriority": true,                 // Приоритет поиска
  "gigacode.showCompletionsInline": true,          // Показывать подсказки inline

  // ┌──────────────────────────────────────────────┐
  // │                E R R O R   L E N S           │
  // └──────────────────────────────────────────────┘
  "errorLens.enabled": true,                       // Включить Error Lens
  "errorLens.fontWeight": "bold",                  // Жирный шрифт ошибок
  "errorLens.fontSize": "12px",                    // Размер шрифта
  "errorLens.gutterIconsEnabled": true,            // Иконки в gutter
  "errorLens.onSave": false,                       // Не показывать ошибки после сохранения

  // ┌──────────────────────────────────────────────┐
  // │          Д О П О Л Н И Т Е Л Ь Н О           │
  // └──────────────────────────────────────────────┘
  "settingsSync.ignoredSettings": [],              // Игнорируемые настройки синхронизации
  "explorer.confirmDragAndDrop": false,            // Не спрашивать подтверждение при перетаскивании
  "workbench.colorCustomizations": {
    "editorGhostText.foreground": "#2CD7F6"      // Цвет ghost-текста
  }
}
