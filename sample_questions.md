# CMPSC 201 Final Exam Sample Questions

Here are examples of the kinds of questions that might be asked. This is not intended to be a sample exam.

1. What are the final values of the variables `boo` and `ghost` in the following C code?

  ```
  double boo = 42.0;
  double ghost = boo;
  double *phantom = &ghost;
  *phantom = 21.0;
  ```

2. Choose one of the following three languages (C, Haskell, Python) and mention two composite data types (as defined in our textbook) that are built into the language you chose.

3. What is currying? Give an example.

4. The following statements are entered into the Haskell interactive environment:

  ```
  Prelude> let creature black lagoon = head black ++ (tail lagoon)
  Prelude> let black = [[1,2,3],[4,5,6]]
  Prelude> let lagoon = [7,8,9]
  Prelude> creature black lagoon
  ```

  What is printed?

5. What is polymorphism? How is it supported by Java?

6. Java supports multiple inheritance.

  Put "X" inside brackets [ ] of the correct answer.

  - [ ] True
  - [ ] False

7. Explain short-circuit evaluation with a simple example involving the logical "or" operator `||`.

8. Define "orthogonality" in a programming language.

9. In Fortran, arrays are stored in column-major order; in C and Java they are stored in row- major order. Does it make any difference to the programmer which method is used? Explain.

10. What are the two principle purposes of "types" in a language?

11. If you have tried to track down precise definitions of the terms "strongly typed" and "weakly typed" you have probably come away frustrated. Our textbook defines a "strongly typed language" as one that "prohibits ... the application of any operation to any object that is not intended to support that operation." Give an example of such an operation and such an object, using only standard primitive types.

12. What does a language-based security entail? Describe what it is, provide at least one problem that may arise in a language-based security and how it can be solved.
