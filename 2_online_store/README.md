# Исследование данных крупного интернет магазина

## Данные

Файл `hypothesis.csv`:
* `Hypothesis` — краткое описание гипотезы;
* `Reach` — охват пользователей по 10-балльной шкале;
* `Impact` — влияние на пользователей по 10-балльной шкале;
* `Confidence` — уверенность в гипотезе по 10-балльной шкале;
* `Efforts` — затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.

Файл `orders.csv`:
* `transactionId` — идентификатор заказа;
* `visitorId` — идентификатор пользователя, совершившего заказ;
* `date` — дата, когда был совершён заказ;
* `revenue` — выручка заказа;
* `group` — группа A/B-теста, в которую попал заказ.

Файл `visitors.csv`:
* `date` — дата;
* `group` — группа A/B-теста;
* `visitors` — количество пользователей в указанную дату в указанной группе A/B-теста

## Задачи

Был подготовлен список гипотез для увеличения выручки крупного интернер-магазина.
* Необходимо приоритизировать гипотезы.
* Запустить A/B-тест и проанализировать результаты.

## Используемые библиотеки

*pandas*, *scipy*, *numpy*, *datetime*, *matplotlib*