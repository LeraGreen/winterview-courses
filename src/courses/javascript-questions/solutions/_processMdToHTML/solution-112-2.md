В файле `generatorTwo` мы используем ключевое слово `yield*`. Это означает, что первое полученное значение `two` равно первому полученному значению в итераторе. Итератор - это массив `['a', 'b', 'c']`. Первым полученным значением является `a`, поэтому в первый раз, когда мы вызываем `two.next().value`, возвращается `a`.