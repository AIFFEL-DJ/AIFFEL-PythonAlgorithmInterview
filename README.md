# AIFFEL 대전 - 파이썬 알고리즘 인터뷰

[AIFFEL 대전](https://aiffel.io/aiffel-dj/)의 퍼실끼리 [파이썬 알고리즘 인터뷰](https://github.com/onlybooks/algorithm-interview)의 문제들을 스터디하고 정리하였습니다.

### 스터디 방식
1. 각자 맡은 문제를 공부한다.
2. 풀이 코드에서 설명이 부족한 부분에 주석을 추가하여 깃헙에 공유한다.
3. 스터디에서 깃헙에 공유한 내용을 토대로 팀원들에게 설명한다.

## 1학기 (자료구조)

### 4장. 빅오, 자료형 이론
(생략)

### 6장. 문자열 조작
Prob 1. 유효한 팰린드롬
- [Sol 1. 리스트로 변환](./ch6/p1_s1.py)
- [Sol 2. 데크 자료형을 이용한 최적화](./ch6/p1_s2.py)
- [Sol 3. 슬라이싱 사용](./ch6/p1_s3.py)
- Sol 4. C 구현(생략)

Prob 2. 문자열 뒤집기
- [Sol 1. 투 포인터를 이용한 스왑](./ch6/p2_s1.py)
- [Sol 2. 파이썬다운 방식](./ch6/p2_s2.py)

Prob 3. 로그 파일 재정렬
- [Sol 1. 람다와 +연산자를 이용](./ch6/p3_s1.py)

Prob 4. 가장 흔한 단어
- [Sol 1. 리스트 컴프리헨션, Counter 객체 사용](./ch6/p4_s1.py)

Prob 5. 그룹 애너그램
- [Sol 1. 정렬하여 딕셔너리에 추가](./ch6/p5_s1.py)
- [Sol 2. set을 이용(커스텀)](./ch6/p5_s2.py)

Prob 6. 가장 긴 팰린드롬 부분 문자열
- [Sol 1. 중앙을 중심으로 확장하는 풀이](./ch6/p6_s1.py)


### 7장. 배열

Prob 7. 두 수의 합
- [Sol 1. 브루트 포스로 계산](./ch7/p7_s1.py)
- [Sol 2. in을 이용한 탐색](./ch7/p7_s2.py)
- [Sol 3. 첫번째 수를 뺸 결과 키 조회](./ch7/p7_s3.py)
- [Sol 4. 조회 구조 개선](./ch7/p7_s4.py)
- [Sol 4. 투 포인터 이용(커스텀)](./ch7/p7_s5.py)

Prob 8. 빗물 트래핑
- [Sol 1. 투 포인터를 최대로 이동](./ch7/p8_s1.py)
- [Sol 2. 스택 쌓기](./ch7/p8_s2.py)

Prob 9. 세 수의 합
- [Sol 1. 브루트 포스로 계산](./ch7/p9_s1.py)
- [Sol 2. 투 포인터로 합 계산](./ch7/p9_s2.py)

Prob 10. 배열 파티션 1
- [Sol 1. 오름차순 풀이](./ch7/p10_s1.py)
- [Sol 2. 짝수 번째 값 계산](./ch7/p10_s2.py)
- [Sol 3. 파이썬다운 방식](./ch7/p10_s3.py)

Prob 11. 자신을 제외한 배열의 곱
- [Sol 1. 왼쪽 곱셈 결과에 오른쪽 값을 차례대로 곱셈](./ch7/p11_s1.py)

Prob 12. 주식을 사고팔기 가장 좋은 시점
- [sol 1. 브루트 포스로 계산](./ch7/p12_s1.py)
- [sol 2. 저점과 현재 값과의 차이 계산](./ch7/p12_s2.py)
- [sol 3. 커스텀](./ch7/p12_s3.py)


### 8장. 연결 리스트

Prob 13. 팰린드롬 연결 리스트
- [Sol 1. 리스트 변환](./ch8/p13_s1.py)
- [Sol 2. 데크를 이용한 최적화](./ch8/p13_s2.py)
- Sol 3. 고(Go)를 이용한 데크 구현(생략)
- [Sol 4. 런너를 이용한 우아한 풀이](./ch8/p13_s3.ipynb)

Prob 14. 두 정렬 리스트의 병합
- [Sol 1. 재귀 구조와 연결](./ch8/p14_s1.py)

Prob 15. 역순 연결 리스트
- [Sol 1. 재귀 구조로 뒤집기](./ch8/p15_s1.py)
- [Sol 1. 반복 구조로 뒤집기](./ch8/p15_s2.py)


Prob 18. 홀짝 연결 리스트
- [Sol 1. 반복 구조로 홀짝 노드 처리](./ch8/p18_s1.py)


Prob 19. 역순 연결 리스트 2
- [Sol 1. 반복 구조로 노드 뒤집기](./ch8/p19_s1.py)


### 9장. 스택, 큐

Prob 20. 유효한 괄호
- [Sol 1. 스택 일치 여부 판별](./ch9/p20_s1.py)

Prob 21. 중복 문자 제거
- [Sol 1. 재귀를 이용한 분리](./ch9/p21_s1.py)
- [Sol 2. 스택을 이용한 문자 제거](./ch9/p21_s2.py)

Prob 22. 일일 온도
- [Sol 1. 스택 값 비교](./ch9/p22_s1.py)

Prob 23. 큐를 이용한 스택 구현
- [Sol 1. push()할 때 큐를 이용해 재정렬](./ch9/p23_s1.py)

Prob 24. 스택을 이용한 큐 구현
- [Sol 1. 스택 2개 사용](./ch9/p24_s1.py)

Prob 25. 원형 큐 디자인
- [Sol 1. 배열을 이용한 풀이](./ch9/p25_s1.py)
