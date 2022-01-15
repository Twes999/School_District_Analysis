# School_District_Analysis

## Project Overview
A chief data scientist for a city school district has given me the following tasks to help the school board with making decisions regarding the school budgets and priorities.

1. A high-level snapshot of the district's key metrics, presented in a table format.
2. An overview of the key metrics for each school, presented in a table format.
3. Tables presenting each of the following metrics:
      -Top 5 and bottom 5 performing schools, based on the overall passing rate
      -The average math score received by students in each grade level at each school
      -The average reading score received by students in each grade level at each school
      -School performance based on the budget per student
      -School performance based on the school size 
      -School performance based on the type of school.

## Resources
-Data Source: schools_complete.csv, students_complete.csv
-Software; Anaconda 4.11.0 , Jupyter Notebook 6.4.6

## Results
The analysis of the school disctrict shows that:
-The district summary is affected by only a few tenths of a percent. The new disctrict summary passing percentages are down.
    -https://github.com/Twes999/School_District_Analysis/blob/main/Resources/Images/District_Summary_Images/District_Summary.png
    -https://github.com/Twes999/School_District_Analysis/blob/main/Resources/Images/District_Summary_Images/New_District_Summary.png


-The school summary isn't affected. THS stays in second place but has a small increase in % Overall Passing.
    -https://github.com/Twes999/School_District_Analysis/blob/main/Resources/Images/School_Summary_Images/School_Summary.png
    -https://github.com/Twes999/School_District_Analysis/blob/main/Resources/Images/School_Summary_Images/New_school_summary.png
    
    
-Replacing the scores doesn't affect Thomas High Schools performance relative to the other schools. THS is still one of the top performing schools.

-Replacing the ninth-grade scores affects the math and reading scores by grade by giving Thomas High School only three eligible scores for the analysis instead of the four like the other schools. Potentially not as accurate of analysis only being able to use tenth-twelfth grades.
    -https://github.com/Twes999/School_District_Analysis/blob/main/Resources/Images/Ninth_grade_replacement_scores/math_scores_by_grade.png
    -https://github.com/Twes999/School_District_Analysis/blob/main/Resources/Images/Ninth_grade_replacement_scores/new_math_scores_by_grade.png
    -https://github.com/Twes999/School_District_Analysis/blob/main/Resources/Images/Ninth_grade_replacement_scores/reading_scores_by_grade.png
    -https://github.com/Twes999/School_District_Analysis/blob/main/Resources/Images/Ninth_grade_replacement_scores/new_reading_scores_by_grade.png
    
       
-Scores by school spending are not affected at all.
    -https://github.com/Twes999/School_District_Analysis/blob/main/Resources/Images/Ninth_grade_replacement_scores/spending_summary.png

-Scores by school size are not affecred at all.
    -https://github.com/Twes999/School_District_Analysis/blob/main/Resources/Images/Ninth_grade_replacement_scores/size_summary.png
    
-Scores by school type are not affected at all.
    -https://github.com/Twes999/School_District_Analysis/blob/main/Resources/Images/Ninth_grade_replacement_scores/type_summary.png
    
 

## Challenge Summary
The changes that were visable in the updated school district analysis were when looking at the district summary and school summary. In each of theis data frames, when looking at the unformatted data you can see the difference in tenths of percents. The reading and math scores in each of these data frames does down by the a few tenths of a percent.
