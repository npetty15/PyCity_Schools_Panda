# PyCity Schools Analysis Pandas

## Purpose

The initial review of the school information was to determine the math and reading scores of students and by using the sum of those student scores, we were able to review several matrixes. Those being a review of the top five and bottom five performing school by overall passing percentage, grade level per school organized by school, in addition to, school size and school type. 

With the initial review being sent to the school board upon approval from Maria, the school board wanted an additional review done, as they believed that Thompson High School (THS) was being dishonest with their grading for their 9th grade class. With instruction from Maria, I was asked to replace all scored for the 9th graders at THS with Nans, or essentially removing the data as to not be counted. Then once that was complete to re-run the original analysis done to break down into the pre-established categories from the first review. 

## Analysis Results

### How is the District Summary Affected?
- Original School Report

![Original_District_Summary_df](https://user-images.githubusercontent.com/100856534/163899881-cd6ad519-5fcc-49e4-9edb-f5eb1a8f8752.png)

- Refactored School Report

![Refactored_District_Summary_df](https://user-images.githubusercontent.com/100856534/163899935-f4769dec-58cd-4d87-b2ce-60ba35ce2448.png)

**Effect of Removing the 9th Graders at THS**

With the scores from the 9th graders removed you can see that the districts scores and percentages for math have been reduced. Reading average scores remained the same. The overall passing percentage reduced from 65.2% to 64.9%. This makes sense, as the 9th grade class of THS is a small portion of nearly $37,000 students in the district. The over change should be minimal. 

### How is the School Summary Affected?
- Original School Report

![Original_School_Summary_df](https://user-images.githubusercontent.com/100856534/163904252-f7deb40d-2aab-4dec-8b6c-f48ca0ccca26.png)


- Refactored School Report

Below is showing the district results using only the 10th to 12th grade scores at THS

![Refactored_School_Summary_df](https://user-images.githubusercontent.com/100856534/163904280-d8e98f31-81fc-4fea-9caf-35588dcf64de.png)

Below is showing the district results using all of 9th to 12th grade scores at THS, but the 9th grader's math and reading were NaN out. 

![Refactored_School_Summary_9to12_df](https://user-images.githubusercontent.com/100856534/164541869-5fd13aac-776c-4f87-97df-6ccd25be46ff.png)

**Effect of Removing the 9th Graders at THS**

In review of the data, if we kept the 9th graders in and went through the analysis, the high school would suffer from the result. For if we left the 9th graders in the review, THS would suffer from lower test scores based on an entire 9th grade class getting 0's. So what ended up occurring was only using the test data for the 10th to the 12th graders at THS. Here we can see that the math scores dropped, reading scores stayed similar. More interesting was that the percent passing dropped for both reading and math and the overall passing dropped as well 

### How Does Replacing the 9th Graders’ Math and Reading Scores Affect THS’s Performance Relative to the Other Schools?

- Original School Report

![Original_Top_Five_School](https://user-images.githubusercontent.com/100856534/164542809-3bf758cc-5f47-417f-87f4-bc1eb5ac7679.png)

- Refactored School Report

![Refactored_Top_Five_School](https://user-images.githubusercontent.com/100856534/164542862-90322774-052f-47e8-90d9-4e76bd800bd4.png)

**Effect of Removing the 9th Graders at THS**

Again here, with removing the 9th grader's passing results from the THS data in the analysis, THS remains as the 2nd best when overall passing percentage is considered. However, as can be seen from the previous school summary, if the 9th grader's scores were removed, but their student count was not, THS would have dropped drastically in the rankings. 

## How Does Replacing the 9th Grade Scores Affect the Following:

### Math and reading scores by grade

- The main difference here for the overall passing grades per grade was that the 9th grade scores have been made null and taken out of the report. Overall, there was no drastic change to the other scores. 

### Scores by school spending

![Scores_per_Spending_Bin](https://user-images.githubusercontent.com/100856534/164546188-ba7f74b9-8362-465b-9ed4-498fc79da4d3.png)

- The overall change per school spending range is nominal as, there is no noticeable change at the whole integer level. 

### Scores by school size

![Scores_by_school_size](https://user-images.githubusercontent.com/100856534/164547164-b75828d2-5592-4367-be8c-ee8ac0b308d8.png)

- The change in passing rates are minimal to the overall passing rates of the district if THS 9th grade scores are removed. 

### Scores by school type

![school_by_type](https://user-images.githubusercontent.com/100856534/164547330-fe1e2a2a-33d2-42d8-b7f4-9b52c4808f0a.png)

- The change here shows us again that the rate change in overall passing scores of the district are fairly minimal when all the scores are combined. 

## Analysis Summary

When comparing the overall passing rates of math and reading for THS, there are two ways to look at it. One being, what is the schools passing rate if the 9th grade scores are removed, but the student count kept in. The other being what are the scores for only the 10th to 12th grades. If the 9th graders were kept in, THS' overall passing percentage dropped drastically from 90% to 65%. However, if the 10th to 12th graders are looked at alone, without the null 9th grade scores and student count, then the overall passing rate does not change much at all. 

When we review the overall placing of schools before and after the scores were removed, we again can look at this in two ways. If the 9th grade student count is left in the school would drop to around mid-range in over all passing percentage. If only the 10 to 12th grade scores are reviewed, THS remains at second best overall scores. 

With the overall changes to the district level reports not being very substantial, it would make sense for a deeper dive of students themselves in this 9th grade class. Doing a review at this level would show if there is a substantial difference between these schools. For example, are the THS scores comparable to other charter schools in the district or are the comparable to their per capita budget category. When this review is taken at the district level the changes do not reflect a very large change. Doing a different type of review may bring more clarity of test scores at THS. 

