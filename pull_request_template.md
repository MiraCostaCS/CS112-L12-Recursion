## 📋 Project Assessment: Lab #12 - Recursion

### 1. Development & Workflow
- [ ] **Commit Messages:** Descriptive and incremental commits tracking recursive algorithm design, base case handling, and testing.

### 2. Functional Requirements (Recursive Algorithm)

#### Method Signature & Setup
- [ ] **Header Definition:** Method defined in `Main.java` with signature accepting `amount` (double), `rate` (double), and `years` (int), returning a double.

#### Base Case Implementation
- [ ] **Stop Condition:** Correctly checks designed stop condition.
- [ ] **Base Return:** Returns the current `amount` without performing further calculations when the base case is reached.

#### Recursive Step Implementation
- [ ] **Compound Calculation:** Calculates `newBalance` for the current year.
- [ ] **Recursive Invocation:** Makes a self-referential call passing new arguments.
- [ ] **Convergence:** Ensures control variable changes toward stop condition on every invocation to prevent infinite recursion and stack overflow errors.

#### Program Integration & Testing
- [ ] **Main Integration:** Uncommented driver code print statements in `main()` to test the recursive method.
- [ ] **Mathematical Verification:** Verified output accuracy against test cases:
    - [ ] `recursiveInterestCalc(7000, 0.07, 5)` yields $9817.86
    - [ ] `recursiveInterestCalc(5000, 0.04, 13)` yields $8325.37
- [ ] **Iterative Comparison:** Verified that recursive output matches the existing iterative method results.

### 3. Code Quality & Standards
- [ ] **Recursion Logic:** Clear separation between base case and recursive step without redundant checks.
- [ ] **Formatting & Style:** Proper indentation, clear variable naming, and inclusion of method-level comments.
