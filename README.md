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

## Random Variables

This reference sheet contains information about commonly encountered probability distributions, both discrete and continuous. It includes the random variable's range, probability mass function, probability distribution function, cumulative distribution function, expectation, and variance.

I compiled this sheet while taking CS 70 at UC Berkeley because, you get the gist now, there was no comprehensive reference I could find. I also used it in HKN review sessions, but now it finally has a home.

## Proofs

This guide is an introduction on how to approach proof problems. Instead of simply defining what proofs are or presenting only completed proofs, this note walks the reader through the entire process of writing a proof. Through examples, it teaches how to use various proof techniques to arrive at a solution. Due to historical reasons there are two versions, one that uses examples from linear algebra, and one that doesn't require linear algebra.

I was instructed to write this note by professor Anant Sahai (hence the linear algebra) when I was a TA for CS 70, but the course ended up not using it, so I am making it available here even though it doesn't exactly fit the category of a formula reference sheet.

## Git Guide

This is a guide on some more advanced Git commands once you are familiar with the basics (add, commit). It was meant to onboard new developers for web development in a club I was in, but it has since been removed so I have moved it here.
