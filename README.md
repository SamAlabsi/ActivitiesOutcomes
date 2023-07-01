-1 Peer review assignment due July 03.
The below code need to be examined and checked if it is in accordance to PEP or not.
# ActivitiesOutcomes
#This function subtracts  2numbers
def subtract(x, y):
    return x - y



       #This function multipliers 2numbers
def multiply(x, y):
   return x * y

##This function divides  2numbers #
def divide(x, y):
   return x / y

print ( "Select operation.")
print ( "1.Add")
print ( "2.Subtract")
print ( "3.Multiply")
print ( "4.Divide")

while True:
   
   choice = input  ("Enter choice(1/2/3/4): ")# Take input from the  user

   # Check if choice is 1 of the four options by completing the following code in the IDE of your choice or notebook
   if choice in ('1', '2', '3', '4'):
      Num1   = float(input("Enter first number: "))
      Num2   = float(input("Enter second number: "))

       if CHOICE == '1':
           print(Num1, "+", Num2, "=", add( Num1, Num2 ))

       elif CHOICE == '2':
           print (Num1, "-", Num2, "=", subtract( Num1, Num2 ))

       elif CHOICE == '3':
           print (Num1, "*", Num2, "=", multiply( Num1, Num2 ))

       elif CHOICE == '4':
           print (Num1, "/", Num2, "=", divide( Num1, Num2 ))
       break
   else:

       Print( "Invalid Input" )#this prints the invalid input....
