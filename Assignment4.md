Assignment -4  (Sales Report)							


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/f4803db5-c6e3-408d-b2aa-d1a1d9be0b31)

Q1.How many salesman?

Answer:
To find the number of salesman using the following formula,
=COUNTA(A4:A15), where, 4 is the first row of Salesman(A), and 15 is the last row of Salesman(A).


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/1efd73e2-5c29-4851-a0ef-a393a6146cc7)


Q.2 If Sales Greater Than Target Then Target Achived otherwise Not Achived.

Answer:
To find the answer using the following formula,
=IF(H22:H32>I22:I32,"Achived","Not Achived"), where,22 is the first row of Sales(H), and 32 is the last row of sales(32).
22 is the first row of Target(I), and 32 is the last row of Target(I).


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/d3f85d49-bfbd-4fae-9876-2907437a0f8a)


Q.3 Rahul Pooja & Ashok Targest & result?

Answer: 
To find the answer using the following formula,
=VLOOKUP(A37,A21:J32,9,0) and=VLOOKUP(A37,A21:J32,10,0), where, column Ais Salesman, 9 is Target and 10 is Result.



![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/e20e614e-50b6-4cfa-8e99-359dc1e00f91)


Q.4 How Many Salesman Achived Target.

Answer: 
To find the answer using the following formula,

=COUNTIF(J22#,"Achived"), where J is the Result column.



![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/d9742c26-918c-48c9-9dca-3074d8cbb47f)


Q.5 Which Sales Man Jan Sales 2000, & Feb Sales is 2500?


Answer: 
To find the answer using the following formula and need to rearrange the original table,


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/e00cc4a7-592d-4a94-af5e-05e1c54a5412)

Formula:=VLOOKUP(C45,L4:N15,3,0), where 3 is Salesman.


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/6df32489-3ed2-4e5b-ad08-60831058a9c7)



