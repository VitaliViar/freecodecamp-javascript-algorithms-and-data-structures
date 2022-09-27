# Используйте условную логику с операторами If
`if`Операторы используются для принятия решений в коде. Ключевое слово `if`указывает JavaScript выполнять код в фигурных скобках при определенных условиях, определенных в скобках. Эти условия известны как `Boolean`условия, и они могут быть только `true`или `false`.

Когда условие оценивается как `true`, программа выполняет оператор внутри фигурных скобок. Когда логическое условие оценивается как `false`, оператор внутри фигурных скобок не будет выполняться.

##### Псевдокод

если ( условие истинно ) {
  оператор выполнен
}
### Пример
```javascript
function test (myCondition) {
  if (myCondition) {
    return "It was true";
  }
  return "It was false";
}

test(true);
test(false);
```
`test(true)`возвращает строку `It was trueи test(false)`возвращает строку `It was false`.

Когда `test`вызывается со значением `true`, `if`оператор оценивает `myCondition`, так это `true`или нет. Поскольку это так `true`, функция возвращает значение `It was true`. Когда мы вызываем `testсо` значением `false`, неmy`Condition` выполняется и оператор в фигурных скобках не выполняется и функция возвращает значение . `trueIt was false`
## Instructions
Создайте `if`оператор внутри функции для возврата `Yes, that was true`, если параметр `wasThatTrueесть`, `true`и возврата в `No, that was false`противном случае.

### Before
```javascript
function trueOrFalse(wasThatTrue) {
  // Only change code below this line



  // Only change code above this line

}
```
### Answers
```javascript
function trueOrFalse(wasThatTrue) {
  // Only change code below this line
if (wasThatTrue) {
return "Yes, that was true";
}

return "No, that was false";
  // Only change code above this line

}
```
