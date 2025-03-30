# Mathematics Extension 1 - Worked Solutions

## HSC 2024 EXTENSION 1
### Question 1: The polynomial x³ + 2x² - 5x - 6 has zeros -1, -3 and α. What is the value of α?

**Solution:**
- If a polynomial has zeros at x = -1, x = -3, and x = α, then it can be written as: P(x) = k(x+1)(x+3)(x-α) where k is a constant.
  - When a polynomial has zeros, we can write it as a product of factors (x-zero).
- Expanding: P(x) = k(x+1)(x+3)(x-α) = k[(x+1)(x+3)](x-α) = k[(x²+4x+3)](x-α)
  - Multiplying the first two brackets.
- P(x) = k[x³+4x²+3x-αx²-4αx-3α] = k[x³+(4-α)x²+(3-4α)x-3α]
  - Distributing the third factor and collecting like terms.
- Comparing with x³ + 2x² - 5x - 6:
  - k(4-α) = 2, so k = 2/(4-α)
  - k(3-4α) = -5
  - k(-3α) = -6, so k = 2
  - From k = 2, we get (4-α) = 1, so α = 3
  - Checking: 2(3-4×3) = 2(3-12) = 2(-9) = -18 ≠ -5, but this is using α = 3
  - Let's verify using the third equation: 2(-3α) = -6, so α = 1
  - Now checking: If α = 1, then 2(4-1) = 6 ≠ 2
- Let's restart by directly using the factor theorem:
  - If the polynomial is x³ + 2x² - 5x - 6 and it has zeros at x = -1 and x = -3, then:
  - P(x) = (x+1)(x+3)(x-α)
  - Expanding: P(x) = (x²+4x+3)(x-α) = x³-αx²+4x²-4αx+3x-3α = x³+(4-α)x²+(3-4α)x-3α
  - Comparing with x³ + 2x² - 5x - 6:
    - 4-α = 2, so α = 2
    - 3-4α = -5, so 3-4(2) = 3-8 = -5 ✓
    - -3α = -6, so -3(2) = -6 ✓
- Therefore, α = 2, which corresponds to option B.

## HSC 2023 EXTENSION 1
### Question (c): Consider the polynomial P(x) = x³ + ax² + bx - 12, where a and b are real numbers. It is given that x + 1 is a factor of P(x) and that, when P(x) is divided by x - 2, the remainder is -18. Find a and b.

**Solution:**
- If (x+1) is a factor of P(x), then P(-1) = 0:
  - P(-1) = (-1)³ + a(-1)² + b(-1) - 12 = -1 + a - b - 12 = 0
  - This gives us: a - b = 13
  - This is our first equation.
- When P(x) is divided by (x-2), the remainder equals P(2):
  - P(2) = 2³ + a(2)² + b(2) - 12 = 8 + 4a + 2b - 12 = -18
  - 4a + 2b = -14
  - a + 0.5b = -3.5
  - This is our second equation.
- To solve these simultaneous equations:
  - From the first equation: a = 13 + b
  - Substituting into the second equation:
    - (13 + b) + 0.5b = -3.5
    - 13 + b + 0.5b = -3.5
    - 13 + 1.5b = -3.5
    - 1.5b = -16.5
    - b = -11
  - Now we can find a by substituting back:
    - a = 13 + (-11) = 2
- Therefore, a = 2 and b = -11.

## HSC 2022 EXTENSION 1
### Question 3: Let P(x) be a polynomial of degree 5. When P(x) is divided by the polynomial Q(x), the remainder is 2x + 5. Which of the following is true about the degree of Q?

**Solution:**
- If P(x) is divided by Q(x), the remainder has degree less than the degree of Q(x).
  - This is based on the polynomial remainder theorem.
- The remainder is 2x + 5, which has degree 1.
  - Since the remainder has terms up to x¹.
- Therefore, the degree of Q(x) must be at least 2.
  - For the remainder to have degree 1, Q(x) must have degree at least 2.
- The degree of Q(x) cannot be 1, because if Q(x) had degree 1, the remainder would be a constant.
  - If Q(x) = ax + b, the remainder would have degree 0 (a constant).
- So the degree of Q(x) could be 2, 3, 4, or 5.
  - Any degree ≥ 2 would allow a remainder of degree 1.
- Therefore, D is correct: "The degree could be 2."

### Question (f): Solve x/(2-x) ≥ 5.

**Solution:**
- Starting with x/(2-x) ≥ 5
  - This is a rational inequality.
- Multiply both sides by (2-x): We need to check the sign of (2-x) first:
  - If 2-x > 0, then x < 2, and multiplying preserves the inequality.
  - If 2-x < 0, then x > 2, and multiplying reverses the inequality.
