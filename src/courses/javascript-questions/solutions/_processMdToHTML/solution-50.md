При использовании метода map, значение `num` равно элементу, над которым он в данный момент зацикливается. В этом случае элементы являются числами, поэтому условие оператора if `typeof num === "number"` возвращает `true`. Функция map создает новый массив и вставляет значения, возвращаемые функцией.

Однако мы не возвращаем значение. Когда мы не возвращаем значение из функции, функция возвращает значение `undefined`. Для каждого элемента в массиве вызывается функциональный блок, поэтому для каждого элемента мы возвращаем `undefined`.