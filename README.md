# School_District_Analysis.

## Main Purpose

The school board has notified that data base shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. 

- We replace the math and reading scores for Thomas High School while keeping the rest of the data intact. 
- Generate charts so information it's clearer.
- Analyze the affectations that Thomas High School could suffer after data review. 

## Results

### How is the district summary affected?

- "Average Math Score" was affected 0.1% since we omit 9th grade's score
- "% Passing Math" decreased 0.2% 
- "% Passing Reading" is affected by 0.01% 
- "% Overall Passing" decreased 0.3%.

Before replace the math and reading scores of 9th graders:
![Before1](https://user-images.githubusercontent.com/96633294/151096531-d873be31-1163-443c-abb3-c7d832f0804c.png)

After replace the math and reading scores of 9th graders:
![After1](https://user-images.githubusercontent.com/96633294/151096569-e3d4750b-fe94-435b-8595-c5dd90290097.png)



## How is the school summary affected?

*Thomas High School Averages change*

- "Average Math Score" value decreases by -0.067
- "Average Reading Score" increased by +0.047 
- "% Passing Math" decreased 26.3% 
- "% Passing Reading" decreased 27.6% 
- "% Overall Passing" decreases 0.3% 
- Of course rates will be reduced since we are taking off some elements. It appears to be an important quantity but after all it could be normal to see this decrease. 

Before replace the math and reading scores of 9th graders:
![PassingpercentBefore](https://user-images.githubusercontent.com/96633294/151097388-0c62b320-e866-4d33-b211-3f71b87dfd3e.png)

After replace the math and reading scores of 9th graders:
![PassingpercentAfter](https://user-images.githubusercontent.com/96633294/151097409-1df49ba2-e723-42bc-955c-e553af820f62.png)


## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

If we check images we can notice Thomas High School ranking it's different with and without taking in consideration math & reading 9th graders. 

2nd place before replacing with NaN the math and reading scores of 9th graders:
![RankingBefore](https://user-images.githubusercontent.com/96633294/151098068-345a5ac1-a792-452a-b4f4-afe842f3b3c9.png)

8th place after replacing with NaN the math and reading scores of 9th graders:
![RankingAfter](https://user-images.githubusercontent.com/96633294/151098229-72c707aa-4f97-42e2-9e3d-8e3bdb333494.png)


## How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade
- Since we delet 9th grade it simply show: NaN



Reading

![ScorebyGrade](https://user-images.githubusercontent.com/96633294/151098540-29fb9d0b-9c4d-4d96-bb2b-02162e8da6ab.png)

Math

![ScorebyGradeMath](https://user-images.githubusercontent.com/96633294/151098762-ae54ebf5-0cef-44dc-86c3-b98ca33fca4b.png)


### Scores by school spending

- Since we just take off scores for an specific grade it doesn't affect spending


### Scores by school size

- Size was not affected by our changes.


### Scores by school type

- Same as points before it was not affected

## Summary

After all the analysis and taking 9th grades off, we can notice THS has decrease several places into the school ranking, also "Average Math Score", "% Passing Math", "% Passing Reading" and "% Overall Passing" were affected. It could be part of the deshonesty showed or just because of taking off several grades. 

With this, school board can look foward to adjust new rules and delimitations to get more precise scores and also consequences if dishonesty in grades responsible.  