- Case 1: x < 2
  - x ≥ 5(2-x)
  - x ≥ 10-5x
  - 6x ≥ 10
  - x ≥ 5/3
  - So the solution is 5/3 ≤ x < 2.
- Case 2: x > 2
  - x ≤ 5(2-x)
  - x ≤ 10-5x
  - 6x ≤ 10
  - x ≤ 5/3
  - This is incompatible with x > 2, so there are no solutions in this case.
- The solution is 5/3 ≤ x < 2.

## HSC 2021 EXTENSION 1
### Question 3: What is the remainder when P(x) = -x³ - 2x² - 3x + 8 is divided by x + 2?

**Solution:**
- To find the remainder when divided by (x+2), we compute P(-2).
  - Using the remainder theorem: if P(x) is divided by (x-a), the remainder is P(a).
  - For division by (x+2) or (x-(-2)), the remainder is P(-2).
- P(-2) = -(-2)³ - 2(-2)² - 3(-2) + 8
  - = -(−8) - 2(4) - 3(-2) + 8
  - = 8 - 8 + 6 + 8
  - = 14
- Therefore, the remainder is 14, which corresponds to option D.

### Question (h): The roots of x⁴ - 3x + 6 = 0 are α, β, γ and δ. What is the value of 1/α + 1/β + 1/γ + 1/δ?

**Solution:**
- For a polynomial equation anx^n + an-1x^(n-1) + ... + a1x + a0 = 0 with roots α, β, γ, ...:
  - Sum of reciprocals of roots = a1/a0 (if a0 ≠ 0)
  - This follows from Vieta's formulas.
- For x⁴ - 3x + 6 = 0, we have a4 = 1, a1 = -3, a0 = 6
  - Sum of reciprocals = a1/a0 = -3/6 = -1/2
- Therefore, 1/α + 1/β + 1/γ + 1/δ = -1/2

## HSC 2020 EXTENSION 1
### Question 1: Which diagram best represents the solution set of x² - 2x - 3 ≥ 0?

**Solution:**
- To solve x² - 2x - 3 ≥ 0:
  - First, we find where x² - 2x - 3 = 0 by factoring.
  - x² - 2x - 3 = (x-3)(x+1) = 0
  - The roots are x = 3 and x = -1.
- The quadratic function is positive when:
  - Either both factors are positive: x > 3
  - Or both factors are negative: x < -1
- So the solution is x ≤ -1 or x ≥ 3
  - This is represented by the regions to the left of -1 and to the right of 3.
- Therefore, option A is correct, showing the number line with points at -1 and 3.

### Question (a): Let P(x) = x³ + 3x² - 13x + 6. (i) Show that P(2) = 0. (ii) Hence, factor the polynomial P(x) as A(x)B(x), where B(x) is a quadratic polynomial.

**Solution:**
- (i) Computing P(2):
  - P(2) = 2³ + 3(2)² - 13(2) + 6
  - = 8 + 3(4) - 26 + 6
  - = 8 + 12 - 26 + 6
  - = 0
  - Therefore, P(2) = 0, which means (x-2) is a factor of P(x).
- (ii) Since (x-2) is a factor, P(x) = (x-2)Q(x) where Q(x) is a quadratic polynomial.
  - We can find Q(x) using polynomial division or synthetic division.
  - Using synthetic division with 2:
    - 1 | 3 | -13 | 6
      2 | 10 | -6
    - 1 | 5 | -3 | 0
  - Therefore, Q(x) = x² + 5x - 3
  - P(x) = (x-2)(x² + 5x - 3)
- We can further factorize the quadratic:
  - x² + 5x - 3 = (x+6)(x-1)
  - Therefore, P(x) = (x-2)(x+6)(x-1)

## ABBOTSLEIGH 2024 TRIAL
### Question: For the polynomial P(x) = x³ - 3x² + 4, it is known that P′(2) = 0. Which of the following statements is incorrect?

**Solution:**
- Let's calculate P'(x) first:
  - P'(x) = 3x² - 6x
  - P'(2) = 3(2)² - 6(2) = 12 - 12 = 0
  - So the statement that P'(2) = 0 is correct.
- Let's check each statement:
  - A. P(2) = 0
    - P(2) = 2³ - 3(2)² + 4 = 8 - 12 + 4 = 0
    - This statement is correct.
  - B. P(x) has one of its roots at x = -1
    - P(-1) = (-1)³ - 3(-1)² + 4 = -1 - 3 + 4 = 0
    - This statement is correct.
  - C. P(x) has a double root at x = -2
    - P(-2) = (-2)³ - 3(-2)² + 4 = -8 - 12 + 4 = -16 ≠ 0
    - This statement is incorrect.
  - D. P(x) is divisible by (x - 2)
    - We already verified P(2) = 0, so (x-2) is a factor.
    - This statement is correct.
