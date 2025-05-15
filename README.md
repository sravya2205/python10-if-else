'''write a program to check whether the person is eligible to vote by using if condition.
testcase:
input:23
output:eligible'''
person=int(input("enter the age:"))
if person>=18:
    print("eligible")

    '''print whether the num  is even and skip the condition if not'''
num=int(input("enter the number:"))
if num%2==0: print(num,"is a even number")
print("after condition exit")

'''program to determine the character entered by user,whether it is an alphabet,digit or space by using seperate if condition and predefined string funcions'''
s=input()
if s.isalnum():
    print("the user has entered the character")
if s.isdigit():
    print("the user has entered the digit")
if s.isspace():
    print("the user has entered the space")

    '''write a program to find the smallest of two numbers by using if-else condition;
where take a manual input from the user
a=-4
b=-99'''
a=int(input())
b=int(input())
if a<b:
    small=a
else:
    small=b
print("small value is",small)

'''write a program to enter a character from (atoz),if the entered character is in 
lowercase convert into uppercase'''
ch=input("enter any character from a-z")
if ch>='a' and ch<='z':
    ch=ch.lower()
    print("it is converted to lower case:",ch)
else:
    ch=ch.upper()
    print("it is converted to upper case",ch)

    '''check whether the given input is a leap year for 4 years and centurians by if-else'''
year=int(input("enter the year"))
if year%4==0 or year%100==0:
    print("it is leap year")
else:
    print("it is not leap year")

    str="india"
if str.isupper() or str.islower():
    str=str.title()
    print("it is converted to title case",str)
