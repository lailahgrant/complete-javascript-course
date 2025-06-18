#### Numbers and Math
> Order of Operations
> 2 + 2
> 2 - 2
> 10 / 2
> 10 * 3 
> All these are **Operations**
> +, -, /, * These are **operators**
>
> In Math, 
> * /  are done first, 
> + - are done after 
> This is called the **operator precedence**.
>
> * / have the same priority
> 2 * 3 / 5 
> In Js, calculate from **left to right**
>
> + - have the same priority
> 2 - 3 + 5 
> In Js, calculate from **left to right**
>
> We can use  brackets () to control which part gets calculated first.
> (1+1)*3
>

Calculations with **floats** are sometimes inaccurate.
    When working with money:-
- Do the calculations in cents. 1 dollar = 100 cents
- Convert back to dollars
```javascript
// want  to add $20.95 to $7.99
// first convert the money to cents 2095 + 799
2095 + 799
//convert the cents to dollars
(2095 + 799) /100

```

##### How to round a number
2.2 to 2
> Use **Math.round()** - rounds to the nearest integer
```javascript
Math.round(2.2);
Math.round(2.8);
```
Forexample; Calculate the tax on a sale
```javascript
// calculate the tax on a sale
/*
1. convert the dollars to cents
2. get the tax e.g. 10% tax on $20.95 and $7.99
3. Convert back the cents to dollars
*/
((2095 + 799) * 0.1) /100;
```

To round the money;
```javascript
//1. round off the money in cents 
//2. convert the cents to dollars
Math.round((2095 + 799) * 0.1) /100

```

### Always [Google](https://www.google.com)
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
<hr>

> Take Away
> - Numbers and Math
> - Order of Operations, and Brackets (...)
> - Calculations using floats can be inaccurate when dealing with money.
> - Math.round()

[Exercise for this lessons is here](./Exercise-images/Js-exercise2.jpg) 
