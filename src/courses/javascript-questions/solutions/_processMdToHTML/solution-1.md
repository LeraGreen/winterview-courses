Внутри функции мы сперва определяем переменную `name` с помощью ключевого слова `var`. Это означает, что переменная будет поднята (область памяти под переменную будет выделена во время фазы создания) со значением `undefined` по умолчанию, до тех пора пока исполнение кода не дойдет до строчки, где определяется переменная. Мы еще не определили значение `name` когда пытаемся вывести её в консоль, поэтому в консоли будет `undefined`.

Переменные, определенные с помощью `let` (и `const`), также поднимаются, но в отличие от `var`, не <i>инициализируются</i>. Доступ к ним не возможен до тех пор, пока не выполнится строка их определения (инициализации). Это называется "временная мертвая зона". Когда мы пытаемся обратиться к переменным до того момента как они определены, JavaScript выбрасывает исключение `ReferenceError`.