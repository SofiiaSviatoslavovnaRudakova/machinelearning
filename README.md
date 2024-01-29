Введение

Прогнозирование связей - часто используемый метод в более широкой области анализа социальных сетей вероятных друзей пользователей в социальной сети (Kumar et al. 2020). Прогнозирование связей часто определяется как задача предсказания отсутствующих связей на основе наблюдаемых в данный момент данных .
Это можно кратко проиллюстрировать на примере социальных сетей, использованных в данном исследовании. Они имеют более высокую плотность по сравнению с другими сетями. Это может повысить эффективность предсказания временных связей, поскольку пары узлов в сетях, использованных в нашем исследовании, скорее всего, будут иметь больше общих соседей, предоставляя больше информации для модели предсказания связей под наблюдением. Таким образом, важно понимать связь между структурными характеристиками сети и эффективностью топологических признаков.
Общим подходом к прогнозированию временных связей является использование модели машинного обучения с контролем, которая использует несколько признаков для классификации отсутствующих или, в случае прогнозирования временных связей, появляющихся в будущем связей (de Bruin et al. 2021). Признаки обычно вычисляются для каждой пары узлов, которые (пока) не связаны между собой, на основе топологии сети (Kumar et al. 2020). Эти топологические признаки, по сути, рассчитывают балл сходства для пары узлов, где более высокое сходство означает большую вероятность того, что эта пара узлов должна быть соединена. К числу наиболее часто используемых топологических признаков, применяемых как в контролируемом, так и в неконтролируемом обучении, относятся общие соседи, коэффициент Адамика-Адара, коэффициент Жаккара.


В данном исследовании были использованы социальные сети с высокой плотностью, что способствует более эффективному прогнозированию связей. Для прогнозирования временных связей применяется модель машинного обучения с контролем, которая использует различные топологические признаки для классификации отсутствующих или будущих связей. Наиболее часто используемые топологические признаки включают общих соседей, коэффициенты Адамика-Адара и Жаккара, а также преимущественное вложение. 

