				
![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/c05040da-21d6-4116-889f-59c3113e7867)


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/8f729d1d-af75-4aef-8d42-0ab3e49d8a20)


Q.1 HOW MANY SUBJECT ? 

Answer:
To find out the number of subjects using the following formula,

=COUNTA(A5:A13), Where 5 is the first row of Subject(A) and 13 is the last row of Subject(A).


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/2541683f-e8ce-4b8e-bddd-c48779218e84)




Q.2 HOW MANY SUBJECT 1 PAPER GREATER THAN 20 ? 

Answer:
To find out the required answer using the following formula,

=COUNTIF(B5:B13,">20"), Where 5 is the first row of Subject1(B) and 13 is the last row of Subject1(B)


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/fd81f3a9-a8f5-4583-90b4-c70eaccc9524)


Q.3 SUBJECT HINDI, MATH & ENGLISH TOTAL NO. & GRADE .

Answer: 
To find the answer using the following formula,

=VLOOKUP(A22,A4:G13,5,0) and=VLOOKUP(A22,A4:G13,7,0), where, A stands for subject, column 5 is "Total" and column 7 is "Grade".


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/2474dbbb-0be8-4263-9896-604cd8f1c282)


Q.4 IF AVE. GREATHER THAN 20 THEN "A", IF AVE. GREATEHR THAN 15 AVE. "B" OTHERWISE "C"


Answer:

To find the answer using the following formula,

=IF(F29:F37>20,"A",IF(F29:F37>15,"B","C")), Where, 29 is the first row of Average(F) and 37 is the last row of Average(F).


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/8e6176d8-a5a1-4c3e-87f2-e9eef10fc238)


Q.5 SUBJECT PHYSICS, MATHS & ENGLISH TOTAL /AVERAGE 


Answer:

To find the Answer using the followind the followinf formula,

=VLOOKUP(A42,A28:G37,5,0) and=VLOOKUP(A42,A28:G37,6,0), where "A" stands for Subjects, column5 is "Total number", column6 is "Average".



![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/24ca8cd4-57a8-4da3-93b1-38ab68ee4019)

 
