# Lift and People


All math nerds, here is a problem, lift has 10 floors... 0, 2, 4, 6, 8 are pressed. What is the probability of this happening? Considering all permutations and combinations of numbers. 1/2^10 I guess. So around 0.1%. Pretty straightforward school maths. via [https://x.com/DhawleDhananjay/status/1826264204766015572](https://x.com/DhawleDhananjay/status/1826264204766015572)

### Assumptions

1. There are 10 floors 1-10 excluding the ground (0) floor
2. The even floors are 2, 4, 6, 8, 10
3. The number of people is 5 which is the same as the number of even floors

### Problem Restatement
We need to calculate the probability that each of the floors 2, 4, 6, 8, and 10 is selected exactly once by 5 people, with one person per floor.

### Solution

1. **Total Possible Outcomes:**
   Each of the 5 people can choose any of the 10 floors, so the total number of possible outcomes is:
   $10^5$

3. **Favorable Outcomes:**
   For the favorable outcomes, we need all 5 people to select the specific floors 2, 4, 6, 8, and 10, with each floor being chosen exactly once. Since we are assigning 5 distinct people to 5 distinct floors, the number of favorable outcomes is simply the number of permutations of 5 items:
   $5! = 120$

4. **Probability Calculation:**
   The probability $P$ is the ratio of favorable outcomes to the total possible outcomes:

   $$P = \frac{5!}{10^5} = \frac{120}{100000} = \frac{3}{2500} \approx 0.0012$$

### Final Answer
The probability that the floors 2, 4, 6, 8, and 10 are selected with exactly one person on each floor is $\frac{3}{2500}$, or approximately 0.0012 = 0.12%.

### Extras

1. The fact that all floors are even doesn't make it more special than any other selection of 5 floors for e.g. 1, 3, 4, 6, 9
2. The problem gets complicated quite quickly if the number of people is greater than the number of floors. See: [Stirling numbers of the second kind - Wikipedia](https://en.wikipedia.org/wiki/Stirling_numbers_of_the_second_kind)
