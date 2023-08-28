**Q13**
````
a = 10
b = 15

# a와 b 중 작은 값을 m에 저장
if a > b:
    m = b
else:
    m = a

# m부터 1까지 역순으로 반복
for i in range(m, 0, -1):
    # a와 b 모두 i로 나누어 떨어지는지 검사
    if a % i == 0 and b % i == 0:
        print(i)  # a와 b의 최대 공약수 출력
        break  # 최대 공약수를 찾았으므로 반복 종료

````
**Q14**
````
temp = 0  # 임시로 값을 저장할 변수 초기화
min_index = 0  # 최솟값을 가리킬 인덱스 변수 초기화
a = [4, 2, 3, 5, 1]  # 주어진 리스트 a

# 리스트의 모든 요소에 대해 반복
for i in range(len(a)):
    min_index = i  # 현재 위치를 최솟값 인덱스로 설정

    # 현재 위치(i+1)부터 리스트의 끝까지 반복
    for j in range(i + 1, len(a)):
        if a[j] < a[min_index]:  # 현재 요소가 최솟값보다 작다면
            min_index = j  # 최솟값 인덱스를 업데이트
    
    # 최솟값 요소와 현재 요소 위치를 교환
    temp = a[min_index]
    a[min_index] = a[i]
    a[i] = temp

print(a)  # 정렬된 리스트 출력 [1,2,3,4,5] 출력

````
