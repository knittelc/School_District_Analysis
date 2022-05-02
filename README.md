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
    Based on the results below, Fig. 3 includes the ninth grade class, where Fig. 4 is without the scores from the Ninth grade Thomas High School students.  The numbers drop significantly in each Percentage category: Passing Math (26.36 points lost), Passing Reading (27.65 points lost), and Overall (25.88 points lost).  These results for Thomas High School drops it from the top five best performing school based on overall passing percentage, to the bottom five, and lowest performing schools.

![Top 5 1](https://user-images.githubusercontent.com/102183530/166153864-070b2c4c-ce36-46fb-89c8-5e778d722e29.png)

###### Figure 3. School summary including all students

![Top 5 2](https://user-images.githubusercontent.com/102183530/166166245-01db6998-e460-4391-abba-750f6db3f26d.png)

###### Figure 4. School summary without Ninth grade students from Thomas High School

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    As noted in the above Figures 3 and 4, Thomas High School drops from the number two(2) overall spot, to the bottom five (5).
    
- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade:
        The biggest affect of removing an entire grade of a school is that there is no data to compare.  So the entire 9th grade for Thomas High School returns a "NAN" value.

    - Scores by school spending
    - Scores by school size
    - Scores by school type

### Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
