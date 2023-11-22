# Excel-exercises-with-solutions
Assignment1:


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/ece2b3ee-c908-4117-8749-2d5a9c6c19db)



Q1. Find the Total Number & Average in all Subjects in Each Student (from above table).

Answer:
For Total number, following formula used for first row and dragged over subsequent rows.

=SUM(C19:G19),where 19 is the 1st row of column Hindi(C) and G19 is the 1st row of column Chemistry(G)



For Average, following formula used,
=Average(C19:G19),where 19 is the 1st row of column Hindi(C) and G19 is the 1st row of column Chemistry(G)



![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/a49fcc0c-0352-4947-88df-d134bed9ba3b)


Q.2 Find Grade Using If Function - If Average Greater  >15 then "A" Grade otherwise "B" Grade.

Answer:
For Grade, the following formula is used and dragged over subsequent rows.
=IF(I33>15,"A","B") , where, 33 is the first row Average(I)



![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/8c954d81-da77-4c32-a906-d7202ea234ea)



Q.3 How Many Student "A" and "B" Grade .

Answer:
To find out the number of students for grade "A" and grade "B", the following formula is used,
=COUNTIF(J33:J42,"A") and =COUNTIF(J33:J42,"B") where 33 is the first row of Grade(J) and 42 is the last row of Grade(J)




![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/5cc411a5-aebe-483b-925b-71ac13e35605)


Q.4 Student Ashok and Manoj Total Number and Average 

Answer:
To find the total number and Average of Ashok and Manoj (SUMIF) formula is used. the formula is as followed,
=SUMIF(B33:B42,A52,H33:H42), where B33 is the first row of the student name, B42 is the last row of the student name and H33 is the first row of total number, H42 is the last row of the student name.




![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/1810e170-7b13-49c2-9623-0937f7e426ba)



Q.5 Count how many Students 

Answer:
To find the total number of students we use COUNTA formula, the formula is as follows,
=COUNTA(B33:B42), where 33 is the first row of the students(B) and 42 is the last row of students(B).

![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/54f395b2-b749-4f7d-8163-2e2116ff49bc)


Q.6 How Many Student Hindi & English Subject Number Grater Then > 20 and <15 

Answer:
To find the answer we use the following formula,
=COUNTIFS(C32:C42,">15",C32:C42,"<20"), where 32 is the first row of Hindi(C) and 42 is the last row of Hindi(C)

And=COUNTIFS(D32:D42,">15",D32:D42,"<20"), where 32 is the first row of English(D) and 42 is the last row of English(D)



![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/0a8f5048-33be-4aae-9414-11b815cda54e)































