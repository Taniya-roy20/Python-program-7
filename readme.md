# Program 7: write a function that accepts two string and returns the indices of all the occurences of the second dtring in the first string as a list. if the second string is not present in present in first string then it should return -1.
code= def occurances(a,b):
newlist=[]
    
if b not in a:
    print(-1)
else:
    i=0
    while i<len(a):
        c=a.find(b,i)
        if c== -1:
         break
        i= c+ len(b)
        newlist.append(c)
        print(newlist)
            
a=input("enter first string;")
b=input("enter second string;")
occurances(a,b)



