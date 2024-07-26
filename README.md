# 7-accecode
'''write a program that promts the user to enter a number between 1 to 7 which are assigned to the corresponding days of a week , where elif is complicatedly repeated till the condition satisfies 
condition : num1 = sunday ,num2 = monday ,......num7 = satursday.
if input is out of range print wrong input 
test case 1:
input :enter any number between 1 to 7: 5
output: Thursday
test case 2:
 input: any number between 1 to 7: 9
 output: Wrong input'''
 
--------------------------------------------------------------------------------
num=int(input("enter any number between 1 to 7:"))
if num==1:print("Sunday")
elif num==2:print("Monday")
elif num==3:print("Tuesday")
elif num==4:print("wednasday")
elif num==5:print("Thursday")
elif num==6:print("Friday")
elif num==7:print("Saturday")
else: print("Wrong input")
