# Boat Manufacturer Profit Simulation using Breakpoint Method and Profit Optimization using Optimise Function

GitHub Pages: https://priauwindu.github.io/Breakpoints-Method-Simulation-for-Boat-Manufacturer/

Performing Profit Simulation using Breakpoint Method and Profit Optimization using Optimise Function given the uncertain demands with unknown data for a hypothetical company named GWS. 

## Introduction

GWS is a company that markets outboard motorboats directly to consumers for recreational use. Recently, they’ve been developing a project they think has a lot of potential: the first mass market boats with electric motors. They haven’t started advertising their new product yet, nor have they organized a presale because they don’t want to lose their first-mover advantage. As a result, GWS has a limited understanding of the size of the market for their new project. They plan to retail their boats for $150,000, but after two years, when competition enters the market and the novelty factor wears off, they’ll have to drop the price to $70,000. They hire a consultant who estimates that at this price point, over the next two years, demand for the new boats will be somewhere between 2,000 and 15,000, with probabilities as in the table below:

Demand	Probability
2,000-5,000	35%
5,001-10,000	40%
10,001-14,000	20%
14,001-15,000	5%

The fixed cost of manufacturing any number of boats is normally distributed, with a mean of $300 million and a standard deviation of $60 million. They estimate that the variable cost to produce one boat will be a minimum of $77 thousand and a maximum of $100 thousand, with a most likely value of $90,000

## Objective

This work covers: 

**1. The simulation of expected total profit over the two year period assuming they produce.** 

- 4,000 boats
- 8,000 boats
- 12,000 boats
- 15,000 boats

including the visualization of: 
- line/ribbon plot depicting the mean profit as well as an 80% and a 95% confidence interval for GWS’ profit if they create between 2000 and 15000 boats, counting by increments of 1000.
- overlapping density plots depicting the distribution of GWS’ profit, assuming they create 2000, 4000, 6000, 8000, 10000, 12000, or 14,000 boats.

Analysis utilized Monte Carlo Simulation to incorporate uncertainty factor for the expected profit for GWS company.

**2. Optimization analysis to determine the number of boats GWS should produce to maximize:**
- Their expected profit
- The 10th percentile of their profit
- The probability that they will earn a profit of at least $50 million

Please note that this repository is intended to document the BU MET AD616 Enterprise Risk Analytics Assignment.

If you find this work/repository useful, you may use or reproduce the code within this repository with proper citation.

Thank you!

Putranegara Riauwindu




