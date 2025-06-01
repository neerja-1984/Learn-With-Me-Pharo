1) Ordered Collecion

![alt text](image-13.png)

--------------------------------------------

2) Arrays ( literal arrays)

![alt text](image-14.png)

----------------------------------------------

3) Set

always removes dups 
therfore in line no. 5 : 

```smalltalk
s1 := Set with: (Set with: #(1 2 1)) with: (Set with: #(1 2 1)) with: 'Hello','Pharo' with: 69.

"(Set with: #(1 2 1)) was only added once"
```

![alt text](image-15.png)

-----------------------------------------------------------

4) Dictionary

![alt text](image-16.png)