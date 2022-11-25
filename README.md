# SUNIL_-KOC29-_CipherSchools
PYTHON PROJECT 1 METHOD
# To print multiplication table using OOPs

class MultiplyTable():
    description="Generates Multiplication table"
    def table(n):
        for i in range(2,n+1): 
          # For every number between 2 and n
            print("\nMultiplication table for %d\n"%i)
            for j in range(1,11):
                print("%d x %d = %d"%(i,j,i*j))

val=int(input("Enter the value for the table :"))

print(" ------------------------ ")

MultiplyTable.table(val)

    **********************************************************************************************************************************************************************
**********************************************************************************************************************************************************************  

PYTHON PROJECT 2 METHOD
# Using for loop
n = int(input("Enter number: "))
for i in range(1,n+1):
    print("MULTIPLICATION TABLE FOR",(i))
    for j in range(1,11):
        print(i, 'x', j, '=', i*j)
        
        
                                            
                                            
                                            
                                            ##****************************##
