# Overview of VBA Refactor Coding

The purpose of the VBA Refactor project was to streamline the stock analysis code used to analyze stock volumn and return for multiple years. Another purpose of refactoring the VBA code was to see if a code with less commands would result in faster calculation.

  ## Results of Analysis
  
 The refactored code for the stock analysis resulted in a leaner code, reducing the annual stock anlysis code by combining the two steps used in the annual stock analysis code into one. The measured time between running the refactored code was approximately .01 seconds differnce, with the refactored code running at .76 seconds vs. the .75 seconds for the original code.
  
  ## Summary
  
  There were two purposes in refactoring the stock analysis code. The first purpose was to code with fewer lines to reach the same results as the non-refactored code, which it did. The second purpose of the refactor was to potentially have code that would run faster than the original (with the logic that fewer lines of code would result in a faster calculation time). While not shown to be the case in the instance of the sample size of stocks being analyzed at this time, it is possible that the shorter refactored code would run faster on a larger data set than the original. 
