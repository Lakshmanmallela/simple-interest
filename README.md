
# calculation of simple interest and finding the total amount
# calculations of simple interests
# defining a function
def simpleint():
    # Taking the inputs from users
    p = float(input("Enter the priciple amount: "))
    t = float(input("Enter the toatal time: "))
    r = float(input("Enter the rate of interest: "))
    #calculating the simple interest
    si = (p*r*t)/100
    totalamt = p+si
    #returning the result
    return p,r,t,si,totalamt

#function calling
res = simpleint()
print('*'*50)
print("calculation of simple interest")
print('*'*50)
print("Principle amount={}".format(res[0]))
print("Total time=",res[1])
print("rate of interest=",res[2])
print("simple interest={}".format(res[3]))
print("Total amount={}".format(res[4]))
print("*"*50)
print(res)

