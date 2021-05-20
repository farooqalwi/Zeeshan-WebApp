Title:Python
Date: 2017-12-03 10:20
Modified: 2018-12-05 19:30
Category: Programing languages
Tags:Programing languages
Authors:Muhammad Zeeshan
### Q: Write code for faulty calculator Which perform following functions ?
1. Multiplication
2. Addition
3. Subtrection
4. Decision
### It performs Following faults.
* 45 x 3 =555
* 56 + 9 =77
* 60 - 8 =22
* 56 / 4 =22
# Code:-
```
print("Enter Your Choice ")
opr = input("+,-,*,/ ")
if opr=='+':
    num1 = int(input("Enter First Number ="))
    num2 = int(input("Enter Second Number ="))
    if (num1==56 and num2==9):
        print("56+9=77")
    else:
        print(num1, "+", num2, "=", num1 + num2)
elif opr=='-':
    num1 = int(input("Enter First Number ="))
    num2 = int(input("Enter Second Number ="))
    if (num1==60 and num2==8):
        print("60-8 =22")
    else:
        print(num1,"-",num2,"=",num1-num2)
elif opr=='*':
    num1 = int(input("Enter First Number ="))
    num2 = int(input("Enter Second Number ="))
    if num1==45 and num2==3:
        print("45x3=555")
    else:
        print(num1,"*",num2,"=",num1*num2)
elif opr=='/':
    num1 = int(input("Enter First Number ="))
    num2 = int(input("Enter Second Number ="))
    if num1==56 and num2==6:
        print("56/6=4")
    else:
        print(num1,"/",num2,"=",num1/num2)
else:
    print("Mistake")
```
# Output:-
![Output](images\b.png)

