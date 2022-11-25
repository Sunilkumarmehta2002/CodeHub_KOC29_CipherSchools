# SUNIL_-KOC29-_CipherSchools
PYTHON PROJECT 1 METHOD
#To print multiplication table using OOPs

class MultiplyTable():
    description="Generates Multiplication table"
    def table(n):
        for i in range(2,n+1): 
          # For every number between 2 and n
            print("\nMultiplication table for %d\n"%i)
            for j in range(n+1):
                print("%d x %d = %d"%(i,j,i*j))

val=int(input("Enter the value for the table :"))

print(" ------------------------ ")

MultiplyTable.table(val)


********************************************************************************************************************************************************************
********************************************************************************************************************************************************************

PYTHON PROJECT 2 METHOD
# using while loop
i = int(input(" Please Enter any Positive Integer less than n : "))


while(i <= 20):
    j = 1
    while(j <= 20):
        print('{0}  *  {1}  =  {2}'.format(i, j, i*j))
        j = j + 1
    print('------------------')
    i = i + 1
