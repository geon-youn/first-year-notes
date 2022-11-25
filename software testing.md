---
alias:
tags: COMPSCI_1JC3
---
# Software Testing
The most important technique for analyzing the quality of a software product. Testing can be used to assess **reliability** and **robustness** (how well it can handle edge cases). 
## Test Case Selection
1. **Blackbox**: Test cases selected to cover the behaviour of the code based on only the *specification of the code*.
2. **Whitebox**: Test cases selected to cover the behaviour of the code based on the *code itself*.
3. **Statistical random**: Test cases selected to measure reliability using an operational profile.
4. **Wild random**: Test cases selected to measure robustness using a uniform random distribution. 
## General Testing Recommendations
- Test the smallest components first (**unit testing**).
- Test all possible paths through and statements in the program (**path coverage** and **statement coverage**).
- Test all types of data combinations including:
	- Cases along the boundaries.
		- At the boundary.
		- Far from the boundary on either side.
		- Close to the boundary on either side.
	- Extreme cases (e.g. very small or very large numbers).
	- Degenerate cases (e.g. an empty file).
	- Erroneous cases (e.g. name of a nonexisting file).
## Limitations
- It is usually impossible to test every possible input and environmental configuration.
- Testing can show *instances of incorrectness* ([[proof by counterexample]]), but it is usually not practical for demonstrating **correctness**.
- Positive testing results are not, by themselves, an indication of software quality.
- The theory of testing leads to many undecidable problems.