
 ![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/dfae747a-ef16-4686-8ba9-66e31e000f0d)


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/85a6ba15-3f37-4729-9f3e-00357f805b64)

Question: What is the column number for the size Grande,Tall, Venti?

Answer: To find the answwer using following formula,

=MATCH(A18,A4:D4,0), where A is "classic favorite column", B is "Tall" column, C is "Grande" column and D is "Venti" column.

![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/00d0e46c-9f19-4066-a2f7-c223eeaaf4f5)

Question: What is the price of a Caffe Mocha, size Grande,Tall, Venti?

Answer: To find the answwer using following formula,

=VLOOKUP(A25,$A$4:$D$13,MATCH(B25,$A$4:$D$4,0)), where A is "classic favorite column", B is "Tall" column,  and D is "Venti" column.


![image](https://github.com/sarojinisarkar/Excel-exercises-with-solutions/assets/151612374/2afc0322-b80c-4ae4-bbbc-9391f34bb514)









