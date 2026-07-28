#find the index value
l=list(map(int, input("enter the values:").split()))
n=int(input("enter a number:"))
for i in range(len(l)):
    for j in range(i+1,len(l)):
        if l[i]+l[j]==n:
            print(i,j)
            break
