Assignment-5


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/2dc03684-b7a3-4d26-abb3-0336f52a36f3)


Q.1 HOW MANY ITEMS ?

Answer: 
To find the answer using following formula,

=COUNTA(A6:A23), where 6 is first row of items(A) and 23 is the last row of items(A).

18

Q.2 HOW MANY BRAKE, WINDOW & TYRES HAVE BEEN BOUGHTS?

Answer: 
To find the answer using following formula,

=COUNTIF(A6:A23,"BRAKES"),=COUNTIF(A6:A23,"WINDOW"),=COUNTIF(A6:A23,"TYRES")
where,
6 is the first row of items(A) and 23 is the last row of items(A).


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/6f1181b8-17ce-4d48-aa71-a657e7157575)


Q.3 HOW MANY ITEMS COST IS >1000 & BELOW > = 1000?

Answer: 
To find the answer using following formula,

=COUNTIF(C6:C23,">1000") and=COUNTIF(C6:C23,"<=1000"), where 6 is the first row of cost(C) and 23 is the last row of cost(C).


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/feebe416-6eb8-46f9-95c1-613e88f9625d)


Q.4 HIGHLIGHT TYRES ITESM & 500 BETWEEN 2000 COST.

Answer: To solve the question we are using conditional formatting.



![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/27442274-46d4-4a8a-b6fc-4998eb37425f)


Q.6 Total Cost of Window and Brakes Items? 

Answer: 
To find the answer using following formula,

=SUMIFS(C41:C53,A41:A53,"WINDOW")and =SUMIFS(C41:C53,A41:A53,"WINDOW"), where  C is the cost column and A is the Item column.


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/eb26c0cc-fa71-49c2-ac91-281f05df123e)







