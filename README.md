# Lecture 1: Input to Output

## Understanding Functions:

### Input Set - Domain:
- The domain refers to the set of all possible input values for a function.
- It encompasses the range of values that can be plugged into the function.

### Output - Co-domain:
- The co-domain represents the set of all possible output values for a function.
- It defines the full range of potential results that the function can produce.

## Function Representation:

### Input to Output Mapping:
- In a function, each input value from the domain is mapped to a single output value in the co-domain.
- This mapping is defined by the function's rule or expression.

#### Example:
- Given function: f(x) = x + 3
- If x is the input, then for x = 1, f(1) = 1 + 3 = 4

- **Alternative Representations:**
  - These expressions all represent the same function:
    - f(x) = x + 3
    - f 0 x = x + 3
    - f:x -> x+3

### Computational Science Notation:
- In computational science, a function can be represented as follows:
  - f:{1,...,5} -> {4,...,8} defined by f(x) = x + 3
  - Here, {1,...,5} is the domain, {4,...,8} is the co-domain, and f(x) = x + 3 is the function rule.

## Inverse Functions:

### Conditions for Existence:
- For an inverse function to exist, the original function must be bijective (one-to-one and onto).
- It means that each element in the co-domain has a unique pre-image in the domain.

### Non-Bijective Functions:
- Functions that are not bijective are called singular functions.
- They do not have a well-defined inverse.

### Inverse Function Procedure:
- To find the inverse of a function, you reverse the rule of the original function.
- For example, if the function rule is f(x) = x + 3, the inverse function would be f(x) = x - 3.

### Example:
- Domain numbers: 1, 2, 3, 4, 5
- Co-domain numbers: 4, 5, 6, 7, 8, 9
- Function rule: f(x) = x + 3
- Inverse function: f(x) = x - 3

## Domain Restrictions:

### Singular Functions:
- A singular function is unable to map back to a single element due to multiple outputs for some inputs.
- Example: g(x) = x² is a singular function as it can't map back to a definite element.

### Domain Restriction Procedure:
- Domain restrictions can be applied to limit the inputs of a function.
- It involves adding additional rules to constrain the domain of the function.

#### Example:
- Given function: g:{-2, ..., 2} -> {0,1,4} defined by g(x) = x²
  - Without restriction: Singular function
  - With restriction: Bijective function (no negative numbers in the domain)

## Composite Functions:

### Procedure:
- Composite functions involve applying one function to the output of another.
- Start from the innermost function and work outwards from the input.

### Example:
- Given functions:
  - f(x) = x + 3
  - g(x) = x²
  - h(x) = x^3

#### Example:
- g(3) = 3² = 9
- f(9) = 9 + 3 = 12

- To find gfh(2):
  - h(2) = 2^3 = 8
  - f(8) = 8 + 3 = 11
  - g(12) = 11² = 121

## Revision Questions:

- To find gf(7):
  - f(7) = 7 + 3 = 10
  - g(10) = 10²
  - gf(7) = 100

- To find ff(4):
  - f(4) = 4 + 3 = 7
  - f(7) = 7 + 3 = 10
  - ff(4) = 10

- To find hg(1):
  - g(1) = 1²
  - h(1) = 1^3
  - hg(1) = 1

## Odd/Even Functions:

### Even Functions:
- A function is even if f(a) = f(-a), meaning the output is the same for positive and negative inputs.

#### Example:
- g(x) =  x²
  - g(3) =  3² = 9
  - g(-3) = (-3)² = 9
  - g(x) is even.

### Odd Functions:
- A function is odd if f(a) = -f(-a), meaning it gives opposite signs for positive and negative inputs.

#### Example:
- h(x) = x^3
  - h(3) = 3^3 = 27 
  - h(-3) = (-3)^3 = -27
  - h(x) is odd.
