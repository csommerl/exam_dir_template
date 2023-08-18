Exam Strategy
=====

---

[TOC]

---

# Lessons from the exam

Abbie:

>  You’ve got the idea exactly right in terms of cutting time down. In some places you had a bit more detail than really required, and sometimes included peripheral information. Most of these questions are well answered within 1-2 short paragraphs, for frame of reference. For example, when describing a topic that has a related code snippet, it is okay to not discuss every line of the code snippet. Rather, you should focus on only the lines that are related to demonstrating the concept the question is probing. Another example is question 9: you answered the question sufficiently within two paragraphs but then included the superfluous description of mutating vs reassigning primitive values and the code example. It can be a tricky balance of writing enough to answer the question fully without being verbose and wasting precious minutes. Hope that helps!

Aim for 1-2 paragraphs

When describing a topic that has a related code snippet, it is okay to not discuss every line of the code snippet.: probably applies to my answers to Question 4.

---

# Fixes

"Lines 2-3 demonstrates" => "Lines 2-3 demonstrate" (2)

"accepts no arguments" => "expects no arguments" (5)

"mutate the object referenced by the variables used to pass those arguments" => "mutate the object referenced by the variable used to pass that object as an argument" (10)

When there is an attempt to access a non-existent property of an object, `undefined` is returned, which represents the absence of a value. (18)

---

# Reminders

- If not sure about what concept is demonstrated, scan list of topics & markdown headings.
- Test code before copying & pasting
- Variables are not passed to or returned by functions; rather values or **references** are.
- Flag output, return value, object mutation, **non-local variables**.
- Make sure to tie together what happens later to what happened earlier.
  - E.g., "Since `greeting` is now assigned to `'Hi'` ..."
- If there is a comparison between how two things work (e.g., contrasting hoisting with `var` and hoisting with `let`), have two separate paragraphs.
- When there is complex code, e.g., chained methods, aim to explain first what it does at the user-level and then what its implementation is.
- Take care to write **invocation** of the `console.log` method.
- Use more user-level description.
  - For example, don't write: "the variable `char` passes its value to the invocation of the `console.log` method, thereby printing that value".
  - Instead, write: "the current character is passed by the local variable `char` to the invocation of the `console.log` method, thereby printing the current character" 

- Method callbacks: The callback function is invoked once per element of the calling array, with that element passed as an argument for the callback function.

- After I'm done: go over docs for concepts & add to explanations as needed.

---

# Key Points from the Study Guide for Test

- Summarize in one sentence what the code demonstrates.
  - Perhaps part of sentence for general concept.
  - And the rest of the sentence for something specific about the concept.
- Don't use bullet points.
- Don't explain everything.
  - For example, it isn't necessary to explain how a `while (true)` loop's implementation works.
- Use precise language.
  - Distinguish between what is **output** and what is **returned**.
  - Flag **object mutation** where relevant.
  - Distinguish between **global, non-local, and local variables**.
- Be consistent between two different acceptable formulations for using the concept of **assignment**.
  - The `greeting` variable is assigned to the string `'Hello'`.
  - The string `'Hello'` is assigned to the `greeting` variable.
- The term "variable" is used in the broadest sense possible, including variables declared with `let` and `const`, function parameters, and function names; but the term does not apply to property names in objects.
- Explain code at the right level:
  1. **Implementation level**: use when describing the way code does something
  2. **User level**: use when describing what code does, not how it does it (description 'for other developers' or 'for documentation purposes')
- Distinguish between `true` / `false` and **truthy** (evaluates to true) / **falsy** (evaluates to false).
- Distinguish between parameters and arguments:
  - **Parameters** are the names assigned to a function's arguments.
  - **Arguments** are the values that are passed to a function.
- What is passed to or returned by functions are **values or references**, not variables.

---

# Timing

1. Orientation (survey questions — 5 minutes)
2. 8 minutes per question: track answers with C(omplete), P(artial), S(kipped)
 	1. Survey - 00:05
	2. Q1-5   - 00:45
	3. Q6-10  - 01:25
	4. Q11-15 - 02:05
	5. Q16-20 - 02:45
	6. Review - 02:59
3. Review (15 minutes)

## Timers

1. Timer 1: 03 hours
2. Timer 2: 40 minutes
3. Timer 3: 08 minutes

Start at 9am

---

# Articles

