# Erstes Projekt EF5
---

```
z=input(" gib zahl z ein")
while z !=0:
    if isInteger (z/2):
        z/=2
        print "0"
    else:
        z-=1
        z/=2
        print "1"
```
h=[]
v=[0,1,2,3,4,5,6,7,8,9,"A","B","C","D","E","F"]
y=input("gib die selbe zahl z nochmal ein")
print"Deine Zahl im Hexadezimalsystem ist:"
while y >0:
rest= y % 16
t =v[rest]
h.append(t)
y=y//16
res= h[::-1]
print res
```

2Programme aus dem Grundlagen-Script.