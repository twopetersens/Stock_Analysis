# Overview of VBA Refactor Coding

The purpose of the VBA Refactor project was to streamline the stock analysis code by reducing the number of lines needed to calculate the volume and ROR on multiple stocks, across multiple years. By reducing the number of lines of code needed, there was also the expectation that the amount of time needed to calculate volume and ROR would be reduced.


  ## Results of Analysis
  
 The refactored code for the stock analysis resulted in a leaner code, reducing the annual stock anlysis code by combining the two steps used in the annual stock analysis code into one. The measured time between running the refactored code was approximately .05 to.1 seconds differnce, with the refactored code running at .68 seconds vs. the .75 seconds for the original code. The refactored code runs faster than the original code.
  
  ## Summary
  
  
  
There were two purposes in refactoring the stock analysis code. The first purpose was to code with fewer lines to reach the same results as the non-refactored code, which it did. The second purpose of the refactor was to produce code that would run faster than the original (with the logic that fewer lines of code would result in a faster calculation time). As shown, the refactored code runs faster than the original code. This means that the shorter refactored code would run a larger dataset faster than the original code produced. 
