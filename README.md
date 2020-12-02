<h1 align="center">SAT Performance in NYC High Schools</h1>
<img src="Photos/SAT Test Taking.png" width=100%>

In this three-part project, I examine how high school students in New York City perform on the SAT test as well as the various demographic factors that correlate with SAT performance.
- **Part 1:** Cleaned eight datasets containing demographic information about NYC schools, selected relevant information from each dataset, and combined all datasets into a single dataset.
- **Part 2:** Analyzed and visualized the various demographic factors of each high school and each factor correlated with SAT performance. The demographic factors analyzed were:
  - Total Enrollment = the number of students enrolled in a given high school
  - Class Size = the average class size of a given high school
  - Ethnicity = a given high school's ethnic breakdown (white, black, Hispanic, Asian), in other words, the percentage of students from each ethnicity
  - English Language Leaners = the percentage of students who are in the ELL program (implying they are learning English)
  - Gender = the percentage of students belonging to a given gender (male, female)
  - Self-Reported Safety = score from 1 to 10 indicating how 
- **Part 3:** Filtered the combined dataset by school district and created maps detailing the average SAT score of each NYC school district

The purpose of this project is to help school districts determine which students might need additional help on the SAT. Since SAT exam scores are a major component in American university admissions, determining which students are struggling the most is of upmost importance.

The original eight datasets I used for my analysis can be accessed here:
- <a href="Required Datasets/ap_2010.csv">ap_2010</a> = information about AP exams
- <a href="Required Datasets/class_size.csv">class_size</a> = information about the average class size
- <a href="Required Datasets/demographics.csv">demographics</a> = information about total enrollment, gender, ethnicity, and ELL students
- <a href="Required Datasets/graduation.csv">graduation</a> = information about graduation rates
- <a href="Required Datasets/hs_directory.csv">hs_directory</a> = information about the location of the schools
- <a href="Required Datasets/sat_results.csv">sat_results</a> = information about SAT results
- <a href="Required Datasets/survey_all.txt">survey_all</a> = survey about student safety
- <a href="Required Datasets/survey_d75.txt">survey_d75</a> = another survey about student safety

The two datasets I created using the datasets above can be accessed here:
- <a href="Created Datasets/combined.csv">combined</a> = contains all relevant information categorized by school
- <a href="Created Datasets/districts.csv">districst</a> = contains all relevant information categorized by school district
