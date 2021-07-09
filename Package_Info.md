# Touch-My-Body

## 코드 패키지 설명

### Main = com.gunyoung.tmb

### $Main.aop

- $Main.aop.annotations : 어드바이스 적용 메소드에 추가할 어노테이션 모음

- $Main.aop.log : 로그 관련 어드바이스 모음

- $Main.aop.login : 로그인 관련 어드바이스 모음

### $Main.config

- $Main.config : Configuration Class 모음

### $Main.controller

- $Main.controller : 화면 반환하는 컨트롤러(@Controller) 모음 

- $Main.controller.rest : Rest 컨트롤러(@RestController) 모음 

### $Main.domain

- $Main.domain.exercise : 운동 관련 엔티티 엔티티 모음

- $Main.domain.like : 좋아요 관련 엔티티 모음 

- $Main.domain.user : 사용자 관련 엔티티 모음 

### $Main.dto

- $Main.dto.jpa : 쿼리 결과 매핑용 DTO 모음

- $Main.dto.request : 클라이언트의 Request Body 매핑용 DTO 모음

- $Main.dto.response : 서버의 Response Body 용 DTO 모음

### $Main.enums 

- $Main.enums : Enumeration Class 모음 

### $Main.error 

- $Main.error : 예외 처리 컨트롤러, 예외 발생 시 응답 객체 모음

- $Main.error.codes : 클라이언트에 보낼 에러 메시지, 코드 번호를 포함한 에러 코드(Enum) 모음

- $Main.error.exceptions : 비즈니스 로직 수행 중 발생하는 예외 

- $Main.error.exceptions.duplication : 중복 문제 관련 예외 모음

- $Main.error.exceptions.nonexist : 부재로 인한 예외 모음 

- $Main.error.exceptions.notmatch : 불일치로 인한 예외 모음 

- $Main.error.exceptions.request : 클라이언트의 잘못된 요청으로 인한 예외 모음 

### $Main.repos

- $Main.repos : JpaRepository 인터페이스 상속 인터페이스 모음 

### $Main.security

- $Main.security : Spring Security 관련 클래스 모음

### $Main.services

- $Main.services.domain.exercise : 운동 관련 엔티티들의 서비스 클래스 모음

- $Main.services.domain.like : 좋아요 관련 엔티티들의 서비스 클래스 모음 

- $Main.services.domain.user : 사용자 관련 엔티티들의 서비스 클래스 모음

### $Main.utils

- $Main.utils : 각종 유틸리티 클래스 (코드 정리에 윤활유 같은 역할) 모음 

