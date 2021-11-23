# School_District_Analysis

## Overview

### Purpose:
Maria asked us to present the following:
- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics:
    - Top 5 and bottom 5 performing schools, based on the overall passing rate
    - The average math score received by students in each grade level at each school
    - The average reading score received by students in each grade level at each school
    - School performance based on the budget per student
    - School performance based on the school size 
    - School performance based on the type of school

After the data was reviewed by the school board, they notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once those were replaced, we repeated the school district analysis with the new scores.

### Objectives:
- Open Jupyter Notebook files from local directories using a development environment.
- Read an external CSV file into a DataFrame.
- Format a DataFrame column.
- Determine data types of row values in a DataFrame.
- Retrieve data from specific columns of a DataFrame.
- Merge, filter, slice, and sort a DataFrame.
- Apply the groupby() function to a DataFrame.
- Use multiple methods to perform a function on a DataFrame.
- Perform mathematical calculations on columns of a DataFrame or Series.

## Results

### How was the District Summary affected?
After replacing the scores for math and reading at Thomas High School, the district summary was only minimally changed.  The percentages for passing math, passing reading, and the overall passing percentage were all lowered by about a quarter of a percent.

**Original District Summary Analysis:**
![Pic 1](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/District%20summary%20original.png)

**Recalculated District Summary Analysis:**
![Pic 2](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/District%20summary%20updated.png)

### How was the School Summary affected?
The percent of students passing at Thomas High School were also only minimally affected.  The percentages for students who passed math, passed reading, and passed overall were all lowered by about a quarter of a percent.

**Original School Summary Analysis:**
![Pic 3](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/THS%20School%20Summary%20Original.png)

**Recalculated School Summary Analysis:**
![Pic 4](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/THS%20School%20Summary%20Updated.png)

### How did replacing the 9th graders' math and reading scores affect Thomas High School's performance relative to other schools?
Replacing the 9th graders' math and reading scores actually had very little effect on the overall percentages.  In fact, as it was less than one percent difference, it didn't change THS's ranking at all.  They remain in the #2 position.

**Original Top Five chart:**
![Pic 5](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/Top%205%20schools%20original.png)

**Recalculated Top Five chart:**
![Pic 6](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/Top%205%20schools%20updated.png)

### How did replacing the 9th grade scores affect the following:
- #### Math and reading scores by grade
    - Replacing the 9th grade scores for Thomas High School didn't affect overall grades at all.  Since the difference was less than half a percent and grades are rounded to the nearest whole number percent, the difference would only even be seen if percents are rounded to the hundredths place.
  
    **Original Math & Reading chart by grade:**
    ![Pic 7](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/math%20and%20reading%20original.png)
    **Recalculated Math & Reading chart by grade:**
    ![Pic 8](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/math%20and%20reading%20updated.png)
 
- #### Scores by school spending
    - Replacing the 9th graders' math and reading scores at Thomas High School did not affect the scores based on spending ranges per student at all.
    **Original chart of scores by school spending:**
    ![Pic9](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/Spending%20summary%20original.png)
    **Recalculated chart of scores by school spending:**
    ![Pic 10](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/spending%20summary%20updated.png)
- #### Scores by school size
    - Replacing the 9th graders' math and reading scores at Thomas High School did not affect the scores based on school size at all.
    **Original chart of scores by school size:**
    ![Pic 11](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/school%20size%20original.png)
    **Recalculated chart of scores by school size:**
    ![Pic 12](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/school%20size%20updated.png)
- #### Scores by school type
    - Replacing the 9th graders' math and reading scores at Thomas High School did not affect the scores based on school type at all.
    **Original chart of scores by school type:**
    ![Pic 13](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/school%20type%20original.png)
    **Recalculated chart of scores by school type:**
    ![Pic 14](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/school%20type%20updated.png)

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the 9th grade at THS have been replaced by NaNs.
    1. 
    2. 
    3. 
    4. 
