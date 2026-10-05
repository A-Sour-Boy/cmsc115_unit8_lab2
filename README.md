# Reflection – AI Number Program Lab

## Student Name:
Travis Doughty

## GitHub Repository Link:
https://github.com/A-Sour-Boy/cmsc115_unit8_lab2

## Iteration 1: AI-generated implementation

What the AI code does:
- The AI-generated code added all numbers in the array and returned the total sum.

Tests passed/failed:
- Some tests passed, but tests expecting the largest value in the array failed.

What surprised you:
- The code worked correctly but solved a different problem than the tests were checking.

Commit message:
- Iteration 1: AI-generated implementation

---

## Iteration 2: largest value implementation

What changed:
- The method was changed to return the largest value in the array instead of the sum.

What improved:
- More JUnit tests passed because the program now matched the expected behavior.

What still failed and why:
- The empty-array test still failed because the method did not handle arrays with no elements.

Commit message:
- Iteration 2: largest value implementation

---

## Iteration 3

Final behavior:
- The method returns the largest value in the array and returns Integer.MIN_VALUE when the array is empty.

What was fixed:
- An empty-array check was added so the method could handle arrays with no values.

What you learned:
- Small changes can fix failing tests and improve the reliability of a program.

Commit message:
- Iteration 3: final version passing all tests

---

## Final Reflection

- How did AI responses change across prompts?
  - The AI responses became more accurate and useful as the prompts became more specific.

- How did testing affect your changes?
  - The JUnit tests showed what was incorrect and helped guide each improvement to the code.

- What did version control help you understand?
  - Version control made it easy to track changes, compare versions, and see how the program improved over time.
