# Touch-My-Body

## 버전 기록

### ver 0.0.1 

- 2021.07.11

    1. 첫 배포

### ver 0.0.2

- 2021.07.14

    1. Cache 직렬화, 역질렬화 과정에서 발생하는 문제 해결

    2. 운동 추가 시 자극 근육 종류 추가 안되는 문제 해결

### ver 0.0.3

- 2021.07.18

    1. 유저의 운동 기록 캘린더에 운동한 날짜에는 표시되도록 변경

    2. 컨트롤러 클래스 주석 보완

### ver 0.0.4

- 2021.08.03

    1. Controller 클래스에 대한 통합 테스트 코드 추가 

    2. RestController 클래스에 대한 통합 테스트 코드 추가 

### ver 0.0.5

- 2021.08.06

    1. 버그 수정: 댓글 및 게시글을 일반 유저가 타인의 것을 삭제 할 수 있던 버그 수정
 
    2. 리팩토링: 클래스명 및 변수 명 의미 명확성 가독성 증진을 위한 변경

    3. 주석 보완: 주석 부족한 부분에 대한 보충 

### ver 0.0.6

- 2021.08.09

    1. 테스트 코드 추가: Service 클래스들에 대한 단위 테스트 코드 추가 

    2. 리팩토링: 반복되는 코드 최소화

### ver 0.0.7

- 2021.08.12

    1. 리팩토링: 반복되느 코드 최소화(AuthorityService 생성)

    2. 주석 정리

### ver 0.0.8 

- 2021.08.20

    1. 배포구조 변경

         - Jenkins -> TravisCI

    2. 리팩토링

         - 좋아요 관련 엔티티들의 부모 클래스 추가 : 추후 확장성 고려

         - 일부 변수명 목적 및 용도에 더 맞게 수정

         - 테스트 코드 리팩토링

### ver 0.0.9

- 2021.08.22

    1. 버그 수정: 일부 캐시 삭제 안되던 버그 수정

         - https://github.com/Gunyoung-Kim/Touch-My-Body/issues/19

    2. 테스트 커버리지 100% 달성

         - 테스트 커버리지 확인 위하여 jacoco 사용

    3. 리팩토링

         - 일부 캐시 키 변경

    4. 캐시 성능 개선

         - 자주 사용되지 않는 캐시 항목 삭제

         - 자주 변경되는 사항에 대한 캐시 항목 삭제

         - 캐시 삭제 최적화

### ver 0.0.10

- 2021.08.24

    1. 리팩토링

         - Controller, RestController들에 대한 리팩토링

    2. 테스트 코드 추가

         - Controller, RestController들에 대한 단위 테스트 코드 추가

### ver 0.0.11

- 2021.09.16

    1. 엔티티의 삭제 성능 개선 (쿼리 발생 숫자 줄임)

         -  관련 이슈 : https://github.com/Gunyoung-Kim/Touch-My-Body/issues/28 , https://github.com/Gunyoung-Kim/Touch-My-Body/issues/27

    2. 코드 리팩토링 및 테스트 케이스 추가 

### ver 0.0.12

    1. 성능개선
     	- DB Indexing을 활용한 성능 개선 : https://github.com/Gunyoung-Kim/Touch-My-Body/issues/32

     	- in절 활용을 통한 성능 개선 : https://github.com/Gunyoung-Kim/Touch-My-Body/issues/33

    2. 전체 패키지 리팩토링
