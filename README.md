# Вопрос 1

[код](/tasks/10/src/first.cpp)

# Вопрос 2

[код](/tasks/10/src/second.cpp)

# Вопрос 3

[код](/tasks/10/src/third.cpp)

# Вопрос 4

[код](/tasks/10/src/fourh.cpp)

# Вопрос 5

a) Т.к. условие в цикле использует оператор <= для сравнения, на последней итерации будет всегда переден индекс массива, которго не существует: последний индекс массива с длинной 4 - 3.

b) Указатель является константным, из-за чего, через него нельзя изменить значение элемента, на которое он указывает.

с) В функцию передается указатель на массив, вместо него самого, из-за чего неизвестна его длинна. Цикл foreach умеет работать только со структурами данных с фиксированной длинной.

d) temp выхожит из контекста функции. Так же нельзя создать массив не зная его длинны во время компиляции.

e) Указатель на неправильный тип данных.

# Вопрос 6 и 7

[код](/tasks/10/src/blackjack.cpp)
