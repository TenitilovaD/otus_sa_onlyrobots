# 2.5. Границы проекта

Заказчиком обозначены ключевые риски проекта:
  1) выход за бюджет, 
  2) выход за пределы целевого срока реализации проекта,
  3) нет референсов, чтобы избежать типичных ошибок, поэтому высокие технологические риски: есть риск, что настроить роботизированную линию производства не получится.

В связи с высокими рисками при реализации полного проекта принято решение реализовать пилотный запуск, выполнив необходимые и достаточные работы для настройки роботизированный линии и ее интеграции в существующие бизнес-процессы и IT-архитектуру. Требования к системе описаны из расчета реализации пилотного проекта на **1 ресторан в городе-миллионнике Москва** и достижения [метрик, описанных в разделе 2.3. Метрики]. 

  [метрик, описанных в разделе 2.3. Метрики]:https://tenitilovad.github.io/otus_sa_onlyrobots/metrics/

В **нефункциональные требования** заложены возможности **для масштабирования** решения на остальные рестораны сети в случае успешного запуска пилотного проекта.

Требования описаны только в части роботизации производства кухни и **замены персонала в количестве 16 человек**. Дальнейшее сокращение операционных расходов и сокращение кассиров следует рассматривать в отдельном проекте.

В проекте предусмотрено **переиспользование и/или взаимодействие с существующими компонентами** IT-ландшафта:
  
  - система оформления заказов через терминал в зале ресторана,
  - система оформления заказов через мобильное приложение,
  - система оплаты заказов,
  - система лояльности,
  - система учета продаж,
  - система учета остатков полуфабрикатов,
  - система управления меню и товарами.

Подробнее границы разрабатываемой ИС и ее взаимодействие с существующим IT-ландшафтом описаны в [разделе 5. Компонентная архитектура].

  [разделе 5. Компонентная архитектура]:https://tenitilovad.github.io/otus_sa_onlyrobots/architecture/
