# Flowchart & Pseudocode - [Danyal Khan](https://github.com/codeXdanyal)

### Table of Content

| Topics                                                                                              |
| --------------------------------------------------------------------------------------------------- |
| [Flowchart](#flowchart)                                                                             |
| [Pseudocode](#pseudocode)                                                                           |
| [Key Difference Between Flowchart and Pseudocode](#key-difference-between-flowchart-and-pseudocode) |
| [Beginner Tip](#beginner-tip)                                                                       |

## Flowchart

A **flowchart** is a diagram that visually represents the sequence of steps or logic flow in solving a problem. It helps you think logically before writing actual code. Each step of the solution is shown using specific symbols (shapes), connected with arrows to show direction or order.

#

### Flowchart Components

Flowcharts use predefined shapes to represent different types of operations:

| **Shape**          | **Purpose**                                       | **Example**                     |
| ------------------ | ------------------------------------------------- | ------------------------------- |
| **Oval (Ellipse)** | Represents Start and End points of the program.   | Start, End                      |
| **Parallelogram**  | Used for Input/Output operations.                 | Input A, B or Print Result      |
| **Rectangle**      | Represents a Process or Calculation step.         | Sum = A + B                     |
| **Diamond**        | Used for Decision or Condition checking (Yes/No). | A > B ?                         |
| **Arrows**         | the flow of execution between steps.              | Flow direction from Start → End |

#

### Example 1: Flowchart to Find Sum of Two Numbers

**Logic Steps:**

```text
1. Start
2. Input A and B
3. Calculate `Sum = A + B`
4. Print Sum
5. End
```

> [!NOTE]
> The parallelogram represents input/output (A, B, Sum), the rectangle represents processing (A + B), and the ovals mark the start and end.

#

### Example 2: Flowchart to Check Even or Odd Number

**Logic Steps:**

```text
1. Start
2. Input N
3. Check if `N % 2 == 0`
4. If Yes → Print “Even”
5. If No → Print “Odd”
6. End
```

> [!NOTE]
> The decision diamond checks the condition (`N % 2 == 0`). The flow splits into two branches: Yes → Even, No → Odd.

## Pseudocode

**Pseudocode** is a step-by-step description of how to solve a problem using plain English-like statements instead of real programming syntax.

- **Pseudo** means false or imitation, so pseudocode is fake code that looks like programming but isn’t bound to any specific language.
- It bridges the gap between logic and real code.

#

### Why Pseudocode is Useful

It helps beginners and developers from different backgrounds understand the logic without worrying about syntax errors.  
In professional environments, teams often write pseudocode first to communicate ideas before implementing them in different languages (Python, C++, Java, etc.).

#

### Pseudocode Writing Rules

1. Write each step clearly in simple English.
2. Focus on logic, not syntax.
3. Each step should represent a single logical action.
4. Indentation is optional but improves readability.

#

### Example 1: Pseudocode for Sum of Two Numbers

**Pseudocode:**

1. Input A, B
2. Sum = A + B
3. Print Sum
4. End

> The logic mirrors the flowchart — take two numbers, perform addition, and print the result.

#

### Example 2: Pseudocode for Area of a Square

**Pseudocode:**

1. Input A
2. Area = A \* A
3. Print Area
4. End

> This program takes side length A as input, calculates the area using A \* A, and displays it. Any beginner can easily translate this into actual code later.

#

### Example 3: Pseudocode for Even/Odd Check

**Pseudocode:**

1. Input N
2. If (N % 2 == 0)
   Print "Even"
   Else
   Print "Odd"
3. End

> Here, % represents the modulus operator used to check divisibility. This pseudocode clearly conveys the logic, no matter which programming language is later used.

## Key Difference Between Flowchart and Pseudocode

| **Aspect**             | **Flowchart**                            | **Pseudocode**                                  |
| ---------------------- | ---------------------------------------- | ----------------------------------------------- |
| **Representation**     | Visual (diagram with shapes)             | Text-based (English-like code)                  |
| **Purpose**            | To visualize the problem-solving process | To describe logic in human-readable form        |
| **Ease for Beginners** | Easier for visual learners               | Easier for those comfortable with writing steps |
| **Used**               | In Early logic-building and teaching     | Real-world problem design and planning          |

## Beginner Tip

If you’re new to programming, start with flowcharts to visualize the logic, then convert them into pseudocode. This builds both your logical thinking and structured problem-solving skills before writing real code.


> **_"Learning never exhausts the mind." – Leonardo da Vinci | Connect: [GitHub](https://github.com/codeXdanyal) | [LinkedIn](https://www.linkedin.com/in/danyal-khan-dk)_**