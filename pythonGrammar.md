파이썬 문법

dict 자동 생성 방법

    from collections import defaultdict

        dict = defaultdict(int)
        dict[key] += temp

파이썬 올림

    import math
        math.ceil(-3.14)    #결과는 -3
        math.ceil(3.14)     #결과는 4

파이썬 논리연산자

    if (a and b)
    if (a or b)

파이썬 배열을 0으로 초기화 하기

    zero = [0 for i in range(10)]

파이썬 배열의 최대 최소

    min(array)
    max(array)

파이썬 배열의 마지막 요소

    array[-1]

파이썬 힙큐 사용 방법

    import heapq
        heap = []
        heapq.heappush(heap, 50)
        //리스트를 힙큐로 변환
        heapq.heapify(heap2)
        result = 
        
파이썬 정렬 방법
    
    array.sort(key = lambda x:x[0]) # array.sort() 와 동일.

파이썬 제곱

    a**b

파이썬 리스트 항목마다 적용

    list(map(int, a))
    == int(a[0])...int(a[1])......