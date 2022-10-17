# Operators and Loops

[Back to home](../README.md)

## Operators

### **Assignment Operators**

[Assignment operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators), assign value to its left and right operand. A simple assignment operator is the equal sign, but there are much more versions that can be used.

![](../Photos/Table%20of%20Assignment%20Operators.png)

### **Comparison Operators**

A [comparison operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#comparison_operators) compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, logical, string, or object values. 

![](../Photos/Table%20of%20Comparison%20Operators.png)

## Loops

Loops offer a quick and easy way to do something repeatedly. There are many different types of loops:

### **For Statment**

A [for loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#for_statement), repeats until a specified conditon evaluates to false.

**EXAMPLE:**

![](../Photos/For%20Loop%20Syntax%20Example.png)

Here is a break down of what is going on:

- The initializing expression initialExpression, if any, is executed.
- The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. Otherwise, the for loop terminates.
- The statement executes. To execute multiple statements, use a block statement ({ }) to group those statements.
- If present, the update expression incrementExpression is executed.
Control returns to Step 2.

**Key Note:** If the conditionExpression expression is omitted entirely, the condition is assumed to be true.

### **While Statement**

A [while statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration#while_statement) executes its statements as long as a specified condition evaluates to true.

**EXAMPLE:**

![](../Photos/While%20Loop%20Syntax%20Example.png)

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

[Back to home](../README.md)