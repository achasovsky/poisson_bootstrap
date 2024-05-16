## Пуассоновский бутстрэп 
Cравнение средних значений двух выборок (уровень значимости - 0.05).

### Средние выборки

##### Выборка A (среднее 100, стд. отклонение 5, число элементов 1000)
<img src='img/c.png'>

##### Выборка B (среднее 95, стд. отклонение 5, число элементов 1000)
<img src='img/d.png'>

1000 элементов недостаточно для того, чтобы выявить различия в межгрупповых средних, равное 5% от среднего значения выборки А. <br>

<img src='img/poisson1.png'>

Верхний график - разность средних значений, на котором хорошо заметно отличие среднего от нуля, и ноль находится вне порогов значиости. 
Распределение средних имеет нормальную форму на уровне значимости 0.05 (p-value: 0.959).

На нижнем графике отображаются распредления средних значений выборок, полученных при сэмплировании.

Теперь сравним выборку А с выборкой, у которой среднее значение равно 85.

##### Выборка A (среднее 100, стд. отклонение 5, число элементов 1000)
<img src='img/c.png'>

##### Выборка C (среднее 85, стд. отклонение 5, число элементов 1000)
<img src='img/d.png'>

Теперь тест зафиксировал значимые различия. 

<img src='img/poisson2.png'>

### Большие выборки

Уведичим число элементов.

##### Выборка D (среднее 100, стд. отклонение 5, число элементов 5000)
<img src='img/a.png'>

##### Выборка E (среднее 95, стд. отклонение 5, число элементов 5000)
<img src='img/b.png'>

После увеличения числа элементов с 1000 до 5000 тест фиксирует значимые различия средних. 

<img src='img/poisson3.png'>












