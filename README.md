# Домашнее задание к занятию "Рисование графиков"
### Цель задания
В результате выполнения этого задания вы научитесь строить линейные графики при помощи QtCharts (можно QCustomPlot)

---
### Инструкция к заданию
1. Скачать проект с прекодом.
1. Добавить в CmakeList.txt модуль для работы с QtCharts
    - Если выполняете при помощи QCustomPlot то соответственно добавить библиотеки(можно взять из примеров лекций) и добавить модуль необходимый для работы QCustomPlot
1. Выполнить требования задания.
--- 
### Задание 1.
1. Необходимо отобразить первую секунду обработанных данных.
1. Наполнение серии данными необходимо реализовать внутри лямбда-функции findMax.
1. Поместить сигнал внутрь findMax сигнализирующий о готовности данных для отрисовки.
1. Отображение графика должно быть реализовано в созданном вами слоте в MainWindow.
1. График должен отображаться в новом окне.
---
### Дополнительные сведенья
1. Частота дискретизации данных составляет 1000 Гц.