# School_District_Analysis

## Overview of the district analysis
After the academic dishonesty has been revealed, the previous analysis could be inaccurate. In order to exclude possible mistaken outputs, the following analysis performed.

## Result
  - Comparing district summary of both previous and new analysis, insignificant difference have revealed. As we can see from attached image, after removing 9th grade of Thomas High School almost all score indicators decreased. (https://github.com/andgerashchenko/School_District_Analysis/blob/00a0d274fd4e1723cdb9c6e707a2f044242f0d31/Resources/district%20_compare.png) 
  - The same picture with school summary output. All averages and percentages of Thomas High School slightly decreased. Other schools' indicators remain the same.(https://github.com/andgerashchenko/School_District_Analysis/blob/bf130f82a580ba22003e81e179a0eb911a03c095/Resources/school_summery_compare.png)
  - In order to sort schools by its overall passing scores, the following code used: 'top_schools = per_school_summary_df.sort_values(["% Overall Passing"], ascending=False)'. Form output image we can see that Thomas High School remain on the same position, relatively to other schools.(https://github.com/andgerashchenko/School_District_Analysis/blob/fb291e50b4928bef2dfa8c9badcb6279de77785c/Resources/top5_schools.png). Therefore we can assume that removing 9th grade scores insignificantlyu affected Thomas High School's prefomance.
  - Here below other comparisons of the outputs before and after removing 9th grade:
      - Math and reading scores by grade. The only difference is replacing 9th grade Thomas High School scores with NaN value. All other scores stayed unaltered.(https://github.com/andgerashchenko/School_District_Analysis/blob/e6f2d5baa2582cb75e604ba323462a41d0940044/Resources/math_scores.png),(https://github.com/andgerashchenko/School_District_Analysis/blob/e6f2d5baa2582cb75e604ba323462a41d0940044/Resources/reading_scores.png)
      - Scores by school spending didn't change at all ( https://github.com/andgerashchenko/School_District_Analysis/blob/9de330cfb146681422881d608a785e026e7d29e1/Resources/spending.png)
      - Scores by school size didn't change also (https://github.com/andgerashchenko/School_District_Analysis/blob/550bd0561517e4e1a10585a14a89186014fbfe0b/Resources/school_size.png)
      - Scores by school type also wasn't affected by removing 9th grade (https://github.com/andgerashchenko/School_District_Analysis/blob/bf800111fe02197d57b217ae261c2117cf07dc00/Resources/school_type.png)

## Summary
Considering all conclusions above, we can summarize that replacing 9th grade Thomas High School scores with NaN value give us more prescise results, however this alteration didn't affect any outputs, which the school board could use for future desicions. 
