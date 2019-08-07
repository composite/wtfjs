```
if(0, 1) console.log('oh, hello?'); // it shows in your console.
if(0, 1) console.log('where am I?'); // it does not show in your console.
```

[ECMA 5.1: Comma operator](https://www.ecma-international.org/ecma-262/5.1/#sec-11.14)

[ECMA 5.1: The `if` statement](https://www.ecma-international.org/ecma-262/5.1/#sec-12.5)

[Comma operator | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comma_Operator)


comma(,) is a **operator**. yes. it's nothing special.

`if` statement can contains your any `expression`, result is simple, last expression will be passed by comma operator.

but there is one difference, `if` statement will be evaluated as `Boolean`.

in fact, you can write comma operated expressions in any kind if you are wrapping with parentheses(`( expression )`) except `function`(you must wrap extra parentheses if you want to add comma operator).

— [@composite][1]

[1]:https://github.com/composite
