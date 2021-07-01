## Expressions and operators notes

- JavaScript has both binary and unary operators, and one special ternary operator, the conditional operator. A binary operator requires two operands, one before the operator and one after the operator:

- For example, 3+4 or x*y

- A unary operator requires a single operand, either before or after the operator:

- Example: operator operand

- An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.

- Example: ![Screenshot 2021-07-01 144425](https://user-images.githubusercontent.com/86576588/124181251-dfc49600-da7a-11eb-87dc-10f6fb68f35d.png)

- Like most expressions, assignments like x = y have a return value. It can be retrieved by e.g. assigning the expression or logging it:

- Example: ![ou](https://user-images.githubusercontent.com/86576588/124181382-08e52680-da7b-11eb-8ef5-f4b649da9f35.png)

- The return value matches the expression to the right of the = sign in the “Meaning” column of the table above. That means that (x = y) returns y, (x += y) returns the resulting sum x + y, (x **= y) returns the resulting power x ** y, and so on.

### Loops Notes

- Loops offer a quick and easy way to do something repeatedly.

- You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

- Example: ![Screenshot 2021-07-01 145411](https://user-images.githubusercontent.com/86576588/124182253-3aaabd00-da7c-11eb-935f-32608c601ee3.png)

- A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

- Example: ![Screenshot 2021-07-01 145554](https://user-images.githubusercontent.com/86576588/124182425-734a9680-da7c-11eb-80cd-024e9c39b886.png)

- The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.

- The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)

- The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.

- If present, the update expression incrementExpression is executed.

- Control returns to Step 2.

