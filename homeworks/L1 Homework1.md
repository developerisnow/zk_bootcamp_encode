### 1. Modular Arithmetic with Set \( S = \{0,1,2,3,4,5,6\} \)

#### a) \( 4 + 4 \)

4+4 = 8
count(S) =7 
8/7 = mod 1
4+4 equiv 1

#### b) \( 3 \times 5 \)
count(S) = 7
3 * 5 = 15
equivalent to mod 1

#### c) Inverse of 3
count(S) = 7
What is 3 * x = equiv 1 mod 7
It's 5, because on previous step we already explain about 3 * 5 = 15
### 2. Is \( S \) with '+' a Group?

To see if \( S \) and '+' make a group, we need to check a few things:

- **Do we stay in the set?** When we add any two numbers in \( S \), do we get another number that's also in \( S \)? Yes, because if we go over 6, we just start from 0 again (like a clock that goes up to 6 instead of 12).
- **Does the order we add things matter?** Yes, in addition, it doesn't matter which order we add things; we always get the same result.
- **Is there a zero?** Yes, 0 is special because if we add it to any number, that number doesn't change.
- **Can we undo addition?** Yes, for every number in \( S \), there's another number that, when added, gives us our special zero.

So, yes, \( S \) with '+' is a group because it passes all these checks.

### 3. What is \( -13 \mod 5 \)?

When we do \( -13 \mod 5 \), we're asking, "If we divide -13 by 5, what's the remainder?" But since -13 is negative, we think, "How many do we need to add to get to a number that 5 can divide?" 

If we add 15 to -13, we get 2 (because -13 + 15 = 2), and 2 is a number that fits nicely after we've divided by 5. So, \( -13 \mod 5 \) is 2. It's like if you owe someone 13 dollars but only pay in 5-dollar bills, you'd need to give them 3 bills (15 dollars) and get 2 dollars back.

### 4. Polynomials: Positive Root and Degree

#### Positive Root

For the polynomial \( x^3 - x^2 + 4x - 12 \), we want to find a positive number that makes the polynomial equal to zero. If we try \( x = 2 \):

\[ (2)^3 - (2)^2 + 4(2) - 12 = 8 - 4 + 8 - 12 = 0 \]

So, \( x = 2 \) works! It's like guessing a number that solves a puzzle, and 2 is the number that completes our puzzle.

#### Degree of the Polynomial

The degree of a polynomial is just the biggest exponent we see. For \( x^3 - x^2 + 4x - 12 \), the biggest exponent is 3 (because of \( x^3 \)). So, the degree is 3. It tells us the polynomial's "size" or how complicated it is, with 3 meaning it's a bit more complex than something like \( x^2 \) or \( x \).

## Questions
1. Any ZKP with blockchain?
	1. Auth private
	2. Transactions private
	3. Voting private
2. What is the most important?
	1. proove without share data
3. What use cases do you want to develop?
	1. Tinder
	2. Tinder for Startups and Investors
	3. ZK ML
	4. Education, HealthCare