- [Launch School’s 109 Written Assessment: A Non-Native English Speaker’s Perspective](https://medium.com/@raul.dehevia/launch-schools-109-written-assessment-a-non-native-english-speaker-s-perspective-d320b47368ba)
- [JS109 Written assessment - Afterword](https://www.dmytronaida.com/2020/05/27/js109-written-assessment.html)
- https://launchschool.com/posts/fffa01b1
- [Passing Launch School’s First Assessments: RB109](https://medium.com/launch-school/passing-launch-schools-first-assessments-rb109-4b2b047060dc)

Cf. [A Comprehensive List of RB109 Practice Problems & Other Tips](https://medium.com/launch-school/a-comprehensive-list-of-rb109-practice-problems-other-tips-4a4fbb3cdd7c)

---

# Lesson Notes

- [ ] lesson1_notes.md
- [ ] lesson2_notes.md
- [ ] lesson3_notes.md
- [ ] lesson4_notes.md
- [ ] lesson5_notes.md
- [ ] lesson6_notes.md
- [ ] small_problem_lessons.md
- [ ] Study group lessons

---

# JS101 Exercises to Redo

## Lesson 3.4

- [ ] [Lesson 3.4, Question 1](https://launchschool.com/lessons/0206c7f9/assignments/da7ec933)
- [ ] [Lesson 3.4, Question 2](https://launchschool.com/lessons/0206c7f9/assignments/da7ec933)
- [ ] [Lesson 3.4, Question 4](https://launchschool.com/lessons/0206c7f9/assignments/da7ec933)
- [ ] [Lesson 3.4, Question 5](https://launchschool.com/lessons/0206c7f9/assignments/da7ec933)

## Lesson 3.5

- [ ] [Lesson 3.5, Question 3](https://launchschool.com/lessons/0206c7f9/assignments/e4fb9aaf)
- [ ] [Lesson 3.5, Question 5](https://launchschool.com/lessons/0206c7f9/assignments/e4fb9aaf)
- [ ] [Lesson 3.5, Question 6](https://launchschool.com/lessons/0206c7f9/assignments/e4fb9aaf)
- [ ] [Lesson 3.5, Question 8](https://launchschool.com/lessons/0206c7f9/assignments/e4fb9aaf)

## Lesson 3.6

- [ ] [Lesson 3.6, Question 1](https://launchschool.com/lessons/0206c7f9/assignments/59c055ee)

## Lesson 4.11

- [ ] [Lesson 4.11, Practice Problem 7](https://launchschool.com/lessons/60e10aa5/assignments/d4f91ca2)
- [ ] [Lesson 4.11, Practice Problem 10](https://launchschool.com/lessons/60e10aa5/assignments/d4f91ca2)

## Lesson 4 Quiz

- [ ] [Lesson 4 Quiz, Question 1](https://launchschool.com/quizzes/3548c910)
- [ ] [Lesson 4 Quiz, Question 12](https://launchschool.com/quizzes/3548c910)
- [ ] [Lesson 4 Quiz, Question 16](https://launchschool.com/quizzes/3548c910)

## Lesson 5

- [ ] [Lesson 5, 5.4, Example 7](https://launchschool.com/lessons/778acada/assignments/a2ba7936)
- [ ] [Lesson 5, 5.4, Example 8](https://launchschool.com/lessons/778acada/assignments/a2ba7936)
- [ ] [Lesson 5, 5.4, Example 9](https://launchschool.com/lessons/778acada/assignments/a2ba7936)
- [ ] [Lesson 5.5, Practice Problem 11](https://launchschool.com/lessons/778acada/assignments/8c5df017)
- [ ] [Lesson 5.5, Practice Problem 14](https://launchschool.com/lessons/778acada/assignments/8c5df017)
- [ ] [Lesson 5.5, Practice Problem 17](https://launchschool.com/lessons/778acada/assignments/8c5df017)
- [ ] [Lesson 5 Quiz, Question 4](https://launchschool.com/quizzes/cd3540bb)

---

# Source of Practice Test Questions

1. Local Variable Scope Example 3
2. (Variable Shadowing Example 1)
3. (Variables as Pointers Example 1)
4. (Variables as Pointers Example 3)
5.  (Study Group)
6. (Textbook Pass-by-Reference)
7. (Textbook More Stuff: various)
8.  (Variables as Pointers Example 11)
9.  (Object Mutability Example 1)
10.  (Object Mutability Example 10)
11.  (Array Methods Example 1)
12.  (Array Methods Example 5)
13.  (Study session)
14.  (Lesson 5 Quiz 1)
15.  (Study Group)
16.  (Rafiq)
17.  (Other Array Methods Example 4)
18.  (Other Array Methods Example 5)
19.  (Truthiness, Study Group)
20.  (JS101 Pass by Value)

