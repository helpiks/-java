# -java
Переменная имеет имя и тип значения, которое она содержит.  

 - Для объявления переменной используется тип, за которым следует имя переменной. 
 
 - Для присвоения значения объявленной переменной используется оператор =. 
 
 - Переменная может изменять своё значение в ходе выполнения программы, если ей присваивается новое значение. 

Тип int используется для хранения целых чисел (англ. integer).

Для работы с десятичными числами используется тип double

В Java есть ещё один тип десятичных чисел, называемый float. 
 
При использовании типа float необходимо использовать постфикс f после значения:Общее правило следующее: использовать float вместо double, когда ресурсы памяти ограничены. Если нужны более точные вычисления, например, при работе с валютой, следует использовать double.

Тип char предназначен для хранения одного символа. Он создаётся аналогично типу Strings, но значение заключается в одинарные кавычки: 

Следующий важный тип — boolean. 
Такой тип может хранить только два значения: true или false. 

Инструкция if является одной из наиболее часто используемых условных инструкций. 
Если условие инструкции if является true, то блок кода внутри оператора if выполняется.  
 
Синтаксис: 
if (condition) {
  //some code 
}
Инструкция if  
 
Для задания условия может быть использован любой из следующих операторов сравнения: 
< меньше 
> больше 
!= не равно 
== равно 
<= меньше или равно 
>= больше или равно 
 
для проверки равенства нужно использовать два знака равенства (==)
За инструкцией if может следовать необязательный блок else, который выполняется в том случае, если условие оценивается как false.  
 Вместо вложенных инструкций if-else можно использовать инструкцию else if для проверки нескольких условий. 