z=int(input())
flag=0

for a in range (2,z):
    if z%a==0:
        flag=1
        break
if (flag==1):
    print("Non Prime")
else:
    print("Prime")
        
