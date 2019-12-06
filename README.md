Problem Definition

FAILED COURSE CREDIT RECOVERY
Proof of Concept, 
From Concept to Practical to Experimental
By : Raghu Bayya


To predict the student's performance in the course, whether students could able to complete the course successful or not 


Here we are not investigating the factors influence the student performance in the course. Based on the information we have, we perform prediction model and not being judgemental to student performance because number of other factors influence which cannot be measured. 


Indicator identified :  Student_Id, Age, Course_No, Announcement_view(No of times), Absent, Average, Course_Hr, no of Consultation.  

Additional conditions :
      Students must have a final course mark of 50 % or greater and less than 60%.
     Less than 30% of absences to his/her course.
   To Evaluate how no of absences in course  will influence the final grades of students .



Confidentiality : Follow content in this document are confidential and intended solely for the use of the individual or entity to which they are addressed. If you receive this document in error please notify to the user. 

Important : Content in this document is free use, you can only use for education and learning purposes not for commercial use, knowledge transfer. No personal data  is used in exercise if only with permission.  


-----Data Prepration----- 

Data has collected form source of evaluation,  


Convering the Students Grades into catagorical variables

1. Grades grater then equal 60 and less then equal to 100 pass
2. Grades greater then equal 50 and less than equal to 59 Re-take
3. Grades greater then equal to 0 and less then equal to 49 re-do
