# Python_School_District_Analysis

## Overview

In the Python school district analysis challenge, I was tasked with replacing the Thomas High School 9th grade reading & math values with NaN values. The second part of the challenge was to rerun all of the analysis and provide a detailed summary of how the overall and individual analysis' changed.

## Results

- How is the district summary affected?

Passing reading %, passing math %, and the overall passing % all went down by ~1% See the examples:

Old: https://github.com/jasonatoledo/Python_School_District_Analysis/blob/master/Resources/Old_District_Summary.png

New: https://github.com/jasonatoledo/Python_School_District_Analysis/blob/master/Resources/New_District_Summary.png

- How is the school summary affected?

The biggest change was the passing rate of Thomas High School dropping from ~90.94% to only ~65.08%. The passing math dropped a whopping ~27% and reading dropped ~14%. It looks like the freshman made a big difference.

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

THomas High School was formerly ranked as the #2 overall school then dropped to #8 overall with the grade changes.

- How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade
  
  The 9th grade math score is showing NaN but my 9th grade reading score for thomas is still showing 83.6 for some reason. I restarted the kernel and checked all of the code and the numbers changed for reading and overall scores so not sure why it is not showing up as NaN.
 
  - Scores by school spending
  
  The school spending & bucket that Thomas High School is in is unaffected but as with the school summary, the overall passing, reading, and math scores are down in overall passing. As for the school spending summary, Thomas dropped the $630-644 bucket from 63% to 56% overall passing and dropped math by 6% and reading by 3% compared to the original spending summary.
 
  - Scores by school size
  
  Because of the changes, Thomas High School affects the "Medium" size schools that are between 1000-2000 students. Overall passing is down 6%, from 91% to 85%. % Passing reading is down from 94% to 88%, and % passing reading is down 97% to 94%.
 
  - Scores by school type
  
  Since Thomas is in the Charter category, District schools are unaffected. Charter %passing math went from 94% to 90%, %passing reading went from 97% to 95%, and %overall passing went from 90% to 87%.
  
  https://github.com/jasonatoledo/Python_School_District_Analysis/blob/master/Resources/Original_Schools_by_type.png  
  
  vs
  
  https://github.com/jasonatoledo/Python_School_District_Analysis/blob/master/Resources/New_Schools_by_type.png
  
  
## Summary

The 4 major changes I noticed after replacing the Thomas High School 9th grade reading and math scores with NaN values are:

1) The overall passing rate for Thomas High School dropped from ~90% to ~65%

2) Thomas High School dropped from the number 2 school in the district to the number 8 school

3) Medium sized schools overall passing rate dropped from 91% to 85%

4) For spending by school, Thomas High School dropped the $630-644 bucket from 63% to 56% overall passing

It is amazing how drastic some of the changes were for only changing 2 values out of all the schools and grade levels.

