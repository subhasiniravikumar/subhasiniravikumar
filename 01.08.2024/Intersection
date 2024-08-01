n=int(input())
n1=set(map(int,input().split()))
m=int(input())
for i in range(m):
    se=list(map(str,input().split()))
    el=set(map(int,input().split()))
    if se[0]=="intersection_update":
        n1.intersection_update(el)
    elif se[0]=="symmetric_difference_update":
        n1.symmetric_difference_update(el)
    elif se[0]=="difference_update":
        n1.difference_update(el)
    elif se[0]=="update":
        n1.update(el)
print(sum(n1))
