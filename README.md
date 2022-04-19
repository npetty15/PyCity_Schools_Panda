# PyCity Schools Analaysis Pandas

## Purpose

The intial review of the school information was to determine the math and reading scores of students and by using the sum of those student scores, we were able to review several matrixes. Those being a review of the top five and bottom five performing school by overall passing percentage, grade level per school organized by school, in addition to, school size and school type. 

With the initial review being sent to the school board upon approval from Maria, the school board wanted an additional review done, as they believed that Thompson High School (THS) was being dishonest with their grading for their 9th grade class. With instruction from Maria, I was asked to replace all scored for the 9th graders at THS with Nans, or essentially removing the data as to not be counted. Then once that was complete to re-run the original analysis done to break down into the pre-established catagories from the first review. 

## Analysis Results

### How is the District Summary Affected?
- Original School Report

![Original_District_Summary_df](https://user-images.githubusercontent.com/100856534/163899881-cd6ad519-5fcc-49e4-9edb-f5eb1a8f8752.png)

- Refactored School Report

![Refactored_District_Summary_df](https://user-images.githubusercontent.com/100856534/163899935-f4769dec-58cd-4d87-b2ce-60ba35ce2448.png)

**Effect of Removing the 9th Graders at THS**

With the scores from the 9th graders removed you can see that the districts scores and percentages for math have been reduced. Reading average scores remained the same. The overall passing percentage reduced from 65.2% to 64.9% 

### How is the School Summary Affected?
- Original School Report

![Original_School_Summary_df](https://user-images.githubusercontent.com/100856534/163904252-f7deb40d-2aab-4dec-8b6c-f48ca0ccca26.png)

- Refactored School Report

![Refactored_School_Summary_df](https://user-images.githubusercontent.com/100856534/163904280-d8e98f31-81fc-4fea-9caf-35588dcf64de.png)

**Effect of Removing the 9th Graders at THS**

Here when we look at THS as the scores and percentages for math have dropped. However, interestingly enough the average scores and percentage for Reading rose slightly when the 9th graders were removed. 

### How Does Replacing the 9th Graders’ Math and Reading Scores Affect THS’s Performance Relative to the Other Schools?


