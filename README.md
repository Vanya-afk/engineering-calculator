# Task

https://docs.google.com/document/d/1j8DnTnRSNoRBdYtKu3Rgk1STLso4X5Rev2-oEyxMsK8/edit#

## How to run the app

Пользователь вводит выражение. live-parsing разбивает всю строку на элементы и 
делает множество проверок. Например убирает возможность ставить несколько знаков подряд
#
Далее строки попадает в reverse-polish-notation где преобразовывается в обратную польскую запись, эта строка передается в get-answer
Там происходит очередное преобразование строки и вызов mathematicalCalculations
#
В зависимости от переданного знака вызывается соответствующая функция
