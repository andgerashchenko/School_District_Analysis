# School_District_Analysis

## Overview of the district analysis
After the academic dishonesty has been revealed, the previous analysis could be inaccurate. In order to exclude possible mistaken outputs, the following analysis performed.

## Result
  - Comparing district summary of both previous and new analysis, insignificant difference have revealed. As we can see from attached image, after removing 9th grade of Thomas High School almost all score indicators decreased. 
![district _compare](https://user-images.githubusercontent.com/79814533/143719551-4b3d559b-495e-481d-933f-9e7a3735eb85.png)

  - The same picture with school summary output. All averages and percentages of Thomas High School slightly decreased. Other schools' indicators remain the same.
![school_summery_compare](https://user-images.githubusercontent.com/79814533/143719581-0611d2ee-ca20-4dc8-9c86-51383c060cdd.png)

  - In order to sort schools by its overall passing scores, the following code used: 'top_schools = per_school_summary_df.sort_values(["% Overall Passing"], ascending=False)'. Form output image we can see that Thomas High School remain on the same position, relatively to other schools.
![top5_schools](https://user-images.githubusercontent.com/79814533/143719708-b9d33d6d-618c-4d69-a68a-c13df2a294c9.png)
Therefore we can assume that removing 9th grade scores insignificantlyu affected Thomas High School's prefomance.
  - Here below other comparisons of the outputs before and after removing 9th grade:
      - Math and reading scores by grade. The only difference is replacing 9th grade Thomas High School scores with NaN value. All other scores stayed unaltered.
![math_scores](https://user-images.githubusercontent.com/79814533/143719716-14edb07a-3d52-4aed-a87e-b51c4608996b.png)
![reading_scores](https://user-images.githubusercontent.com/79814533/143719742-91f06194-10de-4b69-bc31-26364d9963ff.png)

      - Scores by school spending didn't change at all 
![spending](https://user-images.githubusercontent.com/79814533/143719750-835add55-957a-435c-8b42-fea23fb486bf.png)

      - Scores by school size didn't change also 
![school_size](https://user-images.githubusercontent.com/79814533/143719763-f62b7a67-c762-4227-99e1-6e9bc7a81365.png)

      - Scores by school type also wasn't affected by removing 9th grade 
![school_type](https://user-images.githubusercontent.com/79814533/143719784-188b15fb-6eec-4277-a00b-a59c5675dd03.png)


## Summary
Considering all conclusions above, we can summarize that replacing 9th grade Thomas High School scores with NaN value give us more prescise results, however this alteration didn't affect any outputs, which the school board could use for future desicions. 
