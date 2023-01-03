# School_District_Analysis

## The Findings

When we first summarize the data in Delivarable 3 we find:
- Amongst all schools, the average reading score is higher than the average math score

As we drill deeper in th data in Deliverable 4 we find:
- If we compare grade 9 average scores with average scores amongst all students, grade 9 has higher math scores but lower reading scores; however, the grade 9 average score for reading is still higher than the average score for math.
- Average reading and math scores vary by school. Just by looking at the first 3 schools in the data set, Sullivan High School struggles in reading while Dixon High School excels in this same category
- We're also able to find who has the lowest reading score as Matthew Thomas was identified with a readins score of 10.5. 
- The combined average reading score for grades 11 and 12 are higher than the total average. This could indicate that grades 9 and 10 need more attention in reading

In Deliverable 5, the analysis creates comparisons between charter and public schools. The findings are:
- Public schools have higher school budgets compared to Charter schools
- Montgomergy High School has the most amount of students while Chang High School has the least amount of students
- 12th grade Charter school students had the lowest scores in math while 9th grade Charter students had the highest scores.
- 11th grade public school students had the lowest scores amongst other public school students in other grades

## Additional Analysis

The findings of this analysis does not follow a defined pattern for straight-forward analysis; however, the code used provides an excellent template to create a comprehensive analysis. 

For example, one finding that would aid the analysis is finding average math and reading scores by school name. We can use groupby and mean functions to help create a dataframe to support this finding. As a result, we could see which schools are struggling in which area more in order to better allocate resources. If we wanted to focus on specific students, for instance, students that scored below the 25th quartile, we can also create a dataframe to list all students that fit this criteria. Furthermore, we can use this code to find additional insights regarding how school budget correlates with reading and math scores. This can be filtered by school type as well. 
