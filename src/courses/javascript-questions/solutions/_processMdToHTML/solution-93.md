`Object.entries (person)` возвращает массив вложенных массивов, содержащий ключи и объекты:

`[ [ 'name', 'Lydia' ], [ 'age', 21 ] ]`

Используя цикл `for-of`, мы можем перебирать каждый элемент массива, в данном случае подмассивы. Мы можем мгновенно деструктурировать подмассивы в цикле for, используя `const [x, y]`. `x` равен первому элементу в подмассиве, `y` равен второму элементу в подмассиве.

Первым подмассивом является `[ "name", "Lydia" ]`, где `x` равно `"name"`, и `y` равно `"Lydia"`, которые выводятся в лог.
Вторым подмассивом является `[ "age", 21 ]`, где `x` равно `"age"`, и `y` равно `21`, которые выводятся в лог.