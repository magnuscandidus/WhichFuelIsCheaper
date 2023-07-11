# WhichFuelIsCheaper
# cook your dish here
t=int(input())
while t:
    x,y,a,b,k=map(int,input().split())
    if((x+(a*k))<(y+(b*k))):
        print("Petrol")
    elif((x+(a*k))>(y+(b*k))):
        print("Diesel")
    else:
        print("Same Price")
    t-=1
    
