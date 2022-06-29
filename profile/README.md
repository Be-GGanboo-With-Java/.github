# [최종보스 "자바" 레이드] 스터디 진행 방식

- 매주 화요일 23시 구글미팅으로 진행합니다.

- Java 심화 과정에 관하여 각자 발표 자료 준비 후 발표합니다.

- 해당하는 주차에 부여된 문제를 풀어온 후 풀이과정을 설명합니다.

---

## 2022년 07월 이후 변경 및 추가사항 공지

Java 뿐만 아니라 Java 를 활용한 FrameWork 까지 주제 범위 확장

스터디 모임 횟수 확장

<br>

| 화 (Theory)                                              | 목 (Java-Spring)                                                                        | 토 (Spring-DataBase) |
|---------------------------------------------------------|----------------------------------------------------------------------------------------|---------------------|
| 자바(Spring) 관련 이론,<br><br> 객체지향 사실과 오해, <br><br> 이펙티브 자바 | [박재성님 플레이그라운드 강좌](https://edu.nextstep.camp/c/9WPRB0ys/) 를 듣고 SUWIKI 테스트 코드 작성, 구현문제풀이 | QueryDSL            |

---

### 1주차 [220509 完]

|구분|내용|
|---|---|
|Java|OOP|
|Implementation 1|https://programmers.co.kr/learn/courses/30/lessons/12928|
|Implementation 2|https://programmers.co.kr/learn/courses/30/lessons/12926|

<br>

|발표자|발표자료 레포지토리 링크|
|---|---|
|JIWON-JEONG|https://velog.io/@john7645/OOP-%EA%B0%9D%EC%B2%B4%EC%A7%80%ED%96%A5-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D-%EC%99%80-PP-%EC%A0%88%EC%B0%A8%EC%A0%81-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D|
|Diger-King|https://github.com/MoveForword-Java/Diger-King/blob/main/src/Week1/ObjectOrientedProgramming.md|

---

### 2주차 [220516 完]

|구분|내용|
|---|---|
|Java|객체 생성과 소멸 시 내부 동작 과정, Iterator 와 foreach 의 차이점 (제네릭 타입연관지어 정리), Null 과 is empty 차이점  |
|Implementation 1|https://programmers.co.kr/learn/courses/30/lessons/12925|
|Implementation 2|https://programmers.co.kr/learn/courses/30/lessons/12922|

|발표자|발표자료 레포지토리 링크|
|---|---|
|JIWON-JEONG|https://velog.io/@john7645/%EA%B0%9D%EC%B2%B4-%EC%83%9D%EC%84%B1%EA%B3%BC-%EC%86%8C%EB%A9%B8-%EC%8B%9C-%EB%82%B4%EB%B6%80-%EB%8F%99%EC%9E%91-%EA%B3%BC%EC%A0%95, https://velog.io/@john7645/isEmpty-%EC%99%80-null, https://github.com/JIWEON-JEONG/Study/blob/master/src/com/company/iter_foreach/CompareIterForeach.java|
|Diger-King|https://github.com/MoveForword-Java/Diger-King/blob/main/src/Week2/CreateAndPerishObject.md, https://github.com/MoveForword-Java/Diger-King/blob/main/src/Week2/NullVsEmpty.md, https://github.com/MoveForword-Java/Diger-King/blob/main/src/Week2/IteratorVsForeach.md|

---

### 3주차 [220523 完]

|구분|내용|
|---|---|
|Java|JVM(MetaSpace(Method Area)) + 가비지 컬렉터|
|Implementation 1|https://programmers.co.kr/learn/courses/30/lessons/12919|
|Implementation 2|https://programmers.co.kr/learn/courses/30/lessons/12921|

|발표자|발표자료 레포지토리 링크|
|---|---|
|JIWON-JEONG|https://velog.io/@john7645/JVM-Specification-%ED%83%84%EC%83%9D%EB%B0%B0%EA%B2%BD, https://velog.io/@john7645/GC|
|Diger-King|https://diger-king.github.io/blog/JVM, https://github.com/MoveForword-Java/Diger-King/blob/main/src/Week3/GarbageCollector.md|

---

### 4주차 [220530 完]

|구분|내용|
|---|---|
|Java|JIT 컴파일러 + Java 빌드 과정|
|Implementation 1|https://programmers.co.kr/learn/courses/30/lessons/12917|
|Implementation 2|https://programmers.co.kr/learn/courses/30/lessons/12918|

|발표자|발표자료 레포지토리 링크|
|---|---|
|JIWON-JEONG|https://velog.io/@john7645/JIT-%EC%BB%B4%ED%8C%8C%EC%9D%BC%EB%9F%AC-IBM-doc|
|Diger-King|https://github.com/MoveForword-Java/Diger-King/blob/main/src/Week4/JIT-Compiler.md|

---

### 5주차 [220606 完]

|구분|내용|
|---|---|
|Java|컬렉션|
|Implementation 1|https://programmers.co.kr/learn/courses/30/lessons/12915|
|Implementation 2|https://programmers.co.kr/learn/courses/30/lessons/12916|

|발표자|발표자료 레포지토리 링크|
|---|---|
|JIWON-JEONG|https://github.com/JIWEON-JEONG/Study/tree/master/src/com/company/collection|
|Diger-King||

<br>

---

![img](https://www.fssaifoodlicense.com/wp-content/uploads/2016/09/How-to-Renew-Your-FSSAI-Food-License-legalraasta-800x366.jpg)

---

### <화요일> - 1주차 [22/07/05 예정]

| 구분           | 내용                                                                                                                                  |
|--------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Theory       | Gradle, jar, war                                                                                                                    |
| 객체지향의 사실과 오해 | 협력하는 객체들의 공동체, 이상한 나라의 객체                                                                                                           |
| 이펙티브 자바      | [아이템1. 생성자 대신 static 팩토리 메서드를 고려해 볼 것](https://www.youtube.com/watch?v=X7RXP6EI-5E&list=PLfI752FpVCS8e5ACdi5dpwLdlVkn0QgJJ&index=1) |

<br>

|발표자|발표자료 레포지토리 링크|
|---|---|
|JIWON-JEONG||
|Diger-King||

---

### <목요일> - 1주차 [22/07/07 예정]

| 구분           | 내용                                        |
|--------------|-------------------------------------------|
| Java-Spring  | UserDomain, EvaluateDomain 테스트 코드 작성 후 리뷰 |

<br>

|발표자|발표자료 레포지토리 링크|
|---|---|
|JIWON-JEONG||
|Diger-King||

---

### <토요일> - 1주차 [22/07/09 예정]

| 구분              | 내용                                                                                        |
|-----------------|-------------------------------------------------------------------------------------------|
| Spring-Database | [김영한님 강의](https://www.inflearn.com/course/Querydsl-%EC%8B%A4%EC%A0%84) <br> 수강 후 학습 내용 발표 |

<br>

|발표자|발표자료 레포지토리 링크|
|---|---|
|JIWON-JEONG||
|Diger-King||

---

### <화요일> - 2주차 [22/07/12 예정]

| 구분           | 내용                                                                                                                                  |
|--------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Theory       | final, static |
| 객체지향의 사실과 오해 |  |
| 이펙티브 자바      | [아이템2. 생성자 매개변수가 많을 땐 빌더 패턴 사용해보기]https://www.youtube.com/watch?v=OwkXMxCqWHM&list=PLfI752FpVCS8e5ACdi5dpwLdlVkn0QgJJ&index=2&t=750s) |

<br>

|발표자|발표자료 레포지토리 링크|
|---|---|
|JIWON-JEONG||
|Diger-King||

---

### <목요일> - 2주차 [22/07/14 예정]

| 구분           | 내용                                        |
|--------------|-------------------------------------------|
| Java-Spring  | userAdminDomain, ExamDomain 테스트 코드 작성 후 리뷰 |

<br>

|발표자|발표자료 레포지토리 링크|
|---|---|
|JIWON-JEONG||
|Diger-King||

---

### <토요일> - 2주차 [22/07/16 예정]

| 구분              | 내용                                                                                        |
|-----------------|-------------------------------------------------------------------------------------------|
| Spring-Database | [김영한님 강의](https://www.inflearn.com/course/Querydsl-%EC%8B%A4%EC%A0%84) <br> 수강 후 학습 내용 발표 |

<br>

|발표자|발표자료 레포지토리 링크|
|---|---|
|JIWON-JEONG||
|Diger-King||

---



---

## 다룰 예정인 주제

계층 아키텍쳐

예외처리

부동소수점 vs 고정소수점

## 추천 서적

리팩터링

오브젝트
