# 알고리즘이란?
### 어떠한 문제를 해결하기 위해 정해 놓은 일련의 절차

세 정수의 최댓값 구하기


```python
# a, b, c에 정숫값을 입력받아 maximum으로 최댓값 찾기

print('세 정수의 최댓값 찾기')
a = int(input('정수 a : '))
b = int(input('정수 b : '))
c = int(input('정수 c : '))

maximum = a
if b > maximum : maximum = b
if c > maximum : maximum = c

print(f'최대값은 {maximum}입니다.') # f는 python 3.6 버전 이후로 나온 문법. .format과 같은 문법이다.
```

    세 정수의 최댓값 찾기
    정수 a : 10
    정수 b : 20
    정수 c : 30
    최대값은 30입니다.
    

<br>
위와 같이 한 문장씩 순서대로 처리되는 구조를 <strong>순차 구조</strong>라고 한다.
<br> if와 콜론(:) 사이 > <strong>조건식</strong>
<br> 조건식에 따라 실행 결과가 바뀜 > **select structure(선택구조)**
<br>

이때, input() 함수는 문자열로 반환하므로 입력한 데이터의 자료형은 문자열이다. 그래서 int()함수를 이용하여 10진수 정수형으로 변환하였다.
<br> > 형 변환(type conversion)

### 숫자 변환



```python
print('17')
print(type('17'))
print(int('17'))
print(type(int('17')))

```

    17
    <class 'str'>
    17
    <class 'int'>
    
