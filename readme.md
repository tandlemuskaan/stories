# 📝 Sentence Maker

A beginner JavaScript project built 

Overview

This project generates two short stories by combining variables with string concatenation. The variables are updated between stories to create different outputs using the same sentence template.

---

Learning Objectives

Through this exercise I learned:

- Creating variables using `let`
- Updating (reassigning) variable values
- String concatenation using the `+` operator
- Building long strings from multiple variables
- Displaying output with `console.log()`
- Reusing the same template with different data

JavaScript Concepts

### Variables

Variables store data that can be used later.

```javascript
let adjective = "majestic";
let noun = "dragon";
```

---

### Variable Reassignment

Variables declared with `let` can be updated.

```javascript
noun = "bojack";
```

---

### String Concatenation

The `+` operator combines strings and variables.

```javascript
let sentence = "Hello " + name + "!";
```

Output:

```
Hello Muskaan!
```

---

### console.log()

Used to print information to the console.

```javascript
console.log(sentence);

Story Template

```
Once upon a time, there was a(n) [adjective] [noun] who loved to eat [noun2].
The [noun] lived in a [place] and had [adjective2] nostrils that blew fire when it was [verb].
```

The same template is reused after changing the variable values.

Concepts Practiced

- Variables
- String values
- Variable reassignment
- String concatenation
- Code reusability
- Output formatting
- `console.log()`

Challenges Faced

While completing this project I learned that:

- freeCodeCamp checks strings **exactly**, including punctuation and spaces.
- Hidden tests may fail even when the output looks correct.
- Small formatting differences can cause automated tests to fail.


Key Takeaways

- Always pay attention to spaces and punctuation when building strings.
- Use variables instead of hardcoding repeated values.
- Reusing templates makes code easier to maintain.
- Reading error messages carefully can save a lot of debugging time.
 Example Output

```
First story:
Once upon a time, there was a(n) majestic peanutbottle who loved to eat bones.
The peanutbottle lived in a the hills and had fierce nostrils that blew fire when it was breathing out.

Second story:
Once upon a time, there was a(n) happy bojack who loved to eat pop tarts.
The bojack lived in a boat and had big nostrils that blew fire when it was sad.
```

---

## Author

**Muskaan**

Created while learning JavaScript through the freeCodeCamp JavaScript (v9) curriculum.