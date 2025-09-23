---
reading: '[Introduction to Scratch](https://cms.scratchfoundation.org/assets/c914f147-0311-4292-bf5b-f97429ccfcc8)'
...

# Loops in Scratch

---

K-2.PA.3: Develop programs with sequences and simple loops to express ideas or address a problem. (E)

---

K-2.PA.4: Identify and fix (debug) errors in sequences and simple loops.

---

K-2.PA.5: Model daily processes by creating and following algorithms (i.e., sets of step-by-step instructions) to complete tasks. (E)

## What are Loops?

- A way to repeat a sequence of blocks
- They save us from dragging out the same blocks over and over
- They make our code shorter and easier to read

## Example without Loops

- A program to make a character jump up and down 3 times
- We would need three sets of blocks for "jump up" and "jump down"
- That's a lot of blocks for a simple action

---

What's a repetitive task you do every day that could be described as a loop?

## The `forever` loop

- A basic loop that repeats the blocks inside it indefinitely
- It's in the **Control** category
- It's great for things that should always be happening in a game or story

## Exercise

- Create a program where a sprite endlessly moves back and forth across the stage
- Remember to use the `forever` loop
- What happens if you don't use a loop?

## The `repeat` loop

- A loop that repeats the blocks inside it a specific number of times
- Also found in the **Control** category
- It's perfect for actions that need to happen a set number of times

## Loop vs Sequence

- A sequence is a single run-through of a set of commands
- A loop is a program construct that executes a sequence repeatedly

---

How can loops help us tell more complex stories with our programs?

## Developing Programs

- Use loops to make sequences more efficient
- Think about which parts of your program need to be repeated
- A good strategy is to first create the sequence, then wrap it in a loop

## Exercise

- Create a program to use a `repeat` loop
- How many blocks did you save by using a loop?

## Debugging

- Loops can be tricky to debug because they repeat
- If there's an error inside a loop, it will repeat with every iteration

## Common Loop Errors

- **Infinite loops**: when a forever loop doesn't stop
- **Off-by-one errors**: when a `repeat` loop runs one time too many or too few
- **Logic errors**: when the blocks inside the loop don't do what you expect

## Fixing Errors

- Use temporary `wait` blocks to slow down the loop and see what's happening
- Use `say` blocks to print out the values of variables as the loop runs
- Check the number in your `repeat` loop to make sure it's correct

## Summary

- Loops are fundamental to writing efficient code
- The `forever` and `repeat` loops are two common types
- Debugging is a key skill for working with loops

## Further Reading

- A `repeat` loop is also called a [for loop](https://en.wikipedia.org/wiki/For_loop)
- A `forever` loop is also call an [infinite loop](https://en.wikipedia.org/wiki/Infinite_loop)
