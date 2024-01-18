# QuadraticFunction
Creates a java class for the purpose of creating and solving a Quadratic Function


 Write a class, QuadraticFunction, as follows:
 *   - declare fields a, b, and c, type double, to represent the coefficients of a quadratic equation
 *   - constructors;
 *       - no-args constructor to create a QF of the form y = x^2
 *       - 3-args constructor to create a QF with any given coefficients
 *   - accessor method for each field
 *   - findY method to evaluate the quadratic for a given value of x
 *   - findD method to calculate the discriminant of the quadratic
 *   - evaluateD method to return "one real solution", "two real solutions" or "no real solutions"
 *     based on the value of the discriminant (USE findD method)
 *   - toString method to return the "description" of the QF, eg... y = 4.1x^2 + -3.9x + 10.1
 *         when:
 *           a = 4.1
 *           b = -3.9
 *           c = 10.1
 *     IF you can address the  + - as noted with the coefficient, b, ALL THE BETTER!  :)
 *   - findIntercepts method to RETURN the solutions to the quadratic as a 2-element array 
 *     of type double, or null
 *       if 1 real,  9.1   9.1
 *       if 2 real,  -3.1  5.1
 *       if no real, return null
 *     
