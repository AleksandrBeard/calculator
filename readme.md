# Задача: программа “Калькулятор”
### Описание:

Создайте консольное приложение “Калькулятор”.
Приложение должно читать из консоли введенные пользователем арифметические операции и выводить в консоль результат их выполнения.

### Требования:

1. Калькулятор умеет выполнять операции сложения, вычитания, умножения и деления с двумя числами: a + b, a - b, a * b, a / b. **Данные передаются в одну строку (смотрите пример)! Решения, в которых каждое число и арифмитеческая операция передаются с новой строки считаются неверными.**
2. Калькулятор умеет работать как с арабскими (1,2,3,4,5…), так и с римскими (I,II,III,IV,V…) цифрами.
3. Калькулятор умеет работать с цифрами от 1 до 10 включительно.
4. Калькулятор умеет работать только с целыми числами.
5. Калькулятор умеет работать только с арабскими или римскими цифрами одновременно, при вводе пользователем строки вроде 3 + II калькулятор должен выбросить исключение и прекратить свою работу.
6. При вводе пользователем неподходящих чисел приложение выбрасывает исключение и завершает свою работу.
7. При вводе пользователем строки не соответствующей одной из вышеописанных арифметических операций приложение выбрасывает исключение и завершает свою работу.

### Пример работы программы:

Input:

`1 + 2`

Output:

`3`

Input:

`VI / III`

Output:

`II`

### Принципы оценки работы:

Обратите внимание на принципы ООП, постарайтесь разбить программу на логические классы. Решения, в которых весь код программы находится в одном классе будут низко оценены. Продемонстрируйте своё умение в работе с разными синтаксическими конструкциями, не забудьте про исключительные ситуации, при которых выполнение программы невозможно из-за некорректных входных данных.
