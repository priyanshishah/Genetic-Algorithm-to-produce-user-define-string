# Genetic-Alogrithm-to-produce-user-define-string

## Overview 
Implementation of a Genetic Algorithm which aims to produce the user specified target string. 

## Approach
This implementation calculates each candidate's fitness based on the alphabetical distance between the candidate and the target. A candidate is selected as a parent with probabilities proportional to the candidate's fitness. Reproduction is implemented as a single-point crossover between pairs of parents. Mutation is done by randomly assigning new characters with uniform probability.