- Therefore, option C is incorrect.

### Question (a): Solve the inequality (2-3x)/(7x+2) ≤ -2.

**Solution:**
- Starting with (2-3x)/(7x+2) ≤ -2
  - We need to consider the sign of the denominator.
- Case 1: 7x+2 > 0, which means x > -2/7
  - Multiply both sides by (7x+2), maintaining the inequality:
  - 2-3x ≤ -2(7x+2)
  - 2-3x ≤ -14x-4
  - 2-3x ≤ -14x-4
  - 11x ≤ -6
  - x ≤ -6/11
  - So the solution is -2/7 < x ≤ -6/11.
- Case 2: 7x+2 < 0, which means x < -2/7
  - Multiply both sides by (7x+2), reversing the inequality:
  - 2-3x ≥ -2(7x+2)
  - 2-3x ≥ -14x-4
  - 2-3x ≥ -14x-4
  - 11x ≥ -6
  - x ≥ -6/11
  - This contradicts x < -2/7 since -6/11 > -2/7, so there are no solutions in this case.
- The solution is -2/7 < x ≤ -6/11 or approximately -0.286 < x ≤ -0.545.

## ASCHAM 2024 EXTENSION 1
### Question 12 (a): The polynomial P(x) = x³ + bx² + cx + 3 has a root of multiplicity 2 at x = -1. Find the values of b and c.

**Solution:**
- If x = -1 is a root of multiplicity 2 of P(x), then:
  - (x+1)² is a factor of P(x)
  - P(-1) = 0 and P'(-1) = 0
- Let's use these conditions:
  - P(-1) = (-1)³ + b(-1)² + c(-1) + 3 = -1 + b - c + 3 = 0
  - This gives us: b - c = -2
- For the derivative:
  - P'(x) = 3x² + 2bx + c
  - P'(-1) = 3(-1)² + 2b(-1) + c = 3 - 2b + c = 0
  - This gives us: -2b + c = -3
- Solving these equations:
  - From the first equation: b - c = -2, so c = b + 2
  - Substituting into the second equation:
    - -2b + (b + 2) = -3
    - -2b + b + 2 = -3
    - -b + 2 = -3
    - -b = -5
    - b = 5
  - Now we can find c:
    - c = b + 2 = 5 + 2 = 7
- Therefore, b = 5 and c = 7.

### Question 14 (a): Solve 2/|x-1| ≥ 3.

**Solution:**
- Starting with 2/|x-1| ≥ 3
  - Rearranging: |x-1| ≤ 2/3
  - This means: -2/3 ≤ x-1 ≤ 2/3
  - Adding 1 to all parts: 1-2/3 ≤ x ≤ 1+2/3
  - Simplifying: 1/3 ≤ x ≤ 5/3
- Therefore, the solution is 1/3 ≤ x ≤ 5/3.

## BAULKHAM HILLS 2024 TRIAL EXT 1
### Question (b): Consider the polynomial f(x) = x³ + (a+2)x² - 2x + b where a and b are non-zero integers. It is given that (x-2) and (x+a) are both factors of f(x) with a > 0.

**Solution for (i): Justify why 4a + b = -12**
- Since (x-2) is a factor, f(2) = 0:
  - f(2) = 2³ + (a+2)2² - 2(2) + b = 0
  - 8 + 4(a+2) - 4 + b = 0
  - 8 + 4a + 8 - 4 + b = 0
  - 12 + 4a + b = 0
  - 4a + b = -12
- Therefore, 4a + b = -12 is justified.

**Solution for (ii): Show also that 2a² + 2a + b = 0**
- Since (x+a) is a factor, f(-a) = 0:
  - f(-a) = (-a)³ + (a+2)(-a)² - 2(-a) + b = 0
  - -a³ + (a+2)a² + 2a + b = 0
  - -a³ + a³ + 2a² + 2a + b = 0
  - 2a² + 2a + b = 0
- Therefore, 2a² + 2a + b = 0 is shown.

**Solution for (iii): Hence evaluate the integers a and b**
- We have two equations:
  - 4a + b = -12
  - 2a² + 2a + b = 0
- Substituting the first equation into the second:
  - 2a² + 2a + (-12-4a) = 0
  - 2a² + 2a - 12 - 4a = 0
  - 2a² - 2a - 12 = 0
  - a² - a - 6 = 0
  - (a-3)(a+2) = 0
  - a = 3 or a = -2
- Since a > 0, we have a = 3.
- Now we can find b:
  - 4a + b = -12
  - 4(3) + b = -12
  - 12 + b = -12
  - b = -24
