#Approach-1
n=int(input())
a=[]
for i in range(n):
  x=int(input())
  a.append(x)
print(a)
#Approach-2
n=int(input())
a=[]
for i in range(n):
  x=int(input())
  a.insert(0,x)
print(a)
#Approach-3
n=int(input())
a=list(map(int,input().split()))
print(a)

