## Introduction

This simple code challenge can be done in any programming language of your choice while you show us the best of your programming skills.  Although it would be wonderful to see a program that will take any input file and produce the output file for any compliant set of inputs, the purpose of this code challenge is really to assess your skills and your ability to logically understand and solve the task at hand.  There will be a discussion of your code to assess your thought process in developing the program and to gauge whether you are a good fit for this internship.

## Title: Partitioned String Sort

**Given**:  
  Any string with sequences of a) digits and b) non-digits that.  
  AND the set of sequences can repeat n number of times.  
  AND either a) or b) sequence can start or end the string.  

**Expected**:  
  Write code that will sort each a) digit or b) non-digit sequence  
  And keep the relative position in the string as in the original string.

**Example**:  
  **input**: 43512abc87241dDfe.  
  **output**: 12345abc12478Ddef.  

  **Analysis**:   
    We have 4 sequences here:

>       1. 43512
>       2. abc
>       3. 87241
>       4. dDfe

We sort each subsequence

>   1. 12345
>   2. abc
>   3. 12478
>   4. Ddef
>

We then reconstruct the string
  12345abc12478Ddef

## Your challenge:

Write a program that will read the input file `input.txt`, partition sort each line according to the partitioned sort method described above, and output the result to an output file `my-outupt.txt`.

**Bonus**:  Use git to create commits as you develop the code including any design or redesign stages you go through developing the code.

