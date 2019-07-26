# Работа с кодами ответов HTTP для "1С:Предприятие 8"

После проверки пары проектов с помощью [BSL Language Server](https://1c-syntax.github.io/bsl-language-server/) захотелось избавиться от "магических чисел" в коде при работе с HTTP-запросами. Использование данной небольшой библиотеки позволяет сделать работу с кодами ответов HTTP нагляднее и по стандартам 1С.

Рекомендую к ознакомлению и библиотеку [КоннекторHTTP](https://github.com/vbondarevsky/Connector) by [Vladimir Bondarevskiy](https://www.linkedin.com/in/vbondarevsky/).

## Возможности

Основные возможности библиотеки:

- Получение числовых значений кодов ответа по краткому идентификатору;
- Получение кратких идентификаторов по числовому коду ответа;
- Получение представлений кодов ответа;
- Проверка значений переменных через соответствующие кодам ответов функции;
- Определения принадлежности кода ответа к группе кодов (информационные, ошибка клиента, ошибка сервера и т.д.);

## Требования

Платформа **8.3.10** и выше.

## Использование

Скопируйте все общие модули к себе в конфигурацию.

Обработка Тесты для работы библиотеки не нужна и служит только для самодиагностики.

Работа осуществляется через едниный программный интерфейс общего модуля КодОтветаHTTP как в клиентском, так и в серверном контекстах.

## Примеры

//TODO