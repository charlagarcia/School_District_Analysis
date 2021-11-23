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
#write about how district summary changed

**Original District Summary Analysis:**
![Pic 1](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/District%20summary%20original.png)

**Recalculated District Summary Analysis:**
![Pic 2](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/District%20summary%20updated.png)

### How was the School Summary affected?
#write about how school summary changed

**Original School Summary Analysis:**
![Pic 3](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/School%20summary%20original.png)

**Recalculated School Summary Analysis:**
![Pic 4](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/School%20summary%20updated.png)

### How did replacing the 9th graders' math and reading scores affect Thomas High School's performance relative to other schools?
Replacing the 9th graders' math and reading scores actually had very little effect on the overall percentages.  In fact, as it was less than one percent difference, it didn't change THS's ranking at all.  They remain in the #2 position.

**Original Top Five chart:**
![Pic 5](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/Top%205%20schools%20original.png)

**Recalculated Top Five chart:**
![Pic 6](https://github.com/charlagarcia/School_District_Analysis/blob/main/Resources/Top%205%20schools%20updated.png)

### How did replacing the 9th grade scores affect the following:
- Math and reading scores by grade
  - #write analysis
  - 
  - **Original Math & Reading chart by grade:**
  - ![Pic 7](   )
  - **Recalculated Math & Reading chart by grade:**
  - ![Pic 8](  )
- Scores by school spending
  - #write analysis
  - **Original chart of scores by school spending:**
  - ![Pic9](  )
  - **Recalculated chart of scores by school spending:**
  - ![Pic 10](  )
- Scores by school size
    - #write analysis
    - **Original chart of scores by school size:**
    - ![Pic 11](   )
    - **Recalculated chart of scores by school size:**
    - ![Pic 12](   )
- Scores by school type
    - #write analysis
    - **Original chart of scores by school type:**
    - ![Pic 13](  )
    - **Recalculated chart of scores by school type:**
    - ![Pic 14](  )

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the 9th grade at THS have been replaced by NaNs.
    1. 
    2. 
    3. 
    4. 
