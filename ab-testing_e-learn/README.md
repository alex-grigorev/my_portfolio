
# Анализ результатов A/B-тестирования e-learning продукта и расчет его метрик

Проанализировал целесообразность запуска новой версии продукта в сфере онлайн-образования, а также написал функции для пересчета его основных метрик по обновленным данным и построения графиков.
## Использованные библиотеки
pandas, numpy, seaborn, scipy, matplotlib, pingouin, pandahouse, requests, urllib


## В рамках проекта выполнил следующие задачи
1. Анализ результатов А/В-тестирования:
- загрузка данных с помощью API Яндекса;
- предварительное исследование данных, поиск ошибок, их обработка;
- подбор метрик для анализа в соответствии гипотезой эксперимента;
- расчет метрик (CR, ARPU, ARPPU) для тестовой и контрольной групп;
- оценка статистической значимости изменений метрик в группах;
- вывод о целесообразности запуска нововведения на всех пользователей.

2. Расчет метрик e-learning продукта с использованием SQL (оптимизация запроса, CTE, case-конструкции).

3. Написание python-функций для автоматизации расчета метрик и их визуализации (подгрузка дополнитльных данных, их подготовка, расчет метрик и построение графиков).