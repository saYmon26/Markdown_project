# Арифметические операторы.

* Всего в языке C# есть несколько арифметических операторов.

1) Сложение (+)

2) Вычитание (-)

3) Умножение (*)

4) Деление (/)

5) Остаток от деления - *mod* (%)

6) Инкремент (++)

7) Декремент (--)

**Сложение (+), вычитание (-), умножение (*)**

* Эти арифметические операторы полностью подчиняются законам математики. 

**Деление (/)**

1) Деление двух целых чисел.

![Деление_двух_целых](/images/%D0%94%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%86%D0%B5%D0%BB%D1%8B%D1%85.png)

Мы видим что при делении двух целых чисел в ответе получается целое число 2, хотя по правилам математики ответ должен быть 2,5. Это происходит потому что C# автоматически отбрасывает дробную часть. То есть, фактически, ответ может быть записан, как 2 и (остаток 1).
Что же делать если нам нужен ответ с дробной частью?

2) Деление двух чисел с дробной частью.

![Деление_с_дробью](/images/%D0%94%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%20%D0%B4%D1%80%D0%BE%D0%B1%D1%8C%D1%8E.png)

В этом случае мы видим что все поделилось правильно. Дело в том что мы написали 2.0 вместо 2, как в прошлый раз. В данном случае C# понял, что нам нужна дробная часть в результате деления.
Также мы можем использовать 5.0 вместо 5.

**Остаток от деления - *mod* (%)**

![mod](/images/MOD.png)

Как мы можем заметить при делении по mod числа 5 на число 2 в ответе получилось 1. Это ни что иное, как остаток от целочисленного деления одного числа на другое. Например, 10 % 3 = 1 или 14 % 5 = 4.

**Инкремент (++) и декремент (--)**

* Инкремент это увеличение одного и того же значения на 1.

То есть:

a = a + 1;

это то же самое, что и:

a ++;

Эта функция нужна скорее для того, чтобы код смотрелся более красиво.

* Декремент это уменьшение одного и того же значения на 1.

То есть:

a = a - 1;

это то же самое, что и:

a --;

Эта функция тоже нужна для того, чтобы код смотрелся более красиво.

* Приоритет у этих знаков такой же как и в математике: mod, * и / выполняются в первую очередь, а потом уже + и -.

