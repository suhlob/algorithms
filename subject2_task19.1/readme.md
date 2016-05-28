## Задача 19.1 Концерт
параметр: | значение:
------------ | -------------
Имя входного файла: |  input.txt
Имя выходного файла: | output.txt
Ограничение по времени: |  2 с
Ограничение по памяти: | нет
### Условие
Во время трансляции концерта предприниматель решил сделать бизнес на производстве кассет. Он имеет *M* кассет с длительностью *D* звучания каждая и хочет записать на них максимальное число песен. Эти песни (их общее число *N*) передаются в порядке *1, 2, …, N* и имеют заранее известные ему длительности звучания *L1, L2, …, Ln*. Предприниматель, прослушивая песни по порядку, может выполнять одно из следующих действий:

* если песня на текущую кассету помещается, то он может записать её на кассету или пропустить песню;
* если песня на кассету не помещается, то он может пропустить песню или начать её записывать на новую кассету (при этом старая кассета откладывается и туда уже ничего не может быть записано).
Необходимо определить максимальное число песен, которые предприниматель может записать на кассеты.

###Формат входного файла
В первой строке находятся целые числа *N*, *M* и *D (1 ≤ N ≤ 200, 1 ≤ M ≤ 50, 1 ≤ D ≤ 1000)*.
Во второй строке находятся целые числа *L1, L2, …, Ln*, разделённые пробелом *(1 ≤ Li ≤ 1000)*.

### Формат выходного файла
Выведите максимальное число песен, которые предприниматель может записать на кассеты.
