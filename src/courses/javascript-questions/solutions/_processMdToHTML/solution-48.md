Ассоциативность операторов - это порядок, в котором компилятор оценивает выражения, слева направо или справа налево. Это происходит только в том случае, если все операторы имеют _одинаковый_ приоритет. У нас есть только один тип оператора: `+`. Кроме того, ассоциативность слева направо.

`3 + 4` оценивается первым. Это приводит к числу `7`.

`7 + '5'` приводит к `"75"` из-за принуждения. JavaScript преобразует число `7` в строку. Мы можем объединить две строки, используя оператор `+`. `"7" + "5"` приводит к `"75"`.
