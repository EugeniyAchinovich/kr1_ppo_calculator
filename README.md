# Отчёт по контрольной работе № 1
## по предмету “Проектирование программного обеспечения“

#### Выполнил: Ачинович Е. Ю.



## Цель контрольной работы.
Изучить основные элементы пользовательского интерфейса и
размещение их на различных типах слоев. Описание интерфейса с помощью
языка разметки в ресурсах приложения. Работа со списками и адапторами.

## Указания по выбору варианта.
Соответствующий вариант работы выбирается по правилу: последняя цифра номера зачетной книжки + 1.
3+1 = 4 


## Вариант 4.
Калькулятор, где базовый\расширенный блоки кнопок разнесены на разные активити ( экраны). Переход туда-обратно по нажатию специальных кнопок. Сохранять текущее значение в поле результата

## Решение
Программа написана в Android Studio.

#### Тесты находятся в CalculatorNew/app/src/test/java/com/example/calculator/ExampleUnitTest.java

Программа представляет собой Android-приложение – калькулятор с
расширенным блоком кнопок (научный калькулятор). Выполняет
арифметические, тригонометрические функции, возведения в степень,
вычисление корней, факториалов, экспоненты.
Интерфейс классический кнопочный. 


Вычисление синуса 30градусов 
![image](https://user-images.githubusercontent.com/75760235/212774156-8b328ce2-ff84-4b89-b9c2-36e7855058c7.png)
      
      
Пример деления
![image](https://user-images.githubusercontent.com/75760235/212774203-5be33f01-873e-4ddb-8649-b69d50b18439.png)



## Запуск проекта
Открыть проект в Android Studio. Клонировать данный репозиторий. Запустить

## Значения кнопок интерфейса калькулятора

#### AC – All clear – очистить всё
#### С – удалить последний символ ввода
#### ( - открывающая круглая скобка
#### ) - закрывающая круглая скобка
#### Sin – вычислить синус значения в градусах
#### Cos – вычислить косинус значения в градусах
#### Tan – вычислить тангенс значения в градусах
#### Log – логарифм числа
#### Ln – натуральный логарифм числа
#### x! – факториал числа
#### x²– возведение в степень
#### √ – корень числа
#### 1/x – вычисление обратного значения заданному первоначально числу
#### ÷ – операция деления
#### X – операция умножения
#### + – операция сложения
#### - – операция вычитания
#### = - вычислить выражение
#### 1-9 – ввод цифр 1-9 соответственно
#### . – ввод десятичной точки (запятой)
#### П – ввод константы Пи (3.1415…)
