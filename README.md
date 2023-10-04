#program to find the sum of first n natural numbers
#the requirements are
#n as parameter
#num as argument
#display the sum

#code
def sumsqures(n):
    sum=0
    for i in range(1,n+1):
        sum=sum+i
    print("the sum of first ",n,"natural numbers is :",sum)
    #function end here
#ask number from user
num=int(input("enetr the value for n:"))
#num is an argument referrimg to the value input by the user 
#function calling
sumsqures(num)
