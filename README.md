# School_District_Analysis

**Overview of the school district analysis**

The purpose of this analysis was to determine the passing rates and percentages in maths, reading and overall (combined) for grade 10-12 students from "Thomas High School". In addition, a further analysis was conducted to determine if student's scores in maths and reading got impacted by the budget, school type and school size. The code also produced lists of grade 10-12 students from Thomson High School, who were passing maths and reading. Two csv files were imported into the jupyter notebook named as students_complete.csv and schools_complete.csv. The code was also re-factored to replace grade 9 student's score in math and reading from Thomson high school with 'Na'. Overall, the main goal of this analysis was to help Maria to analyze data on student's math and reading standardized test scores. Since there has been evidence of academic dishonesty at Thomson High School, specifically for the the grade 9 students, math and reading scores for Thomas High School were replaced with NaNs while keeping the rest of the data intact. Once the data was cleaned, the school district analysis was repeated. 

**Results**

The bullets below will show how each of the seven school distrit metrics that were studied have been affected by the changes in data due to the removal of the Thomas High School nineth grade scores.

District analysis prior to data cleaning for math and reading scores

<img width="1316" alt="Screen Shot 2021-10-10 at 7 41 38 PM" src="https://user-images.githubusercontent.com/90429568/136716655-578b0db6-8871-499d-8d2c-63d80df8bef0.png"><img width="1057" alt="Screen Shot 2021-10-10 at 8 38 11 PM" src="https://user-images.githubusercontent.com/90429568/136718728-9faf00b0-943d-4cbf-973b-c5a28b7e94ec.png">


District analysis for math and reading scores post data clean

<img width="1081" alt="Screen Shot 2021-10-10 at 7 33 10 PM" src="https://user-images.githubusercontent.com/90429568/136716436-81b58586-8ce2-4b7c-9be7-3435d50e7773.png">

From this analysis, it can be deduced that the data did not get affected by significant amounts after the 461 students from the Thomson High School were removed from the data set. The overall passing percentage dropped by less then one point, and the passing math and reading scores dropped by hundreths of a percentage point.

Affects on school summary prior to data clean

<img width="1057" alt="Screen Shot 2021-10-10 at 8 20 55 PM" src="https://user-images.githubusercontent.com/90429568/136717998-64db7ba7-4b17-4e65-bdba-a59a95213ea8.png">


School summary post data clean

<img width="1057" alt="Screen Shot 2021-10-10 at 7 47 12 PM" src="https://user-images.githubusercontent.com/90429568/136716774-8fb187a7-8c2a-4078-97cb-179fde9dec0c.png">

When comparing the original data to the adjusted data with the removal of about 400 students from Thomas High School, the high school saw a huge affect on its numbers. It's overall passing percentage dropped from about 91% to about 65%.

Thomas High School’s performance relative to the other schools prior to data clean

<img width="1057" alt="Screen Shot 2021-10-10 at 8 23 35 PM" src="https://user-images.githubusercontent.com/90429568/136718098-5685b407-c9f5-4d0f-9c8c-ae8f3c4082c7.png">

Thomas High School’s performance relative to the other schools post data clean

<img width="1057" alt="Screen Shot 2021-10-10 at 8 30 28 PM" src="https://user-images.githubusercontent.com/90429568/136718408-52e8696a-ed93-4285-b919-6c923565c496.png">

Ranking dropped from being top to about middle position.

Math scores by grade prior to data clean

<img width="565" alt="Screen Shot 2021-10-10 at 9 49 31 PM" src="https://user-images.githubusercontent.com/90429568/136722265-4ac07ca2-f3ce-4977-9705-0fe38ebff62a.png">

Reading scores by grade prior to data clean

<img width="565" alt="Screen Shot 2021-10-10 at 9 49 44 PM" src="https://user-images.githubusercontent.com/90429568/136722253-fb77ad2f-99c0-424c-92f9-c2448fed9fea.png">


Math scores by grade post data clean
<img width="1057" alt="Screen Shot 2021-10-10 at 8 45 30 PM" src="https://user-images.githubusercontent.com/90429568/136719025-ffe3a312-4f0c-47be-b8b9-12f2eeb0c36d.png">

Reading scores by grade post data clean

<img width="1057" alt="Screen Shot 2021-10-10 at 8 46 03 PM" src="https://user-images.githubusercontent.com/90429568/136719051-367e0169-08b2-4d3f-b5dd-f041a7911109.png">

Grade 9 scores are replaced with Na.

Scores by school spending pre data clean

<img width="1274" alt="Screen Shot 2021-10-10 at 8 59 07 PM" src="https://user-images.githubusercontent.com/90429568/136719654-7241a61c-3742-40b9-9ed4-d1ebe2118641.png">

Scores by school spending post data clean

<img width="1045" alt="Screen Shot 2021-10-10 at 8 58 53 PM" src="https://user-images.githubusercontent.com/90429568/136719665-e6d299a4-e798-4699-8dc1-5db021b0df1a.png">

The school spending data comes from a much larger data pool because it includes all students across all grades within the district. While the mid-budget schools that include Thomas High School did see a drop in their scores, the difference was minimal.

Scores by school size pre-clean

<img width="1274" alt="Screen Shot 2021-10-10 at 9 01 57 PM" src="https://user-images.githubusercontent.com/90429568/136719790-09875ef3-a6a3-4748-ae92-04094e0d0d80.png">

Scores by school size post-clean

<img width="1063" alt="Screen Shot 2021-10-10 at 9 02 21 PM" src="https://user-images.githubusercontent.com/90429568/136719798-7516792c-6781-472f-9283-192295ce4df9.png">

Scores by school type pre-clean

<img width="1336" alt="Screen Shot 2021-10-10 at 9 03 42 PM" src="https://user-images.githubusercontent.com/90429568/136719838-c6c314ca-6985-45eb-8e44-93a1d0ac6cf7.png">

Scores by school type post-clean

<img width="788" alt="Screen Shot 2021-10-10 at 9 03 58 PM" src="https://user-images.githubusercontent.com/90429568/136719855-6775ba19-c66d-4240-90ff-1bbbf847a1c6.png">

The charter school data that include Thomas High School did see a drop in their scores, the difference was not impacted severly by the removal of the nineth grade scores.

**Summary**
The four changes that occured as a result of the data clean:

- Math and reading scores by grade: Grade 9 grades for both reading and math grades for Thomson High School students got replaces by "Na". Rest of the data set for the scores was not impacted by much.
- Scores by school spending- Since, Thomson High School fell under mid-budget category, the effect on scores was minimal i.e. impact occurred at the hundredth place for all three (reading, math and overall) scores.
- Scores by school size- Similar to situation above, since Thonson High School belongs to medium size catgeory, scores in this category drop by a minimal effect.
- Scores by school type- Charter school district observes a slight drop in values, since Thomson High School belongs in this district. 