- Therefore, a = 3 and b = -24.

**Solution for (iv): Fully factorise f(x) and graph y = f(x)**
- f(x) = x³ + (a+2)x² - 2x + b = x³ + 5x² - 2x - 24
- We know (x-2) and (x+3) are factors, so:
  - f(x) = (x-2)(x+3)Q(x), where Q(x) is a linear polynomial.
- Expanding the known factors:
  - (x-2)(x+3) = x² + 3x - 2x - 6 = x² + x - 6
- So f(x) = (x² + x - 6)Q(x)
- Let's assume Q(x) = x + c and determine c:
  - f(x) = (x² + x - 6)(x + c)
  - Expanding: x³ + cx² + x² + cx - 6x - 6c
  - Collecting like terms: x³ + (1+c)x² + (c-6)x - 6c
- Comparing with the original f(x) = x³ + 5x² - 2x - 24:
  - 1+c = 5, so c = 4
  - c-6 = -2, so c = 4 (confirms)
  - -6c = -24, so c = 4 (confirms)
- Therefore, f(x) = (x-2)(x+3)(x+4) = (x-2)(x+3)(x+4)
- For the graph, the x-intercepts are at x = 2, x = -3, and x = -4.
- The y-intercept is f(0) = -24.
- Since the leading coefficient is 1 (positive), the graph goes up to the right.

## BLACKTOWN 2024 TRIAL EXT 1
### Question 11 (b): The polynomial P(x) = 5x³ - 2x + 20 has roots α, β and γ.

**Solution for (i): Evaluate αβγ**
- For a polynomial a₃x³ + a₂x² + a₁x + a₀ with roots α, β, and γ:
  - Product of roots = αβγ = (-1)³(a₀/a₃)
  - This is from Vieta's formulas.
- For P(x) = 5x³ - 2x + 20, we have a₃ = 5, a₂ = 0, a₁ = -2, a₀ = 20
  - αβγ = -a₀/a₃ = -20/5 = -4
- Therefore, αβγ = -4.

**Solution for (ii): Evaluate α² + β² + γ²**
- For a cubic polynomial, if we denote s₁ = α + β + γ and s₂ = αβ + βγ + αγ:
  - α² + β² + γ² = s₁² - 2s₂
  - From Vieta's formulas, for a cubic polynomial a₃x³ + a₂x² + a₁x + a₀:
    - s₁ = -a₂/a₃
    - s₂ = a₁/a₃
- For P(x) = 5x³ - 2x + 20:
  - s₁ = -0/5 = 0
  - s₂ = -2/5
  - α² + β² + γ² = s₁² - 2s₂ = 0² - 2(-2/5) = 0 + 4/5 = 4/5
- Therefore, α² + β² + γ² = 4/5.

### Question (c): Solve 10x/(1+3x) ≤ 3

**Solution:**
- Starting with 10x/(1+3x) ≤ 3
  - We need to consider the sign of the denominator.
- Since the denominator 1+3x = 0 when x = -1/3, we need to consider cases:
- Case 1: 1+3x > 0, which means x > -1/3
  - Multiply both sides by (1+3x), maintaining the inequality:
  - 10x ≤ 3(1+3x)
  - 10x ≤ 3 + 9x
  - x ≤ 3
  - So the solution is -1/3 < x ≤ 3.
- Case 2: 1+3x < 0, which means x < -1/3
  - Multiply both sides by (1+3x), reversing the inequality:
  - 10x ≥ 3(1+3x)
  - 10x ≥ 3 + 9x
  - x ≥ 3
  - This contradicts x < -1/3, so there are no solutions in this case.
- The solution is -1/3 < x ≤ 3.

## CARINGBAH 2024 EXT 1 TRIAL
### Question 2: The solution to the inequality 3/(x-1) < 5 can be expressed as:

**Solution:**
- Starting with 3/(x-1) < 5
  - We need to consider the sign of the denominator.
- Since the denominator x-1 = 0 when x = 1, we need to consider cases:
- Case 1: x-1 > 0, which means x > 1
  - Multiply both sides by (x-1), maintaining the inequality:
  - 3 < 5(x-1)
  - 3 < 5x-5
  - 8 < 5x
  - 8/5 < x
  - So the solution is x > 8/5 (and also x > 1, which is implied by x > 8/5).
- Case 2: x-1 < 0, which means x < 1
  - Multiply both sides by (x-1), reversing the inequality:
  - 3 > 5(x-1)
  - 3 > 5x-5
  - 8 > 5x
  - x < 8/5
  - So the solution is x < 1 (since we already assumed x < 1).
