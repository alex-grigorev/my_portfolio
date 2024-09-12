
# Дашборд для отдела продаж онлайн магазина

Идея дашборда: отобразить изменение ключевых метрик (выручка и число активных пользователей) за последний месяц, основные тенденции в динамике общих показателей (MAU, AOV, ARPU, количество заказов) в разбивке по странам, чтобы выявить основные направления, на которые нужно обратить больше внимания.

## Решение
[Готовый дашборд на Redash](http://redash.lab.karpov.courses/public/dashboards/9n4GNtZTnf4TShvj2uR0OJwNRB4XMMQTxflUuTUc?org_slug=default)
или в случае неработающей ссылки [скриншоты готового дашборда](https://github.com/alex-grigorev/my_portfolio/tree/main/retail_dashboard/screenshots)

## Использованные инструменты:
SQL, Redash


## В рамках проекта выполнил следующие задачи:

- определил основные показатели (KPI), которые отражали бы текущее состояние бизнеса в целом и в разных странах, а также его динамику;
- написал SQL-запросы к каждой метрике;
- определил оптимальные форматы визуализации метрик на дашборде и реализовал их посредством Redash.
## На основе построенной визуализации можно сделать следующие выводы
- Почти все наши продажи в течение года приходятся на Европу, подавляющий объем продаж (более 80%) - в Великобритании. все основные показатели (выручка, MAU, AOV, количество заказов) колебались в районе +- 30% от уровня декабря 2010 г. заметен постепенный их рост в течение осени 2011 г., что значительно связано, вероятно, с приходом новых покупателей (MAU) в сентябре-ноябре и в основном - из Великобритании. также вероятно, что кратковременный рост продаж и числа покупателей к ноябрю обусловлен распродажами в "черную пятницу", которая обычно проводится в это время. 

- Наибольшую среднюю выручку (ARPU) приносит пользователь из Эйре (кажется, их 2), Нидерландов, Сингапура и Австралии. при этом пользователи из этих стран приносят около 3% общей выручки каждый, их показатели ARPU и AOV имели скачки за год - возможно, необходимо более индивидуально изучать этих клиентов и корректировать работу с ними. 

- В отличие от других метрик, ARPU за год в общем имел тренд к росту на ~30%. 

- Наибольшим спросом пользуются товары: "PAPER CRAFT , LITTLE BIRDIE", "REGENCY CAKESTAND 3 TIER", "WHITE HANGING HEART T-LIGHT HOLDER". может потребоваться более детальный анализ спроса на товары по странам.

- Интерес вызывает резкий скачок ARPU в Нидерладнах в августе 2011 г.

- Однако, уже в декабре 2011 г. основные показатели упали примерно в 2 раза по отн. к прошлому месяцу или сократились на ~25% по отн. к концу прошлого года, что тоже может быть эхом "черной пятницы" в ноябре. за ноябрь-декабрь 2011 г. резкий отток покупателей произошел в Великобритании (почти в 2 раза),  Греции, Италии, Исладии, Нидерландах и Испании - это тоже имеет смысл изучить детальнее.
