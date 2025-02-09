# Laba4_CI-CD

1. Плохие практики в CI/CD

В процессе разработки CI/CD встречаются ошибки, которые могут привести к проблемам в безопасности, надежности и поддерживаемости системы.

1.1. Жёстко закодированные секреты
Почему это плохо?

Любой, у кого есть доступ к коду, увидит пароли и API-ключи.
Секретные данные могут попасть в публичный репозиторий.
1.2. Игнорирование ошибок
Почему это плохо?

Если зависимость не установилась или тесты упали, но деплой всё равно продолжается — это ломает продакшен.
1.3. Монолитный и неструктурированный скрипт
Почему это плохо?

Скрипт CI/CD трудно поддерживать и отлаживать.
При изменениях легко что-то сломать.
1.4. Логирование чувствительных данных
Почему это плохо?

Логи могут попасть в публичное пространство и раскрыть секретные данные.
1.5. Отсутствие проверки перед деплоем
Почему это плохо?

Если код содержит ошибки или уязвимости, он сразу попадёт в прод.
