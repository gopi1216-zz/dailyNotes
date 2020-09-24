## Points to remember as Developer
- Study like Tortoise.
- Study a chapter/topic for 5 or 10 minutes
- Practice the same chapter/topic for 20 to 30 minutes.
- Take rest for 20 minutes.

## Alerts :
- Description: alert is just a box that pops up to give the user a message. Syntax for the alert is mentioned below. Few developers use **window.alert()** and few are good with short method **alert()**.
- Syntax: 
```js
alert('Welcome to JavaScript..!');
```

## Variables :
- Variable is just container holding some value with name. 
- **'var'** is used to create a variable followed by variable name like below example.
```js
var fullName = 'Gopi Jagarlamudi';
```
- Whenever the JS encounters **fullName**, JS knows that it's a variable refers to ***Gopi Jagarlamudi***.
- We can also change variables to new value like below
```js
fullName = 'JavaScript Developer';
```
- Now the **fullName** variable refers to new value ***JavaScript Developer***. Once variable is declared no need to use var to change it's value. If it used, then it's re declaration of same variable which is not recommended.
- In variable we store any kind data like ***String***, ***Number***, ***Float***, ***Double*** and ***Boolean***. Type of variable an be changed based on value assigned to it.
- If we perform addition between **String** and **Number**, then it return combined String not a number.
```js
var weight = 85;
console.log(weight + 20); //This will return 105, casue both are numbers
var weight = "85";
console.log(weight + 20); //This will return 8520, cause weight is String and 20 is number.
```
- In the above example ***20*** automatically converted into String this is called coerson. If you perform addition between two strings then it's called **Concatenation**.

#### Variable naming rules : ####
- Should not enclosed in quotes (If it is wrapped inside quotes then it's **String**).
- Should not start with number.
- Not a JavaScript(language inbuilt keywords like var, let... etc ) keyword which is having proper meaning.
- It Should be short and informative and as recommended it should be in camel case (like **fullname**, **age**, **personAge**, **_fullName**).
- Will start with ***$*** and **_** (like $personName, **_personName**).


## Mathematical Operations
- 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQ0MTI1ODMxNCwxNjYwNjAxMDU2LC04MT
IwMDQ2MTQsLTcyNjk0MDAyNywtMTU2MTg1NDUxMywtMTk3NzE3
NDQzMSwtMjIzNjE1OTk1LDQ1NzQwMTg4NSw5MzY5OTE2MzEsMT
kzMzU4OTQyNywtNDc2MTgxNTldfQ==
-->