`new Number()` это встроенный конструктор функции. И хотя он выглядит как число, это не настоящее число: у него есть ряд дополнительных фич и это объект.

Оператор `==` разрешает приведение типов, он проверяет равенство _значений_. Оба значения равны `3`, поэтому возвращается `true`.

При использовании оператора `===` значение _и_ тип должны быть одинаковыми. Но в нашем случае это не так: `new Number()` это не число, это **объект**. Оба возвращают `false`.
