A = int(input("Enter the Marks of Hindi"))
B = int(input("Enter the Marks of English"))
C= int(input("Enter the Marks of Math"))
D = int(input("Enter the Marks of Science"))
E = int(input("Enter the Marks of SST"))
total = A+B+C+D+E
per = total/5
Z = "Grade"
if per>=90:
    Z="A"
elif per<90 and per>=80:
    Z = "B"
elif per<80 and per>=35:
    Z = "C"
else:
    Z="Fail"    
print("Your Marks are",total)    
print("Your Percentage is",per)
print("Your Grade is",Z)    

