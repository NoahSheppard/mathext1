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

### Question 12(d): When the polynomial P(x) is divided by (x - 1)(x + 4), the quotient is Q(x) and the remainder is R(x). The remainder R
