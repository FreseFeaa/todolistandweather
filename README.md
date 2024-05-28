# Напоминалка ака ToDo

**Задание**

Когда вы запускаете программу, она показывает список будущих событий и сообщает вам, сколько дней осталось до каждого из них. Запустите ее снова на следующий день и вы увидите, что программа вычла один день из каждой из цифр "дней до". Заполните его датами ваших предстоящих дел, и вы никогда не пропустите важный день или срок выполнения домашнего задания.
Текущие, будущие и просроченные задачи выделите разными цветами.
Сами задачи храните в простом текстовом файле, формат которого определите сами.

![image](https://github.com/FreseFeaa/todolistandweather/assets/151909599/6f3829a7-fac3-44b2-8672-c7dc3aa08833)
Пример интерфейса.

Я доработал эту идею, сделал более приятный интерфейс. 
Также я добавил возможность посмотреть погоду на данный момент в любом городе мира. (По умолчанию стоит Санкт-Петербург)
Кроме того, сделал несколько базовых тестов с помощью pytest

Для запуска программы может понадобиться докачать эти библеотеки:
```
py -m pip install requests
```
```
py -m pip install pillow
```
```
py -m pip install pytest
```