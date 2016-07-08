# Doglang
Doglang - язык программирования для собак основанный на стековой машине.
##Краткое руководство:
Doglang - язык основанный на работе с [стеком](https://ru.wikipedia.org/wiki/%D0%A1%D1%82%D0%B5%D0%BA) и более ни с чем, здесь нет переменных, нет регистров.
<br>**Комманды языка:**
* *тяф!* - осуществляет ввод данных и кладет их в стек
* *гав!* - забирает последнее число из стек и выводит на экран
* *вов!* - забирает 2 последних числа из стека, суммирует их и кладет обратно полученную сумму.
* *ваф!* - забирает 2 последних числа из стека, вычитает их (из верхнего нижнее) и кладет обратно полученную разность.
* *ряф* -  забирает 2 последних числа из стека, умножает их и кладет обратно полученное произведение
* *вуф* - забирает 2 последних числа из стека, делит их на цело (верхнее на нижнее) и кладет обратно полученное частное.
* *тряв! число* - кладет указанное число в стек
* *тряф!* - удаляет последнее число из стека
* *руф!* - меняет последних 2 числа в стеке местами
* *рав?* - выводит стек полностью (для дебага)
* *хыр имя* - создает метку с указанным названием
* *рых имя* - переходит на метку с указанным названием если последнее число в стеке == 0 (данные из стека не забираются)
* *рюх.* - завершение программы (обязательно)

##Руководство по интепретатору
* *груг!* - запустить редактор прямо в программе(без сохранения).
* *рыв!* - запустить скрипт из файла. Далее будет необходимо указать путь до фвйла