# Прогнозирование оттока клиента Банка


[ipynb](https://github.com/Alexandra1624/07_forecasting_customer_churn/blob/main/07_forecasting_customer_churn.ipynb)

## Описание проекта

Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.


## Навыки и инструменты

- ![](https://img.shields.io/badge/-Python-bgreen)
- ![](https://img.shields.io/badge/-Pandas-blue)
- ![](https://img.shields.io/badge/-Nympy-B8860B)
- ![](https://img.shields.io/badge/-Matplotlib-violet)
- ![](https://img.shields.io/badge/-Seaborn-teal)
- ![](https://img.shields.io/badge/-Scikit--learn-808000)
- ![](https://img.shields.io/badge/-Phik-556B2F)

## Вывод

Проведен анализ данных, который показал дисбаланс целевого признака. 

Была проведена проверка моделей без учета дисбаланса и с улучшением качества модели за счет трех методов:

1. Взвешивание классов
2. Увеличение выборки (upsampling)
3. Уменьшение выборки (downsampling)

Применяя эти методы удалось значительно повысить F1-меру для модели ***Логистической регрессии***.

Наилучший результат был получен при увеличении выборки для ***Случайного леса***. 
