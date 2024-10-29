# Проект: игровое мобильное приложение 

## Стек: 
Python, Pandas, Matplotlib, Seaborn, SciPy (kstest, anderson, levene, ttest_ind), Statsmodels (proportions_ztest), NumPy.

## Задачи: 
1. Написать функцию на **Python** для подсчета Retention игроков. 
2. Оценить какой набор акционных предложений в результате проведенного A/B-теста был лучше.
3. Выбрать метрики для оценки прошедшего события в игре.

## Реализация: 
1. Провел предварительный анализ и предобработку данных
2. Написал функцию для расчета Retention игроков
3. Посчитал такие метрики Conversion Rate, ARPPU, ARPU
4. Проанализированы результаты A/B теста с использованием статистических тестов в Python:
   - тест Колмогорова-Смирнова для проверки распределения данных,
   - тест Андерсона для проверки нормальности распределения,
   - тест Левена для проверки равенства дисперсий,
   - независимый T-тест для сравнения средних значений двух групп,
   - Z-тест пропорций для анализа долей успеха в двух группах
5. Визуализированы результаты с использованием библиотек seaborn и matplotlib.pyplot.

Проект следует рассматривать как учебный. 