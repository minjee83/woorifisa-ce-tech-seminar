# Topic : 분산데이터베이스 설계

## 🌠 Team 구구구칠

|<img src="https://avatars.githubusercontent.com/u/87555330?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/55776421?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/71498489?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/82265395?v=4" width="150" height="150"/>|
|:-:|:-:|:-:|:-:|
|김민성<br/>[@minsung159357](https://github.com/minsung159357)|SeulGi_LEE<br/>[@seulg2027](https://github.com/seulg2027)|HanJH<br/>[@letsgojh0810](https://github.com/letsgojh0810)|구민지<br/>[@minjee83](https://github.com/minjee83)|

## 📌 선정이유
- 학부 과정에서 다루는 프로젝트들은 대개 단일 데이터베이스 환경에 국한되어 있습니다. 그러나 현업에서는 방대한 데이터를 안정적으로 관리하기 위해 분산 데이터베이스 아키텍처가 필수적이다.
특히 마이크로서비스 아키텍처의 확산과 글로벌 서비스의 증가로 인해, 분산 데이터베이스의 설계와 운영은 현대 시스템 아키텍처에서 핵심적인 과제다.
이에 단순한 CRUD 작업을 넘어, 실제 엔터프라이즈 환경에 적합한 효율적인 데이터베이스 설계 전략을 연구하고자 본 주제를 선정하게 되었다.

## ⚒️ 구현환경
```
Server : Docker

DB : postgreSQL
```
## 💡 준비기간
`2025.02.03` ~ `2025.02.10`

## 📚 기술세미나 목차
1. 분산 데이터베이스 개요
2. 파티셔닝 (Partitioning)
3. 샤딩 (Sharding)
4. 레플리케이션 (Replication)
5. 구현 예시
6. 비교 분석
7. Q&A
8. 멘토 피드백

## 📢 기술세미나 주요 내용
### 1. 분산 데이터베이스 개요  
- 분산 데이터베이스란?  
- 분산 데이터베이스를 사용하는 이유  
- CAP 이론

### 2. 파티셔닝 (Partitioning)  
- 파티셔닝이란?  
- 파티셔닝의 종류 
- 파티셔닝의 장점 및 단점  

### 3. 샤딩 (Sharding)  
- 샤딩이란?  
- 샤딩의 종류  
- 샤딩이 필요한 이유

### 4. 레플리케이션 (Replication)  
- 레플리케이션이란?  
- Master-Slave Replication  
- 장애 처리 - 페일오버 

### 5. 구현 예시
- 파티셔닝
- 샤딩
- 샤딩 + 레플리케이션 

### 6. 비교 분석  
- 해시 샤딩(Sharding) vs 파티셔닝(Partitioning)  
- 샤딩(Sharding) & 레플리케이션(Replication) 비교  

### 7. Q&A
#### ⁉️ 1개의 원본(마스터) 에 여러 레플리카 (슬레이브)가 존재할 때 이들 간의 sync 를 어떻게 맞추는지 궁금합니다.

🛡️ [답변] : <br>

#### ⁉️ 금융권에서는 어떤 분산데이터베이스 전략을 사용하는지 궁금하고 왜 그런지 알고 계시면 설명 부탁드립니다.

🛡️ [답변] : <br>

#### ⁉️ 조회 삽입 성능에서 파티셔닝이 우수하다고 했는데 B+트리와 같은 인덱스와 성능 비교시 어느 것이 우수하다고 비교가 될까요?

🛡️ [답변] : <br>

#### ⁉️ 구현 시 데이터베이스 중에 postgresql을 고른 이유와 다른 db와의 다른점이 있으면 알려주세요.

🛡️ [답변] : <br>

#### ⁉️ cap중에서 현대의 분산 시스템은 어떠한 요소를 최우선으로 설계하고 있나요?

🛡️ [답변] : <br>

#### ⁉️ master → slave IO 소요시간 그 사이 데이터는 유실되는건지, 재해복구 추가적인 방식은 없는지

🛡️ [답변] : <br>

#### ⁉️ Master node에 장애가 생기면 replication 이 어떻게 처리되나요?

🛡️ [답변] : <br>

#### ⁉️ 현업에서 왜 수평 분할 파티션을 더 많이 하는지 궁금합니다.

🛡️ [답변] : <br>

#### ⁉️ 비동기 방식의 레플리케이션에서 데이터의 일관성을 보장하는 해결책이 있을까요? 복제 지연에 대한 해결책이 있는지 궁금합니다.

🛡️ [답변] : <br>

### 8. 멘토 피드백
- 
---
