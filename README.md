# School District Analysis

## Overview

The purpose of this analysis is to provide insights about spending and performance for a school district. The aggregated data includes information on school funding and student standardized tests scores. These insights are to aid the school board in making decisions based on budgets and educational priorities. The original analysis includes data for all students within the district. Recent evidence suggests the reading and math scores for Thomas High School ninth graders is compromised. The analysis was run again, and is now available without the compromised data.

## Results

The following results are a comparison between the original analysis and the analysis performed after the compromised data was removed. For complete detail on the analysis, refer to the analysis script.

![Complete_Python_Script](/PyCitySchools_Challenge.ipynb)

### District Summary

The removal of the Thomas High School (THS) ninth graders resulted in a drop in average math score, no affect on average reading score, drop in percent passing math, drip in percent passing reading and a drop in percent overall passing. Although these changes were in fractions of a percent, the change is measureable.

Original Analysis

![District_Summary](/Resources/district_summary.png)

Analysis with Thomas High School(THS) 9th graders removed

![District_Summary2](/Resources/district_summary_RTHS.png)

### School Summary

The removal of the THS data only affected the outcomes for Thomas High School in the School Summary, because the results are broken out by school. THS did see changes in scores and passing percents, all fractions of a percent.

Original Analysis

![School_Summary](/Resources/school_summary.png)

Analysis with Thomas High School(THS) 9th graders removed

![School_Summary2](/Resources/school_summary_RTHS.png)


### Thomas High School Performance

Although the removal of the THS ninth graders data did lower average tests scores and the passing percents, it was not enough to change Thomas High School's ranking relative to other schools. Thomas High School still ranks second in overall passing percent for the district.

Original Analysis

![TopFive_Summary](/Resources/top_five_schools.png)

Analysis with Thomas High School(THS) 9th graders removed

![TopFive_Summary2](/Resources/top_five_schools_RTHS.png)

### Scores by Variable

#### Math Scores by Grade

The summary for *Math Scores by Grade* is broken out by school. The only data affected is the THS ninth grade scores which are now *NaN*.

Original Analysis

![Math_Scores](/Resources/math_scores_by_grade.png)

Analysis with Thomas High School(THS) 9th graders removed

![Math_Scores2](/Resources/math_scores_by_grade_RTHS.png)

#### Reading Scores by Grade

The summary for *Reading Scores by Grade* is broken out by school. The only data affected is the THS ninth grade scores which are now *NaN*.

Original Analysis

![Reading_Scores](/Resources/reading_scores_by_grade.png)

Analysis with Thomas High School(THS) 9th graders removed

![Reading_Scores2](/Resources/reading_scores_by_grade_RTHS.png)

#### Scores by School Spending

The removal of THS ninth graders data was not enough to influence the results of *Scores by School Spending*.

Original Analysis

![Spending_Summary](/Resources/spending_summary.png)

Analysis with Thomas High School(THS) 9th graders removed

![Spending_Summary2](/Resources/spending_summary_RTHS.png)

#### Scores by School Size

The removal of THS ninth graders data was not enough to influence the results of *Scores by School Size*.

Original Analysis

![Size_Summary](/Resources/size_summary.png)

Analysis with Thomas High School(THS) 9th graders removed

![Size_Summary2](/Resources/size_summary_RTHS.png)

#### Scores by School Type

The removal of THS ninth graders data was not enough to influence the results of *Scores by School Type*.


Original Analysis

![Type_Summary](/Resources/type_summary.png)

Analysis with Thomas High School(THS) 9th graders removed

![Type_Summary2](/Resources/type_summary_RTHS.png)

  
##Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
