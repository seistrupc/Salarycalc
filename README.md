# Salarycalc
A simple program to estimate potential hourly income

Here are a list of equations and variables that I will use for the program
Hourly pay = P
Weekly Hours = H

//weekly pay = W
If h<=40, H*P
else P*40 + ((H%40)*1.5)*P

//Monthly Pay = M
(W*52)/12

//Yearly Pay = Y
M*12

print W, M, Y

//taxes
W*.75 = TW
M*.75 = TM
Y*.75 = TY

print TW, TM, TY
