# School_District_Analysis

## Summary of Findings
### In Deliverable 1:
The data was collected from a CSV file, detailing students from different high schools that comprises of student_id,
- student_name, 
- grade,	
- school_name, 
- reading_score,	
- math_score,	
- school_type and	
- school_budget.

### In Deliverable 2:
The data types were of the following for each column:
- student_id         int64
- student_name      object
- grade             object
- school_name       object
- reading_score    float64
- math_score       float64
- school_type       object
- school_budget      int64
- dtype: object

THe image below showa the function is null 
![isnull](https://github.com/JaredTMurray/School_District_Analysis/blob/main/Student_Data_Challenge_Starter_Code/Unsolved/d2_isnull.png)

### In Deliverable 3:
Analysis of the Dataset for student_df contains numerical data, the description contains these information for each column:

- count - The number of not-empty values.
- mean - The average (mean) value.
- std - The standard deviation.
- min - the minimum value.
- 25% - The 25% percentile*.
- 50% - The 50% percentile*.
- 75% - The 75% percentile*.
- max - the maximum value.

An overall average math score was 64.7 and the minimum reading score 10.5.


### In Deliverable 4:
Research was undertaken to drill down deeper into the grades, math score, reading score. It found the minimum reading score using different methods for a specific high school. The mean reading score was found for all students in grade 11 and 12 combined, which was 74.9.

### In Deliverable 5:
Public High schools were found to have lower math scores in the 9th to 11th grades but higher math grades in the 12th grade than Chartered high schools. Public High schools were found to have higher reading scores in grades 9, 10 and 12, but lower reading scores for grade 11, than Chartered High schools respectively. 
Montgomery High School was found to have the highest number of students with 2038, and Chang High School was found to have the lowest with 171.
Public High schools have a higher budget than Chartered High Schools.

Please click on link to view file: [School_District_Analysis file](https://github.com/JaredTMurray/School_District_Analysis/blob/main/Student_Data_Challenge_Starter_Code/Unsolved/Student_Data_Challenge_Starter_Code.ipynb)
