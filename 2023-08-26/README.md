**Q10**
````
<<소스 코드>>
a = 10 # int 정숫값
b = 'text' # float 실숫값, str 문자 또는 문자열
print(type(a)) # a는 int형 
print(type(b)) # b는 str형

<<출력 결과>>
<class '__1__'> // int
<class '__2__'> // str
````

**Q11**
````
def f(n):
    return lambda a: a * n

k = f(3)  # 함수 f에 인자 3을 전달하여 람다 함수 k를 생성

print(k(10))  # 람다 함수 k에 인자 10을 전달하여 실행하고 결과 출력
````

**Q12**
````
def af(a, b): # 4, 5 입력
    return a + b 

def sf(a, b):
    return a - b

print(str(af(4, 5) * 6)) # 54 출력

````
