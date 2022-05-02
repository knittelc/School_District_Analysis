# School_District_Analysis

## Overview of the school district analysis:
The purpose of this analysis was to look at high-level snapshot of the district's key metrics, per school metrics and report them in an easy to display and understand table format.  Then, return the school data numbers to the school board for their take on the performance outcomes with these in mind:  The Top 5 and bottom 5 performing schools, based on the overall passing rate, the average math and reading score received by students in each grade level at each school, and school performance based on the budget per student, school size, and type of school.  

*After asking for this analysis, the school board was notified that tampered scores were reported for Thomas High School's entire ninth grade student population (461 students).  These data were subsequently removed.  Both analyses are reported here; with sepecial atttention paid to how the data removal affected the overall district.*

### Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- How is the district summary affected?
    Based on the results below, Fig. 1 by removing the ninth grade class at Thomas High School, the following metrics were changed:  Average Math Score decreased by 1.0 tenths, Percentage of people passing math decreased by 2.0 tenths a percent, Percentage of people passing reading decreased by 1.0 tenths of a percentage, and the largest change in metrics are shown in Overall passing percentage which decreased by 3.0 tenths of a percentage.  It should be noted that Average Reading score did not change.
    
![District Summary 1](https://user-images.githubusercontent.com/102183530/166153032-5df61757-6d3b-4231-992e-5fd1122c90c8.png)

###### Figure 1. District Summary initial analysis with all the given data.

![District Summary 2](https://user-images.githubusercontent.com/102183530/166153069-741e62d8-fcec-4692-b7a9-e7d545d08fac.png)

###### Figure 2. District Summary with Ninth grade results from Thomas High School removed from the data.

- How is the school summary affected?
    Based on the results below, Fig. 3 includes the ninth grade class, where Fig. 4 is without the scores from the Ninth grade Thomas High School students.  The numbers increased significantly in each Percentage category: Passing Math (26.36 points gained), Passing Reading (27.65 points gained), and Overall (25.88 points gained).  These results for Thomas High School put it in the top five best performing school based on overall passing percentage.
    
![Top 5 2](https://user-images.githubusercontent.com/102183530/166166245-01db6998-e460-4391-abba-750f6db3f26d.png)

###### Figure 3. School summary including all students

![Top 5 1](https://user-images.githubusercontent.com/102183530/166153864-070b2c4c-ce36-46fb-89c8-5e778d722e29.png)

###### Figure 4. School summary without Ninth grade students from Thomas High School

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    As noted in the above Figures 3 and 4, Thomas High School rises to the number two(2) overall spot.
    
- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade:
        The biggest affect of removing an entire grade of a school is that there is no data to compare.  So the entire 9th grade for Thomas High School           returns a "NAN" value.

    - Scores by school spending:
        The change is minor due to the student count remaining the same, and only tenths of a percentage and average change for any of the metrics; as we       used rounding to the nearest percentage.  None of these scores reflect any changes    
    
    ![scores by school spending](https://user-images.githubusercontent.com/102183530/166172775-8cdee7fb-8498-4a81-b201-95e0242b9eb1.png)
 
        
    - Scores by school size
        This change is also not showing as the small subset of student scores removed, do not impact these final numbers
 
    ![scores by school size](https://user-images.githubusercontent.com/102183530/166173272-b4c579f4-9878-4745-8fc3-493e215b737c.png)

    - Scores by school type
        As Thomas High School is listed as a Charter school, these would have been the only scores affected.  However, due to the small student size,           these numbers are the same as the original.
        
    ![scores by school type](https://user-images.githubusercontent.com/102183530/166173433-d8840487-835d-4118-8721-0b85d268cac1.png)


### Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Changes in analytics are most heavily seen in just the Thomas High metrics.  There are very minor changes (within hundredths of scores) for both reading and math averages.  There are major shifts upward in percentage of passing students in math and reading, thus also affecting the overall passing percentages.  It appears the tampered with grades were significantly pulling down the scores and ranking Thomas High in the bottom of the entire district; rather than the second best ranked school according to the metric: Overall Percent Passing, which is what was used to rank the schools in a stacked ranking.

A note:  these instructions did not have us completely drop the students in this analysis, as it was still relevant to the school spening numbers and school size categories.  As the numbers for reading and math were nullified, it shows how high performing the 10th -12th grade were at this specific school.