- Combining both cases, the solution is x < 1 or x > 8/5
  - This can be written as x ∈ (-∞, 1) ∪ (8/5, ∞)
- Therefore, option D is correct.

## CHELTENHAM GIRLS 2021 TRIAL EXT 1
### Question 6(a): Let P(x) = x³ + 5x² + x - 15. (i) Show that P(-3) = 0. (ii) Hence, factorise the polynomial P(x) as A(x)B(x), where B(x) is a quadratic polynomial.

**Solution for (i): Show that P(-3) = 0**
- Computing P(-3):
  - P(-3) = (-3)³ + 5(-3)² + (-3) - 15
  - = -27 + 5(9) - 3 - 15
  - = -27 + 45 - 3 - 15
  - = 0
- Therefore, P(-3) = 0.

**Solution for (ii): Factorize P(x)**
- Since P(-3) = 0, (x+3) is a factor of P(x).
- We can write P(x) = (x+3)Q(x) where Q(x) is a quadratic polynomial.
- To find Q(x), we can use synthetic division:
  - Using synthetic division with -3:
    - 1 | 5 | 1 | -15
      -3 | -6 | 15
    - 1 | 2 | -5 | 0
  - Therefore, Q(x) = x² + 2x - 5
- So P(x) = (x+3)(x² + 2x - 5)
- We can further factorize the quadratic:
  - x² + 2x - 5 = (x+5)(x-1)
  - Therefore, P(x) = (x+3)(x+5)(x-1)

### Question 6(b): For what values of x is x/(x-1) ≥ -2?

**Solution:**
- Starting with x/(x-1) ≥ -2
  - We need to consider the sign of the denominator.
- Since the denominator x-1 = 0 when x = 1, we need to consider cases:
- Case 1: x-1 > 0, which means x > 1
  - Multiply both sides by (x-1), maintaining the inequality:
  - x ≥ -2(x-1)
  - x ≥ -2x+2
  - 3x ≥ 2
  - x ≥ 2/3
  - So the solution is x ≥ 2/3 (and also x > 1, which means x ≥ 1).
- Case 2: x-1 < 0, which means x < 1
  - Multiply both sides by (x-1), reversing the inequality:
  - x ≤ -2(x-1)
  - x ≤ -2x+2
  - 3x ≤ 2
  - x ≤ 2/3
  - So the solution is x ≤ 2/3 (and also x < 1, which is consistent).
- Combining both cases, the solution is x ≤ 2/3 or x ≥ 1.

## CHERRYBROOK TECHNOLOGY 2022 TRIAL EXT 1
### Question 11(a): Solve the inequality 3/(x-1) < 2.

**Solution:**
- Starting with 3/(x-1) < 2
  - We need to consider the sign of the denominator.
- Since the denominator x-1 = 0 when x = 1, we need to consider cases:
- Case 1: x-1 > 0, which means x > 1
  - Multiply both sides by (x-1), maintaining the inequality:
  - 3 < 2(x-1)
  - 3 < 2x-2
  - 5 < 2x
  - 5/2 < x
  - So the solution is x > 5/2 (and also x > 1, which is implied by x > 5/2).
- Case 2: x-1 < 0, which means x < 1
  - Multiply both sides by (x-1), reversing the inequality:
  - 3 > 2(x-1)
  - 3 > 2x-2
  - 5 > 2x
  - x < 5/2
  - So the solution is x < 1 (since we already assumed x < 1).
- Combining both cases, the solution is x < 1 or x > 5/2.

### Question 11(c): The polynomial equation x⁴ + 4x³ - 3x² + 5x - 7 = 0 has roots α, β, γ and δ. Find the value of 1/α + 1/β + 1/γ + 1/δ.

**Solution:**
- Well when we have
  - 1/α + 1/β + 1/γ + 1/δ
- we need to find what each fraction is missing, which would look like
  - βγδ + αγδ + αβδ + αβγ / αβγδ
- Which now becomes
  - -d/a ÷ e/a
- Subbing in values
  - -5/1 ÷ -7/1
- Which becomes
  - -5/1 * 1/-7
  - -5/-7
- Multiplying by -1/-1
  - 5/7
- So,
  - 1/α + 1/β + 1/γ + 1/δ
- Equals
  - 5/7 

### Question 12(d)
When the polynomial P(x) is divided by (x - 1)(x + 4), the quotient is Q(x) and the remainder is R(x). The remainder R(x) can be written in the general form as R(x) = ax + b.
- It is known that P(1) = -4 and when P(x) is divided by (x + 4), the remainder is 1.
- Find the values of a and b.

#### Solution:
- When P(x) is divided by (x - 1)(x + 4), we can write:
  - P(x) = (x - 1)(x + 4)Q(x) + R(x)
  - Since the divisor is degree 2, the remainder R(x) must be degree at most 1, so R(x) = ax + b

