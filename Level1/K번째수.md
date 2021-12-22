# 링크
https://programmers.co.kr/learn/courses/30/lessons/42748
## 코드
```python
def solution(array, commands):
    answer = []
    for i, j, k in commands:
        answer.append(sorted(array[i-1:j])[k-1])
    return answer
```

### etc
