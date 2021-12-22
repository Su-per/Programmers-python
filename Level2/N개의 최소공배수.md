# 링크
https://programmers.co.kr/learn/courses/30/lessons/12953

## 코드
```python
def solution(arr):
    n = 1
    while True:
        if sum([n%i for i in arr]) == 0:
            return n
        n+=1
```

### etc
