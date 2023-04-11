# Красно-черное дерево
Необходимо превратить собранное на семинаре дерево поиска в полноценное левостороннее красно-черное дерево. И реализовать в нем метод добавления новых элементов с балансировкой.

Красно-черное дерево имеет следующие критерии:
* Каждая нода имеет цвет (красный или черный)
* Корень дерева всегда черный
* Новая нода всегда красная
* Красные ноды могут быть только левым ребенком
* У краной ноды все дети черного цвета

Соответственно, чтобы данные условия выполнялись, после добавления элемента в дерево необходимо произвести балансировку, благодаря которой все критерии выше станут валидными. Для балансировки существует 3 операции – левый малый поворот, правый малый поворот и смена цвета.

# Red-black tree
It is necessary to turn the search tree collected at the seminar into a full-fledged left-sided red-black tree. And implement in it a method of adding new elements with balancing.

The red-black tree has the following criteria:
* Each node has a color (red or black)
* The root of the tree is always black
* The new node is always red
* Red nodes can only be the left child
* All children of the red node are black

Accordingly, in order for these conditions to be met, after adding an element to the tree, it is necessary to perform balancing, thanks to which all the criteria above will become valid. There are 3 operations for balancing – a small left turn, a small right turn and a color change.