- Using the first condition P(1) = -4:
  - P(1) = (1 - 1)(1 + 4)Q(1) + R(1)
  - P(1) = 0 × Q(1) + R(1)
  - -4 = R(1) = a(1) + b
  - Therefore: a + b = -4 ... (Equation 1)

- Using the second condition that when P(x) is divided by (x + 4), the remainder is 1:
  - By the Remainder Theorem, this means P(-4) = 1
  - Substituting into our original equation:
  - P(-4) = (-4 - 1)(-4 + 4)Q(-4) + R(-4)
  - P(-4) = (-5)(0)Q(-4) + R(-4)
  - 1 = R(-4) = a(-4) + b
  - Therefore: -4a + b = 1 ... (Equation 2)

- Solving the system of equations:
  - a + b = -4
  - -4a + b = 1
  - Subtracting the second equation from the first:
  - 5a = -5
  - a = -1
  - Substituting into the first equation:
  - -1 + b = -4
  - b = -3

- Therefore a = -1 and b = -3

## **CRANBROOK 2023 TRIAL EXT 1**
### MCQ: Remainder when Q(x) is divided by (x+1)
The polynomials P(x) and Q(x) are such that P(x) = (x+3)(x-2)Q(x). When P(x) is divided by (x+1), the remainder is 12. What is the remainder when Q(x) is divided by (x+1)?
- A. -3
- B. -2
- C. 2
- D. 3

#### Solution:
- We know P(x) = (x+3)(x-2)Q(x)
- By the Remainder Theorem, when P(x) is divided by (x+1), the remainder equals P(-1)
- We're given that the remainder is 12, so P(-1) = 12
  
- Substituting x = -1 into the equation P(x) = (x+3)(x-2)Q(x):
  - P(-1) = (-1+3)(-1-2)Q(-1)
  - P(-1) = (2)(-3)Q(-1)
  - 12 = -6Q(-1)
  - Q(-1) = -2
  
- By the Remainder Theorem, the remainder when Q(x) is divided by (x+1) is Q(-1) = -2
- Therefore, the answer is B. -2

### Question 11(a): Solve |5x-1| < 5
#### Solution:
- Using the definition of absolute value, we have two cases:
  - Case 1: 5x-1 ≥ 0, which means x ≥ 1/5
    - Then |5x-1| = 5x-1
    - So: 5x-1 < 5
    - 5x < 6
    - x < 6/5
    - So for this case: 1/5 ≤ x < 6/5
      
  - Case 2: 5x-1 < 0, which means x < 1/5
    - Then |5x-1| = -(5x-1) = 1-5x
    - So: 1-5x < 5
    - -5x < 4
    - x > -4/5
    - So for this case: -4/5 < x < 1/5
      
- Combining both cases: -4/5 < x < 6/5

### Question 11(c): Find values for polynomial roots
The polynomial P(x) = x³ + 3x² - 4x - 5 has roots α, β and γ

#### Part (i): Find α + β + γ
- For a polynomial of form ax³ + bx² + cx + d, the sum of roots is -b/a
- In P(x) = x³ + 3x² - 4x - 5, we have a = 1 and b = 3
- Therefore, α + β + γ = -3/1 = -3

#### Part (ii): Find α² + β² + γ²
- For a cubic polynomial with roots α, β, and γ:
  - (α + β + γ)² = α² + β² + γ² + 2(αβ + αγ + βγ)
  - So α² + β² + γ² = (α + β + γ)² - 2(αβ + αγ + βγ)
      
- We know α + β + γ = -3
- For a polynomial of form ax³ + bx² + cx + d:
  - The sum of products of roots taken two at a time is c/a
  - So αβ + αγ + βγ = -4/1 = -4
      
- Therefore:
  - α² + β² + γ² = (-3)² - 2(-4)
  - α² + β² + γ² = 9 + 8
  - α² + β² + γ² = 17

## **FORT ST HIGH**
### MCQ: Solution to inequality 3/(x-2) ≤ 4
The solution to the inequality 3/(x-2) ≤ 4 is given by:
- A. x < -2 and x ≥ -11/4
- B. x > -2 and x ≤ -11/4
- C. x < 2 and x ≥ 11/4
- D. x > 2 and x ≤ 11/4

