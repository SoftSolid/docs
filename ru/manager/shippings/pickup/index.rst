Служба доставки Самовывоз
-------------------------

Описание
========

Служба доставки "Самовывоз"" позволяет указывать пункты выдачи заказов магазина и стоимость.

.. epigraph::

    Функциональные возможности:

    *   Указание пунктов выдачи заказов
    *   Указание стоимости доставки для каждого пункта выдачи заказов

Настройка
=========

1.  Установите модуль "Самовывоз".

    .. note::

        Модуль используется совместно с модулем "Поиск ближайших магазинов".

    .. fancybox:: img/pickup_shippings001.png
        :alt: pickup

2.  Для создания пунктов выдачи заказов перейдите в меню "Модули" - "Расположение магазина". В окне "Расположение магазина" для добавления нового магазина нажмите на кнопку **+**.

    .. fancybox:: img/pickup_shippings002.png
        :alt: pickup

3.  В окне "Новое местоположение магазина" заполните поля

    .. list-table::
        :stub-columns: 1
        :widths: 10 30

        *   -   Название
            -   Название точки выдачи заказов

        *   -   Страна
            -   Страна пункта выдачи заказов

        *   -   Город
            -   Город ПВЗ

        *   -   Координаты
            -   Координаты для отображения ПВЗ на карте

        *   -   Доступен для самовывоза
            -   При отключении, ПВЗ отображаться не будет

        *   -   Дополнительный сбор
            -   Дополнительная стоимость доставки

        *   -   Адрес
            -   Адрес ПВЗ

        *   -   Телефон
            -   Телефон ПВЗ

        *   -   Режим работы
            -   Режим работы ПВЗ

        *   -   Пункты назначения
            -   Расположение пункта выдачи заказов

    .. note::

        ПВЗ отображается в зависимости от выбранного "Пункта назначения". "Пункт назначения" отображается после сохранения ПВЗ.

    .. fancybox:: img/pickup_shippings003.png
        :alt: pickup

    .. fancybox:: img/pickup_shippings004.png
        :alt: pickup

4.  Создайте новый способ доставки (:doc:`см. "Создание способа доставки" </manager/shippings/general/settings/index>`).

    Настройки нового способа доставки:

    .. list-table::
        :stub-columns: 1
        :widths: 10 30

        *   -   Расчет тарифа
            -   В режиме реального времени

        *   -   Служба доставки
            -   Самовывоз

        *   -   Другие настройки
            -   На ваше усмотрение

    .. fancybox:: img/pickup_shippings005.png
        :alt: pickup

5.  Выполните настройку нового способа доставки во вкладке "Настроить".

    Необходимые настройки:
    
    *   Переместите из списка "Доступные магазины" пункты самовывоза в список "Выбранные магазины".

    *   Сортировка пунктов самовывоза.

    *   Способ отображения пунктов самовывоза при оформлении заказа.

    .. fancybox:: img/pickup_shippings006.png
        :alt: pickup

6.  Проверьте работу способа доставки.

    .. fancybox:: img/pickup_shippings007.png
        :alt: pickup

7.  При переходе на детали заказа, для способа доставки "Самовывоз" будет отображаться карта с указанием ПВЗ.

    .. fancybox:: img/pickup_shippings008.png
        :alt: pickup

(:doc:`Больше о способах доставки </manager/shippings/index>`)

