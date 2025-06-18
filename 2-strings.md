## Strings

[This is the project we are referreing to](https://supersimple.dev/projects/amazon) -  using the project's browser console.

> string = text
> Numbers and Strings are different types of values in JavaScript.
>


```javascript
//in the browser's console
'hello' // '' - single quotes
alert('hello');

// Concatenation: add two strings to make one bigger string
'some' + 'text'

'some' + 'more' + 'text'

//find out the value of something using typeof
typeof 2
typeof 'hello'

// what if we add a string and a number together
// javascript automatically changes this number to a string
'hello' + 3 //hello3
// this is called Type coercion (automatic type conversion)

//js adds from left to right

// Strings also follow the order of operation (in calculations)
'$' + (20.95 +7.99)

// calculate money in cents first then convert it to dollars
'$' + (2095 +799) /100  //'$28.94'

// to write this string //Items (2): $28.94
// Use concatenation
'Items ('+(1+1)+ '): $' + (2095 + 799)/100

// create a pop up
alert('Items ('+(1+1)+ '): $' + (2095 + 799)/100)

```

#### 3 ways to create strings
- Use ' ' single quote
- Use " " double quote
- Use `` backticks 

> In js, he recommends using ' ' for creating strings as they're easy to read and type
> Use '  ' by default
> '  '  are easier to read and type.

Escape Character 
    Character =  1 letter/ number/ symbol in a piece of text.

    e.g. hello = 5 characters
Character can be;
- Letter (a,b,c)
- Number (1,2,3)
- Symbol (!, @, #)
- Escape characters - special characters that can be used in a string (\' - single quote, \" - double quote, \n - newline character)

```javascript
// if the string has ' in it
// a) Use " " 
"I'm learning JavaScript"

/* b) Escape Character 
// 
*/
'I\'m learning JavaScript'

// \n - newline character
alert('some\ntext')

```

Use `` backticks 
- ``  create **template strings**.
- Strings created by `` actually have a name, called **template strings**
- Special features of template strings are;
    - Interpolation = insert a value directly into a string.
        A combination of `` ${}  allows us to insert values directly into the string
        - ${} = insert value directly into string
        - Interpolation is the recommeded way.
    - Multi-line strings 
```javascript
//a) Used concatenation
'Items ('+(1+1)+ '): $' + (2095 + 799)/100

//b) Use Interpolation to write the following (template strings)
// Items (2): $28.94
`Items (${(1+1)}): $${(2095 + 799)/100}`
// a combination of ${} = allows us to insert values directly into the string

// c) Multi-line strings
`some
text` //'some\ntext'

```

> What should we use to create a string?
>
> '   '  vs `` (single quotes or template strings)
> 1. Use '  ' by default.

<hr>

#### Take away
- String = text
- Can use strings and numbers together
- Three ways to create strings;
    - '...',   "....",   ``(template strings)
- Escape characters: \`, \n
- Interpolation, mulit-line strings 

<hr>

[Exercise for the Strings is here](./Exercise-images/Strings-exercise.jpg) 
[Exercise for the Strings is here](./Exercise-images/Strings-exercise1.jpg) 
[Exercise for the Strings is here](./Exercise-images/Strings-exercise2.jpg) 

<img src="./Exercise-images/Strings-exercise.jpg" alt="Exercise for the Strings is here">
<img src="./Exercise-images/Strings-exercise2.jpg" alt="Exercise for the Strings is here">
<img src="./Exercise-images/Strings-exercise2.jpg" alt="Exercise for the Strings is here">




