# Part 2 Answers

## Question 1
Line 12 prints 3 because `var i` is function-scoped, so it is accessible outside the loop after the loop ends.

## Question 2
Line 13 causes a ReferenceError because `discountedPrice` was declared with `let` inside the loop and is not accessible outside.

## Question 3
Line 14 prints the last computed value because `var finalPrice` is function-scoped and accessible outside the loop.

## Question 4
The function returns an array of discounted prices because values are pushed into the `discounted` array during each loop iteration.

## Question 5
Line 12 causes a TypeError: Assignment to constant variable because `discountedPrice` is declared with `const` and then reassigned.

## Question 6
Line 13 causes a ReferenceError because the variable is block-scoped and not accessible outside the loop.

## Question 7
Line 14 causes a ReferenceError because `i` was declared with `let` and is not accessible outside the loop.

## Question 8
The function returns an array of discounted prices because the calculations are done correctly within the loop.

## Question 9
Line 11 causes a ReferenceError because the variable is not defined in that scope.

## Question 10
Line 12 causes a ReferenceError due to block scoping of variables.

## Question 11
The function returns correct values if variables are properly scoped, otherwise it throws an error.

## Question 12 (Objects)

A. student.name  
B. student["Grad Year"]  
C. student.greeting()  
D. student.favoriteTeacher.name  
E. student.courseLoad[0]  

---

## Question 13 (Arithmetic)

'3' + 2 = "32"  
→ string + number → string concatenation  

'3' - 2 = 1  
→ string converted to number  

3 + null = 3  
→ null becomes 0  

'3' + null = "3null"  

true + 3 = 4  
→ true = 1  

false + null = 0  
→ false = 0, null = 0  

'3' + undefined = "3undefined"  

'3' - undefined = NaN  

---

## Question 14 (Comparison)

'2' > 1 → true  

'2' < '12' → false  
→ string comparison  

2 == '2' → true  
→ type coercion  

2 === '2' → false  
→ strict comparison  

true == 2 → false  

true === Boolean(2) → true  

---

## Question 15

== compares values after converting types  
=== compares both value and type without conversion  

---

## Question 17

Result: [2, 4, 6]

Explanation:
Each number is passed into the function and multiplied by 2.

---

## Question 19

Output:
1  
4  
3  
2  

Explanation:
1 and 4 run immediately.  
3 runs next (setTimeout with 0 delay).  
2 runs last (setTimeout with delay).