# SHNAPCS
software and hardware new automated process control systems

# Архитектурные требования к компонентам системы:
* сервер для работы с контроллером (на начальном этапе на базе EasyServer)
* сервер приложений для веб-клиентов (может горизонтально масштабироваться)
* веб-клиент для браузеров Chrome и Mozilla
* балансировщик нагрузки (Nginx)
* сервер отчетов
* сервер логирования

# Функциональные требования:
* поддержка faceplate для объектов
* наследование объектов
* группировка объектов
* объектная модель базы каналов
* история объекта (проигрыватель на основе протокола)
* единая среда параллельной разработки проектов на базе веб-технологий
* поддержка скриптов для бизнес-логики (lua, java, js, python, jexl)
* встроенный отладчик скриптов
* поддержка векторной графики
* расширяемость элементов управления
* кроссплатформенность решения
* поддержка протоколов: OPC-UA, Modbus, Snap7
* интеграция с EPLAN
* журнал событий
* генератор отчетов
* авторизация, уровень доступа, администрирование
* возможность сравнения изменений в проектах
* CI/CD, тестирование и быстрое развертывание проектов
  
