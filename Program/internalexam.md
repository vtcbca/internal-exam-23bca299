### 9. Create text file on python by taking input from user. Read Python.txt file and Print it in Reverse. 


```python
f=open("D:\\23BCA299\\data\\python.txt","w")
```


```python
line=[]
```


```python
while True:
    l=input()
    if l:
        line.append(l+"\n")
    else:
        break
text="\n".join(line)
```

     python is a programming language
     python is an interprited language
     python is very easy language
     python is a object-oriented language
     
    


```python
f.write(text)

```




    136




```python
f.close()
```


```python
f=open("D:\\23BCA299\\data\\python.txt","r")
```


```python
file_content=f.read()
```


```python
f.close()
```


```python
reversed_content=file_content[::-1]
print(reversed_content)
```

    
    egaugnal detneiro-tcejbo a si nohtyp
    
    egaugnal ysae yrev si nohtyp
    
    egaugnal detirpretni na si nohtyp
    
    egaugnal gnimmargorp a si nohtyp
    


```python

```
