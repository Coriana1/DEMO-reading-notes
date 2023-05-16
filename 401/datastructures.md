# Data Structures and Algorithms

1. What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?
  - One of the key factors to consider when choosing a data structure for a specific problem is the time complexity of the operations involved. Time complexity, using Big O notation, offers insights into how the execution time of an operation scales as the size of the data structure increases. By analyzing the time complexity, we can estimate the efficiency of the operations and make informed decisions about the suitability of a data structure for the problem at hand.

2. How can we ensure that we’ll avoid an infinite recursive call stack?
  - Implement proper termination conditions && ensure that recursive function is making progress towards the base case.
      - **Base case, recursive case, check inputs, test & debug, ad tail recursion (if needed)**