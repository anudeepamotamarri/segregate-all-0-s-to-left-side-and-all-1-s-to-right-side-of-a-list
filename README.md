# segregate-all-0-s-to-left-side-and-all-1-s-to-right-side-of-a-list 
x=input()
li=x.split()
print(li)
y=[]
for i in li:
    if i=='1':
        y.append(int(i))
    else:
        y.insert(int(i),0)
print(y)        
