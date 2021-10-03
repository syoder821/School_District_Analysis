# School_District_Analysis

## Project Overview
An analysis of the school district was completed and supplied to the school board.  The analysis contains summaries based on school type, school size, school spending, and scores by grade.  The school board believes the data file provided for the initial analysis shows evidence of dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have asked for the math and reading scores for Thomas High School to be replaced with NaNs while keeping the rest of the data intact.  The school district analysis was repeated with the updated dataset to determine the affect on the overall analysis.  

## Resources
- Data Source: election_results.csv
- Software: Anaconda virtual environment Python Jupyterlab Pandas

## Results:
### Affect on District summary:

- Original District summary
![Alt Text](https://github.com/syoder821/School_District_Analysis/blob/main/Analysis/District_summary.png)


- Updated District summary:

![Alt Text](https://github.com/syoder821/School_District_Analysis/blob/main/Analysis/District_summary_updated.png)


The district summary was minimally affected with the removal of the Thomas High School ninth grade scores.  The overall passing percentage decreased by 0.1%.  

### Affect on School summary:

- Original Top Schools summary:

![Alt Text](https://github.com/syoder821/School_District_Analysis/blob/main/Analysis/top_schools_summary.png)

- Updated Top Schools summary:

![Alt Text](https://github.com/syoder821/School_District_Analysis/blob/main/Analysis/top_schools_summary_updated.png)


The school summary was also minimally affected with the removal of the Thomas High School ninth grade scores. Thomas High School's overall passing percentage decreased 0.31%.  Thomas High School's overall passing performance relative to other schools remained unchanged.  After updating the Thomas High School ninth grade scores, Thomas High School has a lower passing reading percentage than Griffin High School.
The math and reading scores for Thomas High School now show nan in the summary of math and reading scores by grade.  
The scores by school spending, school size, and school type summaries are unchanged with the updated dataset removing THS ninth grade scores.  

## Summary
Average math scores, passing math percentage, passing reading percentage, and overall passing percentage all decreased slightly after the reading and math scores at Thomas High School have been replaced with NaNs.  
