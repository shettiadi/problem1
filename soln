import itertools

length=input()
length=10
list1=[''.join(x) for x in itertools.product('AP', repeat=length)]

list2=[]
for x in list1:
    #print("for"+x)
    if x.find('AAAA')>-1:
        #print(x)
        pass
    else:
        list2.append(x)

b=len(list2)        
count=0
for y in list2:
    if y[-1]=='A':
        #print('yes')
        count+=1
        list2.remove(y)
a=count     

print(f"{a}/{b}")
