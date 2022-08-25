# odd-pairs
t=int(input())
for i in range(t):
    n=int(input())
    if n%2==0:
        e=n//2
        k=e*n
        print(k)
    else:
        e=n//2
        k=e*n
        j=k+e
        print(j)
        
