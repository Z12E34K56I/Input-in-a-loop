# Input-in-a-loop
count=0

total=0

while count < 3:

      num=int(input("Enter a subject score:"))
      
      total+=num
      
      count+=1

print(f"The final score is {total}.")

count=0

wins=0

losses=0

while count<=6:

     result=input("Enter the result("WIN or LOSSES:)")unpper()

     if result=="W":

        wins+=1

     elif result=="L":

           losses+=1

           count+=1

radio=wins/losses
print(f"The win/loss ratio is {ratio}." )
