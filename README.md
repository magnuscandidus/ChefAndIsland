# ChefAndIsland
# cook your dish here
t=int(input())
while t:
    x,y,x1,y1,d=map(int,input().split())
    a=x/x1
    b=y/y1
    c=min(a,b)
    if(c>=d):
        print("Yes")
    else:
        print("No")
    t-=1
