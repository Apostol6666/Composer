# Composter

Сначала устанавливаем Apache, подключаем к нему php и скачиваем composter, который подключаем к php.

Делаем проект и подключаем в него composer, после ищем и подсоединяем нужные нам библиотеки:

1) Для работы с базами данных - 2 подключения, https://packagist.org/packages/lichtner/fluentpdo - быстрая и легкая библиотека PHP для быстрого создания запросов, работает с любыми таблицами, поддерживающими PDO подключение

2) Для работы с кешем в памяти для временного хранения сложных запросов к БД - Класс PHP Abstract Cache, система кэширования для уменьшения кол-ва запросов - https://packagist.org/packages/phpfastcache/phpfastcache

3) Для Формирования XLS-отчетов на основе данных - https://packagist.org/packages/deivisondc/csv-xls-report-generator

4) Для Формирования PDF-документы на основе данных - https://packagist.org/packages/phpoffice/phpword

5) Для Отправки SMS-сообщения для верификации пользователей - https://packagist.org/packages/doge-dev/laravel-sms-verification

6) Для Отправки E-mail-уведомления и рассылки для пользователей - https://packagist.org/packages/laravel/framework

7) Для Использования облачного хранилище AWS S3 - https://packagist.org/packages/aws/aws-sdk-php

8) Для Использования интеграция со службой доставки для расчета стоимости - https://packagist.org/packages/shiptor/shipping-calculator

9) Для Использования интеграция с социальными сетями для авторизации пользователей - https://packagist.org/packages/mad-web/laravel-social-auth

10) Данные о товарах регулярно отправляются в Яндекс.Маркет - https://packagist.org/packages/bukashk0zzz/yml-generator

11) Для Принименения онлайн-оплата от покупателей - https://packagist.org/packages/swedbank-spp/swedbank-payment-portal

12) Для Принименения средства тестирования (например, PHPUnit) - https://packagist.org/packages/phpunit/phpunit
