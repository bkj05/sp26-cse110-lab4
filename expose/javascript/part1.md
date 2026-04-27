# Part 1 Answers

## Question 1
Line 9 prints `values added: 20`.

This happens because `result` was declared with `var`, and `var` is function-scoped, so it can be accessed inside the function.

## Question 2
Line 13 prints `final result: 20`.

This happens because `var` is function-scoped, so `result` can still be accessed outside the if block.

## Question 3
You should not use `var` because it can be accessed outside the block where it was declared. This can cause bugs and unexpected behavior.

## Question 4
Line 9 prints `values added: 20`.

This works because `result` is being used inside the same block where it was declared with `let`.

## Question 5
Line 13 causes a `ReferenceError`.

This happens because `let` is block-scoped, so `result` cannot be accessed outside the if block.

## Question 6
Line 9 causes a `TypeError: Assignment to constant variable`.

This happens because `result` was declared with `const`, so it cannot be reassigned.

## Question 7
Line 13 is never reached because the code already errors before that when it tries to reassign the `const` variable.