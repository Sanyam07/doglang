# Version: 1.1
![logo](https://github.com/alxmamaev/image-storage/blob/master/doglang/logo.jpg)
# Doglang
Doglang - язык программирования для собак основаный на стековой машине.
##Краткое руководство:
Doglang - язык основаный на работе с [стеком](https://ru.wikipedia.org/wiki/%D0%A1%D1%82%D0%B5%D0%BA) и более ни с чем, здесь нет переменных, нет регистров.
<br>**Комманды языка:**
* `тяв!` - осуществляет ввод числа и кладет его в стек
* `гав!` - выводит последнее число в стеке на экран (не забирает его)
* `тяф!` - берет все введенные символы с экрана, и кладет их в стек интерпритируя как числа (смотри таблицу unicode)
* `гаф!` - выводит последнее число в стеке (не забирает его) в виде буквы (смотри таблицу unicode) 
* `вов!` - забирает 2 последних числа из стека, суммирует их и кладет обратно полученную сумму.
* `ваф!` - забирает 2 последних числа из стека, вычитает их (из верхнего нижнее) и кладет обратно полученную разность.
* `ряф!` -  забирает 2 последних числа из стека, умножает их и кладет обратно полученное произведение
* `вуф!` - забирает 2 последних числа из стека, делит их на цело (верхнее на нижнее) и кладет обратно полученное частное.
* `тряв!` **число** - кладет указанное число в стек
* `тряф!` - удаляет последнее число из стека
* `руф!` - меняет последних 2 числа в стеке местами
* `раф!` - полностью переворачивает стек
* `брюх!` - копирует последнее число в стеке и кладет его в стек
* `рав?` - выводит значения стека на экран (для дебага)
* `хыр` **имя** - создает метку с указанным названием
* `рых` **имя** - переходит на метку с указанным названием если последнее число в стеке не ноль (данные из стека не забираются)
* `;` - символ комментария, интепретатор не воспринимает символы после него
<br>*Полная документация с подробным описанием доступна в разделе [WIKI](https://github.com/alxmamaev/Doglang/wiki)"

## Руководство по интерпретатору
После запуска интепретатора, вам будет необходимо указать путь до файла с программой на языке Doglang.

## Запуск
* Если у вас windows, в папке exe_for_windows лежит уже собранный exe файл. Для запуска собранного exe файла необходимо иметь установленный [MVC++](https://www.microsoft.com/ru-RU/download/details.aspx?id=5555)
* Ксли у вас другая ОС, вам необходимо скачать python версии 3 и запустить файл main.py

## Пример программы
Пример программы выводящей *hello world* На экран
```
;Записываем буквы в стек
тряв! 0
тряв! 100
тряв! 108
тряв! 114
тряв! 111
тряв! 119
тряв! 32
тряв! 111
тряв! 108
тряв! 108
тряв! 101
тряв! 104
;Запускаем цикл и достаем буквы из стека
хыр рекс
гаф!
тряф!
рых рекс
```
*Другие примеры программ лежат в папке `examples/`*

## Зависимости
* [Python 3.x](https://www.python.org/downloads/)

## Лицензия распространения
Весь исходный код распространяется под лицензией MIT

## Подсветка синтаксиса
Вы можете установить синтаксис Doglang в редактор notepad++(или совместимый), xml-файл подсветки находтся в папке `highlighter/`
![](https://github.com/alxmamaev/image-storage/blob/master/doglang/notepad.jpeg)

## Автор
**Мамаев Александр** ([alxmamaev](https://alxmamaev.github.io/))
<br>[Вконтакте](https://vk.com/alxmamaev)
<br>[Телеграм](https://t.me/alxmamaev)
<br>alxmamaev@ya.ru 
