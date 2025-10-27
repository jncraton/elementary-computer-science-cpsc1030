---
reading: '[Introduction to Scratch](https://cms.scratchfoundation.org/assets/c914f147-0311-4292-bf5b-f97429ccfcc8)'
...

# Conditionals in Scratch

---

K-2.PA.3: Develop programs with sequences and simple loops to express ideas or address a problem. (E)

---

K-2.PA.4: Identify and fix (debug) errors in sequences and simple loops.

---

## What are Conditionals?

- A way to make a decision in your program
- They run a block of code **only if** a certain condition is true
- They give our programs "if-then" logic

## The `if` Block

- Found in the **Control** category 
- The simplest conditional block
- It holds a hexagonal "reporter" block for the condition

## Reporter Blocks

- The green blocks from the **Sensing** category
- They report a value, like `touching color?` or `mouse down?`
- When the condition is met, they report as "true"

---

What's a decision you make every day that has an "if-then" structure?

## `if...then...`

- The `if` block is a basic decision maker
- The code inside it only runs when the condition is true
- It's a fundamental part of programming

## `if...then...else`

- A more advanced conditional block
- It runs one block of code if the condition is true
- It runs a different block of code if the condition is false

## Exercise

- Create a program where a sprite says "Hello" only if the space key is pressed.
- What happens if the space key is not pressed?
- Can you use the `forever` loop from our last lesson to make it continuously check for a key press?

## Conditionals and Loops

- You can put conditionals inside loops
- This lets your program continuously check for a condition
- This is how you make interactive programs and games

## Exercise

- Use a `forever` loop to make a sprite change its costume
- Now, add an `if` block inside the loop
- Make the sprite say "Ouch!" if the mouse is touching it

---

How can we use conditionals to make a program more like a conversation?

## Combining Logic

- You can combine multiple conditions using `and` or `or`
- These are found in the **Operators** category
- This lets you create more specific conditions

## Debugging

- Conditionals can be tricky to debug
- A common error is a condition that's never true
- Another is having your code in the wrong `if` or `else` block

## Common Conditional Errors

- **Missing a condition**: The conditional block is empty
- **Incorrect condition**: The condition never evaluates to true
- **Block placement**: The code is not in the correct part of the conditional

## Fixing Errors

- Use the `say` block to check if your condition is being met
- Check the hexagonal reporter block to ensure it's the right one
- Use temporary `wait` blocks to slow down the program and see what happens

---

What's a common mistake you see when people are trying to teach a child to follow instructions?

## Problem Solving

- Use conditionals to solve a problem with multiple outcomes
- For example, if a sprite gets to the edge, turn it around
- Or, if a player's score reaches 10, stop the game

## Exercise

- Create a simple game where a character chases an object
- Use an `if` block to detect when the character touches the object
- When it touches, make the object disappear and add to a score variable
