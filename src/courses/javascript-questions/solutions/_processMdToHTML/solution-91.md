Метод `.push` возвращает _новую длину_ массива, а не сам массив! Устанавливая `newList` равным `[1, 2, 3].push(4)`, мы устанавливаем `newList` равным новой длине массива: `4`.

Затем мы пытаемся использовать метод `.push` для `newList`. Поскольку `newList` является числовым значением `4`, мы не можем использовать метод `.push`: выдается ошибка TypeError.
