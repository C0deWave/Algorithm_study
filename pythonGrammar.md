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

파이썬 순열, 조합

    from itertools import permutations
    from itertools import combinations

        list(combinations(items, 2))
        
파이썬에서 중복 제거하는 방법

    len(set(answer))

파이썬 정규식 사용방법

    import re
        answer = re.match('[+]{1}82-10-[0-9]{4}-[0-9]{4}', phone_number)
        answer = re.fullmatch('[+]{1}82-10-[0-9]{4}-[0-9]{4}', phone_number)

파이썬 리스트 개수 세기

    from collections import Counter

    numbers = [1,1,2,2,3,3,3]
    # counter({1:2, 2:2, 3:3})
    counter = Counter(numbers)
    # 가장 큰 값 호출
    mostOne = counter.most_common(n=1)

파이썬 이진수로 변환

    num = 10
    binary = format(num,'b')
    print(binary)

