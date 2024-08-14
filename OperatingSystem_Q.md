## Item01
운영체제
시분할 시스템(time-sharing system)
다중 프로그래밍 시스템(multi-programming system)
일괄처리 시스템(Batch system)
대화형 시스템(interactive system)
다중 처리기 시스템(multi-processor system)
시스템 콜(System Call)과 커널(Kernel)
커널모드와 유저 모드
폴링
인터럽트 
입출력(I/O) 제어 방식
직접 메모리 접근(Direct Memory Access, DMA)
동기식 I/O와 비동기식 I/O

## Item02
프로그램(Program)
프로세스(Process)
프로세스 문맥 (Process Context)
문맥 교환(Context switch)
프로세스의 메모리 공간
프로세스 제어 블록(PCB)
멀티 프로세스(Multi Process)
프로세스 수행 상태 변화 과정
프로세스끼리 협력하는 방법(IPC)
fork() 명령어
쓰레드
쓰레드의 메모리 공간
쓰레드 제어 블록(TCB)
사용자 수준 쓰레드(User Thread)
커널 수준 쓰레드(Kernel Thread)
멀티 쓰레드 프로그래밍(Multi Thread)
멀티 쓰레드 vs 멀티 프로세스
Thread-Safe (의미, 이렇게 설계하는 방법)
프로세스 vs 쓰레드

## ITem03
기아 상태(Starvation)
CPU 스케줄링
선점형 스케줄링 vs 비선점형 스케줄링
선입선출 스케줄링(FCFS, First-Come-First-Service)
라운드 로빈 스케줄링(RR, Round-Robin)
최단 작업 우선 스케줄링(SJF, Shortest-Job-First)
최소 잔류 시간 우선 스케줄링(SRTF, Shortest Remaining Time First)
최상 응답 비율 순서 스케줄링(HRRN, High-Response-Ratio-Next)
우선순위 스케줄링(Priority scheduling)
멀티 레벨 큐 스케줄링(MLQ, Multi-level Queue)
멀티 레벨 피드백 큐 스케줄링(MFQ, Multi-level Feedback Queue)

## Item04
병행성/동시성 (Concurrency)
병렬성 (Parallelism)
프로세스 동기화(Synchronization)
임계 영역(Critical Section)
경쟁 상태(Race Condition)
상호 배제(Mutual Exclusion)
뮤텍스(Mutex)
세마포어(Semaphore)
뮤텍스 vs 세마포어
모니터(Monitor)
교착 상태(Deadlock)

## Item05
절대 주소 지정 vs 상대 주소 지정
내부 단편화(Internal Fragmentation)
외부 단편화(External Fragmentation)
메모리 관리(Memory Management)
반입 기법
메모리 배치 기법
메모리 할당 기법
연속 할당 기법(Contiguous Memory Allocation)
불연속/분산 할당 기법(Non-contiguous Memory Allocation)
외부 단편화 해결 방법
가상 메모리(Virtual Memory)
가상 주소와 물리 주소
페이지 교체 기법
FIFO(First-In-First-Out: 선입선출)
LRU(Least Recently Used)
LFU(Least Frequently Used)
Clock Algorithm
쓰레싱(Thrashing) - 문제점
워킹 셋(Working Set) - 쓰레싱 해결 방안 1
페이지 부재 빈도(PFF, Page Fault Frequency) - 쓰레싱 해결 방안 2


// https://dev-cheddung.tistory.com/61