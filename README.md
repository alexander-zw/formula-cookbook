# The Formula Cookbook

A reference of commonly used mathematical formulas in certain areas.

If you only need to reference formulas, you can view the PDFs located in the root directory. However for your convenience, the source TeX files are included in `src/`.

## Vector Calculus

This reference sheet contains formulas for the derivatives of matrix-vector equations. Derivatives include partial derivatives, gradients, Jacobians, Hessians, and matrix gradients. Formulas include definitions, fixed matrix-vector equations, product rules, and chain rules.

Make sure to check the conventions you use, for example sometimes the Jacobian is transposed.

I compiled these formulas because the most commonly used vector calculus reference, the Matrix Cookbook, contains too many rarely used formulas and confusing notation (writing gradients and Jacobians all as partial derivatives), so it is overkill to use for something like an machine learning class.

I used these formulas for EECS 127 and CS 189 at UC Berkeley. Interestingly, although these formulas are imperative to doing the homework, neither of those classes bother to teach them.

## Asymptotic Analysis

This reference sheet contains summation formulas useful for calculating an algorithm's time or space complexity.

The reason I made this sheet is that although any class that does complexity analysis will mention a few of these formulas, they often are not comprehensive and contain duplicates (1 + 2 + 4 + ... + n is really a substitution of variables from 1 + 2 + 4 + ... + 2^n).

This sheet originated when I was taking CS 61A and CS 61B at UC Berkeley. I then shared them through HKN review sessions, and I thought it was time I put them in a PDF.
