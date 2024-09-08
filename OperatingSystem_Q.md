# 운영체제 면접 질문 정리

## 목차
1. [운영체제 기본 개념](#item01)
2. [프로세스와 스레드](#item02)
3. [CPU 스케줄링](#item03)
4. [동기화와 병행성](#item04)
5. [메모리 관리](#item05)

## Item01: 운영체제 기본 개념 <a name="item01"></a>

1. 운영체제의 정의와 역할
2. 시분할 시스템(time-sharing system)
3. 다중 프로그래밍 시스템(multi-programming system)
4. 일괄처리 시스템(Batch system)
5. 대화형 시스템(interactive system)
6. 다중 처리기 시스템(multi-processor system)
7. 시스템 콜(System Call)과 커널(Kernel)
8. 커널모드와 유저 모드
9. 폴링(Polling)
10. 인터럽트(Interrupt)
11. 입출력(I/O) 제어 방식
12. 직접 메모리 접근(Direct Memory Access, DMA)
13. 동기식 I/O와 비동기식 I/O

## Item02: 프로세스와 스레드 <a name="item02"></a>

1. 프로그램(Program)
2. 프로세스(Process)
3. 프로세스 문맥 (Process Context)
4. 문맥 교환(Context switch)
5. 프로세스의 메모리 공간
6. 프로세스 제어 블록(PCB)
7. 멀티 프로세스(Multi Process)
8. 프로세스 수행 상태 변화 과정
9. 프로세스간 통신 방법(IPC)
10. fork() 시스템 콜
11. 스레드(Thread)
12. 스레드의 메모리 공간
13. 스레드 제어 블록(TCB)
14. 사용자 수준 스레드(User Thread)
15. 커널 수준 스레드(Kernel Thread)
16. 멀티 스레드 프로그래밍(Multi Thread)
17. 멀티 스레드 vs 멀티 프로세스
18. Thread-Safe (의미와 설계 방법)
19. 프로세스 vs 스레드

## Item03: CPU 스케줄링 <a name="item03"></a>

1. 기아 상태(Starvation)
2. CPU 스케줄링의 개념과 목적
3. 선점형 스케줄링 vs 비선점형 스케줄링
4. 선입선출 스케줄링(FCFS, First-Come-First-Service)
5. 라운드 로빈 스케줄링(RR, Round-Robin)
6. 최단 작업 우선 스케줄링(SJF, Shortest-Job-First)
7. 최소 잔류 시간 우선 스케줄링(SRTF, Shortest Remaining Time First)
8. 최상 응답 비율 순서 스케줄링(HRRN, High-Response-Ratio-Next)
9. 우선순위 스케줄링(Priority scheduling)
10. 멀티 레벨 큐 스케줄링(MLQ, Multi-level Queue)
11. 멀티 레벨 피드백 큐 스케줄링(MFQ, Multi-level Feedback Queue)

## Item04: 동기화와 병행성 <a name="item04"></a>

1. 병행성/동시성 (Concurrency)
2. 병렬성 (Parallelism)
3. 프로세스 동기화(Synchronization)
4. 임계 영역(Critical Section)
5. 경쟁 상태(Race Condition)
6. 상호 배제(Mutual Exclusion)
7. 뮤텍스(Mutex)
8. 세마포어(Semaphore)
9. 뮤텍스 vs 세마포어
10. 모니터(Monitor)
11. 교착 상태(Deadlock)

## Item05: 메모리 관리 <a name="item05"></a>

1. 절대 주소 지정 vs 상대 주소 지정
2. 내부 단편화(Internal Fragmentation)
3. 외부 단편화(External Fragmentation)
4. 메모리 관리(Memory Management) 기법
5. 반입 기법
6. 메모리 배치 기법
7. 메모리 할당 기법
8. 연속 할당 기법(Contiguous Memory Allocation)
9. 불연속/분산 할당 기법(Non-contiguous Memory Allocation)
10. 외부 단편화 해결 방법
11. 가상 메모리(Virtual Memory)
12. 가상 주소와 물리 주소
13. 페이지 교체 기법
    - FIFO(First-In-First-Out: 선입선출)
    - LRU(Least Recently Used)
    - LFU(Least Frequently Used)
    - Clock Algorithm
14. 쓰레싱(Thrashing) - 문제점
15. 워킹 셋(Working Set) - 쓰레싱 해결 방안 1
16. 페이지 부재 빈도(PFF, Page Fault Frequency) - 쓰레싱 해결 방안 2