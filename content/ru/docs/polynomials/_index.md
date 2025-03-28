+++
title = 'Многочлены'
weight = 3
bookFlatSection = true
+++

Для интерполяции функций часто используются *интерполяционные многочлены*.

*Интерполяционные многочлены* представляют из себя полиномы вида $a_0 + a_1x + a_2x^2 + \cdots$, проходящие через заданный набор узловых точек и зависящие только от координат этих точек.

Пусть заданы $(n+1)$ точек с индексами с $0$ по $n$ включительно: $(x_k, y_k),{}_{k \in \left\{0, ..., n\right\}}$.

При интерполяции многочленами обычно стоят многочлен степени $n$, потому что через $(n+1)$ точку проходит *единственный* многочлен этой степени.

Существует два подхода к интерполяции:
1. Вычисление коэффициентов интерполяционного многочлена, а затем вычисление его значений в каждой нужной точке:
	- [Формула Лагранжа](lagrange.md)
	- [Улучшенная формула Лагранжа](imp_lagrange.md)
	- [Формула Ньютона](newton.md)
2. Вычисление значений интерполяционного многочлена напрямую --- без расчёта коэффициентов:
	- [Формула Лагранжа](lagrange.md)
	- [Улучшенная формула Лагранжа](imp_lagrange.md)
	- [Формула Ньютона](newton.md)
	- [Барицентрическая формула](../barycentric-formula/_index.md)