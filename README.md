# School_District_Analysis
School Analysis grades using Pandas
# Overview of the school district analysis
  The porpuse of this analysis is to understad different procedures that can be apply to a Data Frames and lists or series, in order to clean, analyse, work, and display them in a way everybody can understand the presentation of data.
Therefore in this analysis is asked to replace the reading and math scores by NaN values due the inconsistency existed in Thomas High School for the 9th grades in the math and reading scores. Doing this, we will have to analyse the School District anlysis newly, getting different metrics for the new Data Set after that action.
Finally we will analyse how this changes affected the retrieved values.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
* How is the district summary affected?
The district summary is affected with replacing all the math and reading scores with "NaN" values, which mean that there is no value in those rows.
Thus in the moment wwe get some metrics they will be changed automatically so the summarizing reults will retrieve differents values.
* How is the school summary affected?
The values for the school summary were not affected after replacing the NaN. We could say that in the "budget" field, it is assigned by school, not by student directly,  therefore the total budget remained intact.
FOTO
FOTO
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The "average math and reading scores" were not affected either due the calculation for these values is directly proportional to the number of students.

* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade
  The way doesn´t affect the scores for the rest of the schools, exept for the "Thomas High School" due it will reduce its general average score in           comparision with the rest of the schools.
  PHOTO
  * Scores by school spending
  For this metric, the replace of the ninth-graders don´t affect the budget per school, neither the per student bugdet, beacuse although the Thomas High Scholl could not waste part of the budget in the classmates for the ninth grades, the per studet budget has an assigned amount since the begining.
  
  * Scores by school size
  This field wasn´t
  * Scores by school size affected afetr replacing the ninth grades for NaN values, because althoug the size of student was reduced instantly, the schools are independant with their grades.
  * Scores by school type
  In this field the results will be affected due the "type" of Thomas High School is Charter, so this school dont have reading and math grades therefore   the average will be reduced for all the "charter" type schools in comparision with the "District" schools.
  PHOTO
# Summary
We could mention that there were some changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs. 
To start with, the number of student was reduced in nearly 500 students, secondly we. got a new Data Frame at merging our school_data_df and student_data_df, third we have our updated data frame with values = NaN, and four we create new Data Frames when summarizing information.
