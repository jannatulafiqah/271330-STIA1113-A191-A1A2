# STIA1113-Assignment-1-2
Student info.
NAME        : NURUL JANNATUL AFIQAH BINTI AZHAN.
MATRIC NUM  : 271330
#introduction
#flowchart
#pseudocode

![flowchart](https://user-images.githubusercontent.com/55247821/68546001-698aa000-040d-11ea-8e78-46811466cf05.png)
![flowchart1](https://user-images.githubusercontent.com/55247821/68546005-714a4480-040d-11ea-815e-bb30f05a46a0.png)

Pseudocode.

1.	Start program.
2.	Get the carprice,downpayment,loanperiod,i=0,rate,balance=0,interest=0,interests,principals,prinsipal.
3.	If car price is less than 3000
4.	Display “error,must higher than 30000”.
5.	Else
6.	Get downpayment.
7.	Display “downpayment”.
8.	If downpayment is less equal than 0.
9.	Display “error,cannot be negative”.
10.	Else
11.	Get loanperiod.
12.	Display “loanperiod”.
13.	If loanperiod less equal than 5 or loanperiod greater equal than 9.
14.	Display “error,must between 8-6 years”.
15.	Else
16.	Get rate.
17.	Display “interest rate”.
18.	If rate less than 3 or rate greater than 7.
19.	Display “error,must between 4-6”.
20.	Else
21.	Compute the interest=(carprice-downpayment)*rate/100.
22.	Compute interests=interest.
23.	Compute principal=((carprice-downpayment)+(interest*loanperiod))/loanperiod.
24.	Compute principals=principal.
25.	Compute balance=(principal*loanperiod)-principal.
26.	Display “YEARS,PRINCIPAL,INTEREST,BALANCE”.
27.	While iless equal than loanperiod.
28.	Display I,principals,interests,balance.
29.	i++
30.	interests+=interest.
31.	principals+=principal.
32.	balance-=principal.
33.	End program.

