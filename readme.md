# Program 7: write a function that accepts two string and returns the indices of all the occurences of the second string in the first string as a list. if the second string is not present in present in first string then it should return -1.
def occurances(a,b):
<br>
    newlist=[]
    <br>
    if b not in a:
    <br>
        print(-1)
        <br>
    else:
    <br>
        i=0
        <br>
        while i<len(a):
        <br>
            c=a.find(b,i)
            <br>
            if c==-1:
            <br>
                break
                <br>
            i=c+len(b)
            <br>
            newlist.append(c)
            <br>
        print(newlist)
        <br>
a=input("enter first string ;")
<br>
b=input("enter second string ;")
<br>
occurances(a,b)
![image](https://github.com/user-attachments/assets/441cdbe2-9d71-4fd2-bade-15ba218e3168)




