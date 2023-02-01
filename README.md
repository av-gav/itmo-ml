# itmo-ml
Online course "ML for Scientific Data Analysis"

* Часть визуализации переделана на plotly
* Исправлен баг с преобразованием даты в исходном наборе данных
* Добавлены столбцы dayofyear и hour для проверки сезонной зависимости температуры - выявлена автокоррелляция 
* Датасет подготовлен для тренировки моделей. Решаем 2 задачи - регрессию для температуры и классификацию для осадков
* Созданы базовые модели, использована линейная регрессия и дерево решений со стандартными гиперпараметрами для предсказания температуры. Для бинарной классификации - логистическая регрессия, для многоклассовой - дерево решений.
