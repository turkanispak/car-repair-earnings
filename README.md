# car-repair-earnings
 A C program to calculate the daily car repair earning of a company.
 
 
Write a C program to calculate the daily car repair earning of a company. The following information is inputted by an employee for each customer: • A character for the type of vehicle: ‘C’ for car, ‘B’ for bus, ‘T’ for truck. • An integer between 0 and 24 for the hour of arrival. • An integer between 0 and 60 for the minute of arrival. • An integer between 0 and 24 for the hour of departure. • An integer between 0 and 60 for the minute of departure. • A character for the Type of repair (T: Tire change/repair, L: Oil Change, M: Mechanical repair, O:Other) 
The management uses two different rates for each type of vehicle, shown in the Table.
Vehicle Oil Change Rate (TL) Tire Change Rate (TL) Other repairs (TL) 
CAR     120                  80                     500 
TRUCK   150                  100                    700 
BUS     200                  150                    1000 
 
Mechanical repair Rate (TL) 
 
Simple 200/hr Complex 500/hr 
 
These rates are base rates for the repair. On top of these labor cost will be added which is 20TL/hr.  Vehicles stay at the repair shop daily.  Your program must prompt the user to enter each piece of data as shown below for each customer until E is inputted. For each customer amount to be paid should be calculated and displayed. At the end of the day total income of the company is displayed on the screen. (For mechanical repair, input type of the repair as well (S for simple, C for complex)) 
 
 
 
 
 
The output format is shown below for each customer. 
 
 
 
 
 
 
 
Sample Run: 

Input I for inputting arrival and departure time or E to exit: I 
Input Type of vehicle ? C 
Input Hour vehicle arrived ( 0 - 24 ) ? 14 
Input Minute vehicle arrived ( 0 - 60 ) ? 23 
Input Hour vehicle left ( 0 - 24 ) ? 16 
Input Minute vehicle left ( 0 - 60 ) ? 23 
Inut Type of the maintenance (T: Tire change/repair, L: Oil Change, M: Mechanical repair, O:Other): T 
---------- 
Type of vehicle : Car  
TIME-IN                    14 : 23 
TIME-OUT                16: 23 
Total Time:        2.00 hours 
 ------------ 
TOTAL CHARGE FOR CUSTOMER  80.00 TL + 40TL labor= 100TL 
********** 
Input I for inputting arrival and departure time or E to exit: E 
Total Daily Income:  12456.87 TL 
BYE 

 
