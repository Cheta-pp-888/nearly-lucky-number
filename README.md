# nearly-lucky-number
chetan=list(input())
sum=0
for i in range(len(chetan)):
    if ((chetan[i] == "4") or (chetan[i]=="7")):
        sum=sum+1

if  (sum==7) or (sum==4):
    print("YES")
else:
    print("NO")
