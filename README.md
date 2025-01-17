
# Очистка данных Windows - Скрипт BAT

Этот скрипт предназначен для очистки различных системных и пользовательских данных в операционной системе Windows. Он предлагает три уровня очистки: Минимальная, Средняя и Максимальная. Используйте этот скрипт для освобождения места на диске и удаления следов активности пользователя.

 clear_for_me24 -- скрипт от 07.08.2024 
 
 Очистка -- скрипт от 2020 года 

## Описание типов очистки

### 1. Минимальная Очистка

**Минимальная очистка** включает базовые операции по очистке данных. Этот режим подходит для быстрого освобождения места и удаления следов пользовательской активности.

**Что очищается:**
- **ShellBag**: Записи о папках и файлах, открытых через Проводник Windows.
- **RunMRU**: Список недавно введенных команд и приложений.
- **ComDlg32 OpenSaveMRU**: Записи о последних открытых и сохраненных файлах в диалоговых окнах.

### 2. Средняя Очистка

**Средняя очистка** включает все действия из Минимальной очистки, а также дополнительные операции для более глубокого удаления следов активности пользователя и системных данных.

**Что очищается дополнительно:**
- **UserAssist**: Информация о приложениях, которые были запущены пользователем.
- **AppCompatCache**: Данные о совместимости приложений.

### 3. Максимальная Очистка

**Максимальная очистка** предоставляет наиболее полное очищение системы. Этот режим наиболее эффективен для удаления всех возможных следов пользовательской активности и системных данных.

**Что очищается дополнительно:**
- **Журналы событий Windows**: Очищает все журналы событий (приложений, системные, безопасности).
- **DiagnosedApplications**: Записи о диагностике приложений.
- **История поиска**: Недавние запросы и результаты поиска.
- **Background Activity Moderator (BAM)**: Настройки фоновых активностей и задач.
- **AppCompatFlags**: Записи о слоях совместимости приложений.
- **Монтированные устройства**: Информация о недавно подключенных устройствах и их путях.

## Как использовать скрипт

1. **Создайте резервные копии**: Прежде чем запускать скрипт, создайте резервные копии важных данных.
2. **Запустите скрипт от имени администратора**: Для выполнения некоторых операций требуется запуск скрипта с правами администратора.
3. **Выберите тип очистки**: После запуска скрипта вам будет предложено выбрать тип очистки (1, 2 или 3). Введите соответствующий номер и нажмите Enter.

## Примечания

- **Права администратора**: Некоторые операции требуют прав администратора. Убедитесь, что вы запустили скрипт с достаточными привилегиями.
- **Влияние на систему**: Очистка может повлиять на работу системы и приложений, удаляя данные, которые могут быть использованы для диагностики или восстановления.

## Пример использования

1. Сохраните скрипт в файл с расширением `.bat`, например `clean_for_me24`.
2. Запустите файл `clean_for_me24` от имени администратора.
3. Выберите тип очистки, введя номер (1, 2 или 3) и нажмите Enter.
