# simple_split
# Your code here
#Solution by Sachin Kumar Yadav 
n=int(input())
ele=input()
ele=ele.split(" ")
mid=n//2
list=[]
for i in ele:
    list.append(int(i))
list.sort()
s=list[0:mid]
t=list[mid:mid*2]
s=sum(s)
t=sum(t)
r=t-s
print(r)
