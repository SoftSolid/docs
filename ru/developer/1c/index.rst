*****************************
CommerceML (1С). Схема работы
*****************************

Описание процесса обмена данными интернет-магазина с ситемами учета: 1С, МойСклад, Class365.

Инструкции по модификации и расширению модуля обмена на платформе CS-Cart.

Обмен данными осуществляется в формате CommerceML 2. 

При обмене данными между системой учета и CS-Cart, **инициатором обмена данных всегда выступает система с которой выполняется обмен**. 

Обработка данных на стороне интернет-магазина выполняется через скрипт ``/app/addons/rus_exim_1c/controllers/frontend/exim_1c.php``.

Процесс обмена, модификация и тестирование
==========================================

.. toctree::
    :maxdepth: 3
    :glob:

    catalog
    orders
    check_list

Структура XML файлов обмена данными
===================================

.. toctree::
    :maxdepth: 3
    :glob:

    catalogxml
    ordersxml



