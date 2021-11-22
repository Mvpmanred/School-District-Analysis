# School-District-Analysis
## Overview of the school district analysis
  The main purpose of this project is to analyze high shcool students standardardized test scorse data, passing rates, and student funding from variety of sources and formats. I will be helping Maria to prepare all standardized test data for anaalysis reporting and presentation to provide insights about performance trends and patterns. These insights are used to inform discussions and strategic decisions at the school and district level. And the challenge is to change math and reading scores for ninth grade students and replace them with "NaN" and run analysis for 10th to 12th graders.
  
## Results
![Nan 9th](https://user-images.githubusercontent.com/92561493/142800994-64cb2a4e-3db7-4838-b09a-d07e8dfcccc3.PNG)
  -First we entered code "student_data_df.loc[(student_data_df["school_name"] == "Thomas High School") & (student_data_df["grade"] == "9th"), "reading_score"] = np.nan" to replace 9th grade reading scores by using "NaN" values.
  -With the same method, we entered code "student_data_df.loc[(student_data_df["school_name"] == "Thomas High School") & (student_data_df["grade"] == "9th"), "math_score"] = np.nan" to replace 9th grade math scores by using "NaN"
  -After we altered the data, there would be some changes in metric references.

![before 9](https://user-images.githubusercontent.com/92561493/142800706-caa216de-02e2-49fa-bd44-ea8645cc5d72.PNG)
![district without 9](https://user-images.githubusercontent.com/92561493/142800715-f43aaafc-6b27-4bbb-b840-bf605c66d05c.PNG)
 -The changes in data has affected some of school disctrict metrics. The first picture is the orignal analysis from disrict summary. The second picture is the updated 
  -As we can see from both pictures.Total students, Total budget and Average Reading Score have remained unchanged.
  -Other three metrices: Average Math Score, %Passing Math and % Overall Passing have changed.
  
  
  ## Summary
    After we replaced nineth grade data with "Nan", we observed that 3 of district metrics were changed. The average math score has decreased 0.1%; the percentages of passing math has decreased 0.2%; percentages of overall passing has decreased 0.1%. Since the average math score has decreased, we can also conclude that percentages of passing both math and reading also decreased. With these observations, we are able to inform discussions and strategic decisions at the school and district level in order to allcoate student funding. 
