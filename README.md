# Системная Утилита на C#

🔧 **Системная Утилита** - это консольное приложение на C#, которое выполняет функции мониторинга и управления ресурсами ПК под MacOS. Оно демонстрирует знание системного программирования и взаимодействия с операционной системой без использования интернет-соединения.

## Функциональные Возможности

### 1. Мониторинг Системных Ресурсов
- **Процессор**: Отображение текущей загрузки процессора в реальном времени с графическим представлением (например, прогресс-баром).
- **Оперативная Память**: Информация о общем объеме, используемой и свободной памяти. Возможность очистки неиспользуемой памяти.
- **Дисковые Накопители**: Список доступных дисков с указанием их объема, свободного и занятого пространства. Предупреждение при достижении заданного порога заполнения.

### 2. Управление Процессами
- Вывод списка всех запущенных процессов с деталями: имя процесса, идентификатор (PID), потребляемая память и CPU.
- Завершение процесса по PID или имени.
- Фильтрация процессов по имени или потреблению ресурсов.

### 3. Файловый Менеджер
- Древовидное отображение каталогов и файлов с возможностью отображения скрытых файлов.
- Операции: копирование, перемещение, удаление, переименование файлов и папок; создание новых каталогов.
- Поиск файлов по имени, расширению, размеру или дате изменения.

### 4. Управление Службами Mac
- Отображение списка служб с их статусом (запущена, остановлена, приостановлена).
- Возможность запуска и остановки выбранных служб.
- Просмотр свойств службы (тип запуска, путь к исполняемому файлу).

### 5. События Системы
- Чтение и отображение событий из системного журнала Windows с фильтрацией по типу, источнику и идентификатору события.
- Экспорт выбранных событий в файл (TXT или CSV).

### 6. Настройки
- Просмотр и удаление лог-файла с журналом действий пользователя (Info, Warning, Error).

## Многопоточность
- Обеспечивает плавную работу приложения при длительных операциях.
- Использует отдельные потоки для ввода-вывода и обработки данных с индикаторами прогресса.

