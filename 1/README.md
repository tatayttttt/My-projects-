Наша цель исследовать случайную прогулку :)

При решении задачи допускается использование только следующих библиотек: NumPy и Matpoltlib

Применение других библиотек запрещено.

Смоделируем случайную прогулку в 1000 шагов. На первом шаге мы находимся в точке 0, на следующем шаге в точке 1 или -1, с равной вероятностью, каждый последующий шаг прибавляет к предидущему с равной вероятностью 1 или -1. Визуализируем прогулку.

Рекомендация:

использовать значение np.random.seed(42) для получения идентичных результатов https://ru.wikipedia.org/wiki/Ответ_на_главный_вопрос_жизни,_вселенной_и_всего_такого https://www.youtube.com/watch?v=D5O0vqatpXg

Сначала получить ветор вида [0,1,1,1,-1,-1,1 ...], а уже затем искать кумулятивную сумму.

Задание 1. Найти максимальное и минимальное значение (глобальное) на траектории. Визуализировать эти точки на графике (желательно их подписать).

Задание 2. Найти значение индекса, начиная с которого будет сделано свыше 10 шагов в одну сторону. Визуализировать эти шаги на графике (достаночно другим цветом на графике выделить данный участок, желательно его подписать).

Задание 3. Найти значение индекса, с которого будет сделано максимальное количество шагов в одну сторону. Визуализировать эти шаги на графике (достаночно другим цветом на графике выделить данный участок, желательно его подписать).
