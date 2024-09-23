# Shamir-Secret-Sharing-Algorithm-

This repository contains a JavaScript implementation of a simplified version of Shamir's Secret Sharing algorithm. The main focus of this implementation is to decode polynomial roots provided in a JSON format and calculate the constant term of the polynomial.

## Description

Shamir's Secret Sharing is a cryptographic algorithm that allows a secret to be divided into parts, giving each participant a unique part. To reconstruct the secret, a certain minimum number of parts (roots) are required. This implementation reads roots from a JSON file, decodes them based on their specified bases, and uses Lagrange interpolation to find the constant term of the polynomial.

## Files

- `findConstantTerm.js`: The main JavaScript file that contains the logic to decode the roots and calculate the constant term.
- `input.json`: Example JSON input file containing the roots with their bases and values.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/NitGit24/Shamir-Secret-Sharing-Algorithm.git
   cd Shamir-Secret-Sharing-Algorithm
