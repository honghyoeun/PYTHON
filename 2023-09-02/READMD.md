**Q1**
````
x, y = 100, 200
print(x==y) # 출력결과 true 
````
**Q2**
````
while(True) :
  print('A')
  print('B')
  print('C')
  continue
  print('D') # A,B,C가 반복된다
````
**Q3**
````
a = ["대","한","민","국"]
for i in a:
 print(i)

#출력결과 : 대\n한\n민\n국
````

**Q4**
````
a = ["대","한","민","국"]
for i in a:
 print(i, end= "") # 출력결과 : 대 한 민 국
````
**Q5**
````
class arr:
 a = ["Seoul", "Kyeonggi", "Inchon", "Daejoen", "Daegu", "Busan"]
str = ''
for i in arr.a:
  str = str + i[0]
print(str) # 출력결과 : SKIDDB
````
