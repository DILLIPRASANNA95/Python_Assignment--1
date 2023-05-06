# Python_Assignment--1

# program to display the fibonacci sequence up to n-th term
nterm = int(input(" how many terms?"))
# first two terms
n1, n2 =0, 1
count =0
# check if the numnber of terms is valid
if nterms <= 0:
print(" please enter a positive integer")
# if there is only one term, return n1
elif nterms == 1:
print ("fibonacci sequence upto",nterms,":")
print (n1)
#generate fibonacci sequence
else:
print("fibonacci sequence:")
while count < nterms:
print(n1)
nth = n1 +n2
#update values
n1 = n2
n2 = nth
count += 1
