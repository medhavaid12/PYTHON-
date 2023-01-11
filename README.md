# PYTHON-
UPES-OPEN-ASSIGNMENT-2-PYTHON
Q1.#function for nth fabonacci number
#1+1=2 1+2=3 3+5=8
fabon=int(int(input("number of terms:")))
n1,n2=0,1
count=0
if fabon<=0:
   print("please enter a positive integer")
   #if 1 term then the code will return 1
elif fabon==1:
   print("sequence upto", fabon, ":")
   print (n1)
else:
    print ("Fabonacci sequence:")
    while count<fabon:
      print(n1)
      nth=n1+n2
#values updated
      n1=n2
      n2=nth
      count+=1
#THIS WAS RUN BY MEDHA VAID
#SAPID:500107848
