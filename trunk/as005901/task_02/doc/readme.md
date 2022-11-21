***<h1 align = "center">Лабораторная работа №2 «PID-регуляторы»</a>***

<font size = 3>
<p align = "right">
Выполнил: Абоимов И.В.</p>
<p align = "right">
Проверил: Иванюк Д.С.</p>
</font>

## **Цель работы:**

<p aling = "justify">
На C++ реализовать программу, моделирующую изображённый на картинке ПИД-регулятор. В качестве объекта управления использовать математическую модель, полученную в предыдущей работе. Использовать ООП, в программе должно быть не менее 3-х классов (+наследование).
</p>

![](pictures/PID_regulator.png)

<p align = "justify">
Здесь w(t) - алгоритм функционирования системы; u(t) - управляющее воздействие; z(t) - внешние возмущающие воздействия, влияние которых нужно свести к минимуму (пренебрегаем им); y(t) - выходная переменная; e(t) = w(t) - y(t) - отклонение выходной переменной y(t) от желаемого значения w(t).
</p>

## **Код программы:**

Исходный код программы находится по пути trunk\as005901\task_01\src.  
  
Результаты работы программы:  
  
![](pictures/work_mode.png)  
  
## **Результаты регулирования:**

<p align = "justify">
графики y(t) - выходная температура (синий), e(t) - реакция на скачок (зелёный), u(t) - управляющее воздействие (красный)  
</p>  

![поместите md-файл с файлами изображений](pictures/graph.png)  

## **Вывод**

<p align = "justify">
Построил PID-регулятор для нелинейной модели, описанной в предыдущей работе. PID-регулятор выполняет свои функции корректно, т.к. процесс регулирования устойчивая.  
</p>