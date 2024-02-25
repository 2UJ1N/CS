# CS
👩🏻‍💻 기술 면접에 대비해서 CS를 공부하고 그 내용을 정리합니다.

<br>

## 📌 목차

### 1️⃣ 자료구조(Data Structure)

- 배열 Array
- 연결 리스트 Linked List
- 벡터 Vector
- 스택 Stack
- 큐 Queue
- 그래프 Graph
- 트리 Tree
- 힙 Heap
- 맵 Map
- 셋 Set
- 해시 Hash
- 트라이 Trie
- B-Tree & B+Tree

### 2️⃣ 알고리즘(Algorithm)
- 거품 정렬 Bubble Sort
- 선택 정렬 Selection Sort
- 삽입 정렬 Insertion Sort
- 퀵 정렬 Quick Sort
- 병합 정렬 Merge Sort
- 힙 정렬 Heap Sort
- 기수 정렬 Radix Sort
- 계수 정렬 Count Sort
- 이분 탐색 Binary Search
- 해시 테이블 구현
- DFS & BFS
- 최장 증가 수열 LIS
- 최소 공통 조상 LCA
- 동적 계획법 Dynamic Programming
- 다익스트라 Dijkstra
- 비트마스크 BitMask

### 3️⃣ 운영체제
- 운영체제 소개
  - 운영체제 필요성
  - 운영체제 정의
  - 운영체제 역할
- 운영체제 구조
  - 커널
  - 시스템 호출
- 프로세스
  - 프로세스 개념
  - 프로세스 상태
  - 프로세스 제어 블록
  - 프로세스 문맥 교환
- 스레드
  - 스레드 개념
  - 멀티스레드의 구조
  - 멀티스레드의 장단점
  - 멀티 프로세스 VS 멀티 스레드
- CPU 스케줄링
  - 장기 스케줄링
  - 중기 스케줄링
  - 단기 스케줄링
- 스케줄링 알고리즘
  - FCFS
  - SJF
  - Round Robin
  - SRT
  - Priority scheduling
  - Multilevel Queue
  - Multilevel Feedback Queue
- 인터럽트
  - 인터럽트 개념
  - 동기적 인터럽트, 비동기적 인터럽트
  - 인터럽트 처리 과정
  - 인터럽트와 이중 모드
- 프로세스 동기화
  - 공유자원, 경쟁상태, 임계구역
  - 피터슨 알고리즘
  - 뮤텍스
  - 세마포어
  - 모니터
- 교착 상태(Deadlock)
  - 교착 상태 정의
  - 교착 상태 조건
  - 교착 상태 해결 방법
  - 식사하는 철학자 문제
- 메모리 관리
  - 메모리 관리 필요성
  - 고정 분할 방식
  - 가변 분할 방식
- 가상 메모리 개요
  - 가상 메모리 정의
  - 가상 메모리 필요성
  - 페이징 기법
  - 세그먼테이션 기법
- 가상 메모리 관리
  - 요구 페이징
  - 페이지 교체 알고리즘
    - FIFO
    - OPT
    - LRU
<br>
<br>

### 📁 패키지 구조

```
CS-study
    ├── database
    |   └── 01_관계형_데이터베이스.md
    |   └── ...
    |
    ├── network
    |   └── ...
    |
    ├── interview => 면접 질문 아카이빙
    |   ├── database_expected_question.md => 데이터베이스 면접 질문
    |   ├── os_expected_question.md
    |   └── ...
    ...
```



### 📍 커밋 및 PR

1. **커밋 메시지**

   ```
   커밋메세지: [카테고리] {커밋 메세지}
   ```
   ```
   docs: 파일 생성
   add: 파일 추가 - 이미지 파일 업로드
   chore: 파일 내부 수정
   rename: 파일명 수정
   fix: 오류 처리시
   ```

   - 작성 예시) `[OS] CPU 스케줄링 알고리즘`
   - 수정 예시) `rename: [OS] 이름 수정`
