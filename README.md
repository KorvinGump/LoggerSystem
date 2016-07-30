# LoggerSystem
Система логирования написана с использованием ООП. Есть базовый класс, который наследуется каждым типом логера:
логер в консоль, файл и базу данных.
Проект написан в Netbeans с использованием сервера xampp.
Logger.php Базовый класс для всех типов логеров.
loggers - папка с классами для логирования в консоль, файл и базу данных.
tests - примеры тестов для логеров.
tests\console.php тест для логирования в консоль
tests\file.php тест для логирования в файл
tests\sql.php тест для логирования в базу данных
tests\combine.php смешанное логирование, используем сразу три типа логирования сразу
CreateDB.sql SQL скрипт для создания пустой базы данных.
test_db.sql - дамп базы данных
