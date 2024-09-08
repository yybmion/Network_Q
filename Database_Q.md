# 데이터베이스 면접 질문 정리

## 목차
1. [기본 개념](#item01)
2. [SQL](#item02)
3. [인덱스](#item03)
4. [정규화](#item04)
5. [트랜잭션과 동시성 제어](#item05)

## Item01: 기본 개념 <a name="item01"></a>

1. 파일시스템과 데이터베이스의 차이점
2. 데이터베이스의 특징
3. DBMS의 정의와 특징
4. 스키마의 개념
5. 3단계 데이터베이스 구조
6. 데이터 독립성
7. RDBMS(관계형 데이터베이스 관리시스템)
8. 릴레이션 스키마와 릴레이션 인스턴스
9. 릴레이션의 차수와 카디널리티
10. 키(Key)의 종류와 특징
    - 슈퍼키, 후보키, 기본키, 대리키, 외래키
11. 무결성 제약조건
    - 도메인 무결성, 개체 무결성, 참조 무결성
12. 다양한 데이터베이스 시스템
    - 오라클DB, MySQL, MariaDB, MongoDB 등
13. MySQL 엔진
14. InnoDB

## Item02: SQL <a name="item02"></a>

1. SQL의 특징과 프로그래밍 언어와의 차이
2. SQL 실행 과정
3. DML / DDL / DCL
4. 참조 무결성
5. CASCADE 설정
6. VIEW
7. SELECT 절의 처리순서
8. SELECT ~ FOR UPDATE 구문
9. GROUP BY절
10. ORDER BY절
11. INNER JOIN과 OUTER JOIN의 차이
12. LEFT OUTER JOIN, RIGHT OUTER JOIN
13. CROSS JOIN
14. 서브쿼리
15. DROP, TRUNCATE, DELETE의 차이
16. DISTINCT
17. SQL Injection과 예방 방법
18. SQL 안티패턴
19. 페이지네이션 구현 방법

## Item03: 인덱스 <a name="item03"></a>

1. 랜덤 I/O와 순차 I/O
2. 인덱스의 개념과 동작 방식
3. 인덱스 설정 기준
4. 인덱스 개수와 성능의 관계
5. 커버링 인덱스(Covering index)
6. 다중 컬럼 인덱스(Multi-column index, 복합 인덱스)
7. B-Tree 인덱스와 B+Tree 인덱스
8. Hash 인덱스
9. 클러스터링 인덱스
10. 인덱스 스캔 방식
11. 쿼리 실행 계획
12. 쿼리 힌트
13. 인덱스 성능 확인 방법 -> 인덱스가 잘 동작하고 있는지 어떻게 확인할 수 있을까요?
14. 인덱스 사용시 주의사항
15. GROUP BY와 인덱스
16. 복합 인덱스 설계 예시 (이름, 국가, 성별) -> 이름, 국가, 성별이 있는 테이블에서 인덱스를 어떻게 걸어야할까요?

## Item04: 정규화 <a name="item04"></a>

1. 이상 현상의 개념
2. 삽입 이상(Insertion Anomaly)
3. 갱신 이상(Update Anomaly)
4. 삭제 이상(Deletion Anomaly)
5. 함수 종속성
6. 완전 함수적 종속
7. 부분 함수적 종속
8. 이행 함수적 종속
9. 제 1 정규형 (1NF)
10. 제 2 정규형 (2NF)
11. 제 3 정규형 (3NF)
12. BCNF 정규형
13. 반정규화
14. 유일성과 최소성 개념

## Item05: 트랜잭션과 동시성 제어 <a name="item05"></a>

1. DB 세션
2. Commit (업데이트 확정)
3. Rollback (업데이트 취소 처리)
4. Auto Commit 설정
5. 트랜잭션의 개념
6. 트랜잭션의 ACID 특성
7. 트랜잭션 격리 수준
8. READ UNCOMMITTED 격리 수준
9. READ COMMITTED 격리 수준
10. REPEATABLE READ 격리 수준
11. SERIALIZABLE 격리 수준
12. DB 동시성 제어(병행제어)
13. 갱신 손실 문제
14. DB 락 (Database Lock)
15. DB 데드락
16. DB 회복
17. REDO, UNDO
18. 체크포인트 회복 기법
19. MySQL InnoDB의 기본 트랜잭션 격리 수준