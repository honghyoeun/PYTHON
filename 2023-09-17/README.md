## 예제

1. **Hello World 출력하기**:

```python
print("Hello, World!")
```

2. **변수와 연산**:

```python
# 변수 할당
x = 5
y = 3

# 연산 수행
sum_result = x + y
product_result = x * y

# 결과 출력
print("합계:", sum_result)
print("곱셈 결과:", product_result)
```

3. **조건문 사용 (if문)**:

```python
age = 18

if age >= 18:
    print("당신은 성인입니다.")
else:
    print("당신은 미성년자입니다.")
```

4. **반복문 사용 (for문)**:

```python
fruits = ["사과", "바나나", "체리"]

for fruit in fruits:
    print(fruit)
```

5. **함수 정의**:

```python
def greet(name):
    print("안녕하세요, " + name + "님!")

greet("Alice")
greet("Bob")
```

6. **리스트 조작**:

```python
numbers = [1, 2, 3, 4, 5]

# 리스트 순회
for number in numbers:
    print(number)

# 리스트에 새로운 요소 추가
numbers.append(6)

# 리스트 슬라이싱
subset = numbers[2:4]
```

7. **사용자 입력 받기**:

```python
name = input("이름을 입력하세요: ")
print("안녕하세요, " + name + "님!")
```

8. **예외 처리 (try...except)**:

```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("0으로 나눌 수 없습니다.")
```

이 예제들은 Python의 기본 문법 및 기능을 보여주는 것이며, Python은 다양한 영역에서 사용되는 다양한 라이브러리와 기능을 제공합니다. Python을 사용하여 데이터 분석, 웹 개발, 인공 지능 및 기계 학습, 게임 개발 등 다양한 분야에서 프로그래밍을 할 수 있습니다.