#### Solution:
- We need to be careful with the domain: x ≠ 2 (since we can't divide by zero)
- Multiplying both sides by (x-2):
  - We need to consider two cases based on whether (x-2) is positive or negative

- Case 1: When x > 2, (x-2) is positive
  - 3 ≤ 4(x-2)
  - 3 ≤ 4x-8
  - 11 ≤ 4x
  - x ≥ 11/4
  - So for this case: x > 2 and x ≥ 11/4, which simplifies to x ≥ 11/4 (since 11/4 > 2)

- Case 2: When x < 2, (x-2) is negative
  - Multiplying an inequality by a negative number reverses the direction
  - 3 ≥ 4(x-2)
  - 3 ≥ 4x-8
  - 11 ≥ 4x
  - x ≤ 11/4
  - So for this case: x < 2 and x ≤ 11/4, which simplifies to x < 2 (since 11/4 < 2)

- Combining both cases: x < 2 or x ≥ 11/4
- None of the answers match this exactly, but looking closer at the options, let's verify:
  - D states: x > 2 and x ≤ 11/4
  - Since x > 2 implies x > 11/4, but we also need x ≤ 11/4, this creates an impossible condition
  - The inequality should be "or" not "and"
  - D is incorrect, but the closest answer would be x > 2 and x ≥ 11/4 (which simplifies to x ≥ 11/4)

- Option D should be the answer, but there appears to be a typo in the question. The correct solution is x ≥ 11/4.

## **FRENSHAM HIGH**
### MCQ: Factor of polynomial
Which of the following is NOT a factor of the polynomial P(x) = x³ - x² - 8x + 12 ?
- (A) (x + 3)
- (B) (x + 3)²
- (C) (x - 2)
- (D) (x - 2)²

#### Solution:
- To check if (x + 3) is a factor, we evaluate P(-3):
  - P(-3) = (-3)³ - (-3)² - 8(-3) + 12
  - P(-3) = -27 - 9 + 24 + 12
  - P(-3) = 0
  - So (x + 3) is a factor

- To check if (x + 3)² is a factor, we need to check if (x + 3) is a repeated factor:
  - We need to evaluate P'(-3) where P'(x) is the derivative of P(x)
  - P'(x) = 3x² - 2x - 8
  - P'(-3) = 3(-3)² - 2(-3) - 8
  - P'(-3) = 3(9) + 6 - 8
  - P'(-3) = 27 + 6 - 8 = 25
  - P'(-3) ≠ 0, so (x + 3) is not a repeated factor
  - Therefore (x + 3)² is NOT a factor

- To check if (x - 2) is a factor, we evaluate P(2):
  - P(2) = (2)³ - (2)² - 8(2) + 12
  - P(2) = 8 - 4 - 16 + 12
  - P(2) = 0
  - So (x - 2) is a factor

- To check if (x - 2)² is a factor, we evaluate P'(2):
  - P'(2) = 3(2)² - 2(2) - 8
  - P'(2) = 3(4) - 4 - 8
  - P'(2) = 12 - 4 - 8 = 0
  - Since P'(2) = 0, (x - 2) is a repeated root
  - So (x - 2)² is a factor

- Therefore, option (B) (x + 3)² is NOT a factor of the polynomial

### Question 11(c): Polynomial roots
Consider the polynomial P(x) = x³ - 2px + q where p and q are constants and p ≠ 0.
It is given that α, β and α + β are roots of the equation P(x) = 0.

#### Part (i): Prove that α = -β
- Let's call the three roots α, β, and γ, where γ = α + β
- For a cubic polynomial with constant term q, the product of roots is -q
- So α · β · γ = -q
- Substituting γ = α + β:
  - α · β · (α + β) = -q
  - α²β + αβ² = -q

- For a polynomial of form x³ + 0x² - 2px + q:
  - The sum of roots is 0 (since coefficient of x² is 0)
  - So α + β + γ = 0
  - Substituting γ = α + β:
  - α + β + (α + β) = 0
  - 2α + 2β = 0
  - 2(α + β) = 0
  - α + β = 0
  - Therefore, α = -β which is what we needed to prove

#### Part (ii): Find all the roots of P(x) = 0 in terms of p
- We've shown α = -β, so the roots are α, -α, and γ = α + (-α) = 0
- One root is 0
- Let's find the other roots using the remaining conditions

- Since one root is 0, (x) is a factor of P(x)
- So P(x) = x(x² - 2p)
- The other two roots come from solving x² - 2p = 0
- x² = 2p
- x = ±√(2p)

- Therefore, the three roots of P(x) = 0 are:
  - 0, √(2p), and -√(2p)

## **GIRRAWEEN HIGH 2024 EXT 1**
### MCQ: Multiplicity of root
What is the multiplicity of the root x = 1 of the equation f(x) = 3x⁵ - 5x⁴ + 5x - 3?
- A. 1
- B. 2
- C. 3
- D. 4

#### Solution:
- To determine multiplicity, we need to check:
  - If f(1) = 0, then x = 1 is a root (multiplicity at least 1)
  - If f'(1) = 0, then the multiplicity is at least 2
  - If f''(1) = 0, then the multiplicity is at least 3, etc.

- Check if x = 1 is a root by evaluating f(1):
  - f(1) = 3(1)⁵ - 5(1)⁴ + 5(1) - 3
  - f(1) = 3 - 5 + 5 - 3 = 0
  - Since f(1) = 0, x = 1 is a root (multiplicity at least 1)

- Take the derivative: f'(x) = 15x⁴ - 20x³ + 5
  - f'(1) = 15(1)⁴ - 20(1)³ + 5
  - f'(1) = 15 - 20 + 5 = 0
  - Since f'(1) = 0, the multiplicity is at least 2

- Take the second derivative: f''(x) = 60x³ - 60x²
  - f''(1) = 60(1)³ - 60(1)² = 60 - 60 = 0
  - Since f''(1) = 0, the multiplicity is at least 3

- Take the third derivative: f'''(x) = 180x² - 120x
  - f'''(1) = 180(1)² - 120(1) = 180 - 120 = 60 ≠ 0
  - Since f'''(1) ≠ 0, the multiplicity is exactly 3

- Therefore, option C. 3 is correct

### MCQ: Expression for polynomial
The polynomial f(x) = 2x² + kx + 4 can be expressed as f(x) = (x - 2)g(x) + 6.
Which of the following is the correct expression for g(x)?
- A. 2x - 1
- B. 2x + 1
- C. 2x - 3
- D. 2x + 3

#### Solution:
- Using polynomial division or the remainder theorem:
  - When dividing f(x) by (x - 2), the remainder is f(2) = 2(2)² + k(2) + 4 = 8 + 2k + 4 = 12 + 2k
  - We're told the remainder is 6, so:
  - 12 + 2k = 6
  - 2k = -6
  - k = -3

- Now we have f(x) = 2x² - 3x + 4
- We can use polynomial long division to find g(x):
  - When dividing 2x² - 3x + 4 by (x - 2):
  - First term of quotient: 2x² ÷ x = 2x
  - Multiply: 2x(x - 2) = 2x² - 4x
  - Subtract: (2x² - 3x + 4) - (2x² - 4x) = x + 4
  - Next term of quotient: x ÷ x = 1
  - Multiply: 1(x - 2) = x - 2
  - Subtract: (x + 4) - (x - 2) = 6
  - So g(x) = 2x + 1

- Therefore, option B. 2x + 1 is correct

### Question 11(a): Solve inequality
Solve 1/(2x-1) > 0

#### Solution:
- For a fraction to be positive, either both numerator and denominator are positive, or both are negative
- Since the numerator is 1 (which is always positive), the denominator must be positive
- So 2x - 1 > 0
- 2x > 1
- x > 1/2

- Remember to check the domain: 2x - 1 ≠ 0, so x ≠ 1/2
- Therefore, the solution is x > 1/2

### Question 11(b): Find roots of polynomial
The polynomial 4x³ - 12x² + 5x + 6 = 0 has roots α, β and γ.
Find α, β and γ given that one of the roots is the sum of the other two.

#### Solution:
- Let's say γ = α + β
- For a cubic equation ax³ + bx² + cx + d = 0:
  - Sum of roots = -b/a
  - Sum of products of roots taken two at a time = c/a
  - Product of roots = -d/a

- In our equation 4x³ - 12x² + 5x + 6 = 0:
  - a = 4, b = -12, c = 5, d = 6
  - Sum of roots: α + β + γ = -b/a = -(-12)/4 = 3
  - Sum of products: αβ + αγ + βγ = c/a = 5/4
  - Product of roots: αβγ = -d/a = -6/4 = -3/2

- Substituting γ = α + β:
  - α + β + (α + β) = 3
  - 2(α + β) = 3
  - α + β = 3/2

- Using the product condition:
  - αβ(α + β) = -3/2
  - αβ(3/2) = -3/2
  - αβ = -1

- Now we have:
  - α + β = 3/2
  - αβ = -1

- These are the Vieta formulas for a quadratic equation x² - (3/2)x - 1 = 0
- Using the quadratic formula:
  - x = (3/2 ± √((3/2)² - 4(-1)))/2
  - x = (3/2 ± √(9/4 + 4))/2
  - x = (3/2 ± √(9/4 + 16/4))/2
  - x = (3/2 ± √(25/4))/2
  - x = (3/2 ± 5/2)/2
  - x = 3/4 ± 5/4
  - x = 2 or x = -1/2

- So α = 2 and β = -1/2
- And γ = α + β = 2 + (-1/2) = 3/2

- Therefore, the three roots are: 2, -1/2, and 3/2
