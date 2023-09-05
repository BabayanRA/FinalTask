## Задача :
# Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

### Описание решения:

### Задается два массива одинаковой длинны (A и B), в одном из них (A) заранее прописаны строки. Далее каждый элемент массива A проверяется условием, что длина строки элемента меньше, либо равна 3. Если таковое условие соблюдается, то в массив B данный элемент записывается (для массива B - есть счетчик целых чисел j, который увеличивается на 1 в том случае, если в массив B в результате проверок записалась строка из массива A).
### После того, как проверка всех элементов массива А закончилась полностью, полученный массив В выводится на экран.