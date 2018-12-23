

```python
from tkinter import *
```


```python
def f1():
    print("나를 호출했군요..")
    print("내가 실행될 코드입니다..")
    
f1()
```

    나를 호출했군요..
    내가 실행될 코드입니다..
    


```python
def f2():
    print("나는 f2입니다.")
    print("내가 실행될 코드입니다..")
  
def f3():
    print("나는 f3입니다.")
    print("내가 실행될 코드입니다..")
    
    
f2()
print()
f3()
```

    나는 f2입니다.
    내가 실행될 코드입니다..
    
    나는 f3입니다.
    내가 실행될 코드입니다..
    


```python
def call(event): #event 자리에는 아무것이나 넣어도 됨
    print("버튼을 누르셨군요.")
    a = 100
    b = 200
    print(a+b)


w = Tk()
w.configure(bg="white")
b = Button(w, text="합계를 구해주세요.")
b.pack()

b.bind("<Button-1>", call) #버튼을 한 번 누르면 앞쪽의 call 함수를 호출한다는 의미



w.mainloop()
```

    버튼을 누르셨군요.
    300
    


```python

```
