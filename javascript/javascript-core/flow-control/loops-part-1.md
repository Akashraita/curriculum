---
author: alexjmackey
type: normal
category: must-know
links:
  - '[For Loops](https://youtu.be/24Wpg6njlYI){video}'
  - '[While / Do While loops](https://youtu.be/v9zgD8wjtbw){video}'
practiceQuestion:
  formats:
    - fill-in-the-gap
    - type-in-the-gap
  context: standalone
revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
---

# Loops I


---

## Content

JavaScript supports the standard loop constructs you may have seen in other languages:

### `for` loop

```javascript
// print values from 0 to 9
for (let i = 0; i < 10; i++) {
  console.log(i);
}

// 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
```

In the above code, `i = 0` shows that we start at zero, `i++` means that we will continue increasing the value of `i` by one each time the loop executes and `i < 10` means that we will stop doing it when the value exceeds 9.

`i--` means the value will decrease each time the loop executes. You can see an example of how it might be used below:

```javascript
// print values from 9 to 0
for (let i = 9; i >= 0; i--) {
  console.log(i);
}

// 9, 8, 7, 6, 5, 4, 3, 2, 1, 0
```

### `while` loop

The `while` loop continues to run as long as its condition is true:

```js
let i = 0;

// print values from 0 to 9
while (i < 10) {
  console.log(i);
  i++;
}

// 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
```

> 💡 The loop will never run if the expression is never true:

```javascript
let i = 10;

// this loop will never run because i = 10
// and thus the condition i < 10 means
// 10 < 10, which is never true
while (i < 10) {
  console.log(i);
  i++;
}

```

### `do..while` loop

`do..while` loops are similar to `while` loops but have the important difference that they will always run at least once before the condition is checked:

```javascript
let i = 10;

// runs once
// because the condition
// is checked at the end
do {
  console.log(i);
  i++;
} while (i < 10);
```

> 🤔 In all of the examples above the loop stops once a condition is met, but what if we wanted the loop to go on forever? Is there a way to do that using any of the loops discussed above? 
>
> Leave a comment or view some of the other comments for inspiration before moving on.

---

## Practice

Complete the syntax of the following `do/while` loop such that `i` will be `10` at the end of it:

```javascript
let i = 0;
??? {
  i++;
} ??? (i < ???)
```

- `do`
- `while`
- `10`
- `if`
- `else`
- `9`
- `for`


---

## Revision

Complete the following `for` loop such that it's syntactically correct and runs 10 iterations:

```javascript
??? (??? i = 0; i < 10; ???) {
  console.log(i);
}
```

- `for`
- `let`
- `i++`
- `while`
- `do`
- `i--`
 
