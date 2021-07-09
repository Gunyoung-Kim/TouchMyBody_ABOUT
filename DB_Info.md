# Touch My Body

## DB 테이블 설명

### 사용 데이터 베이스

- mysql

---

### 테이블 설명

![TouchMyBodyTable](https://user-images.githubusercontent.com/60494603/125125625-cc799080-e134-11eb-8868-5ade689ad6db.png)

- 모든 테이블은 id, created_at, modified_at, version 컬럼 보유

#### user

- 해당 서비스의 유저

- email: 유저의 이메일 주소, password: 비밀번호, first_name: 이름, last_name: 성

  nick_name: 서비스에서 표시되는 닉네임, role: 유저의 권한 (관리자, 매니저, 일반 유저)

#### user_exercise 

- 유저의 웨이트 트레이닝(이하 운동) 기록 

- date: 해당 운동한 날짜, description: 해당 기록에 대한 짧은 설명, laps: 몇 회 반복했는지, 

  sets: 몇 세트 했는지, weight: 몇 kg으로 했는지, exercise_id: exercise 외래키 

  user_id: user 외래키 

#### exercise 

- 웨이트 트레이닝 운동 종류 

- name: 이름, description: 운동에 대한 설명, movement: 운동하는법, caution: 운동 시 주의사항

  target: 운동 분류(가슴운동, 하체운동, 등운동 등)

#### muscle

- 근육 종류

- name: 이름

#### exercise_muscle

- 운동할때 자극되는 근육 종류

- is_main: 주 자극근육인지 여부, exercise_id: exercise 외래 키, muscle_id: muscle 외래 키

#### feedback 

- 운동 정보에 관한 유저의 피드백

- title: 제목, content: 내용, exercise_id: exercise 외래 키, user_id: user 외래 키

#### exercise_post

- 운동 관련 게시글 

- title: 제목, contents: 내용, exercise_id: exercise 외래 키, user_id: user 외래 키

#### comment 

- 게시글에 추가되는 댓글

- contents: 내용, is_anonymous: 작성자가 익명으로 표시되길 원하는지, writer_ip: 작성자의 IP 주소,

  exercise_post_id: exercise_post 외래 키, user_id: user 외래 키

#### post_like

- 게시글에 추가되는 좋아요

- exercise_post_id: exercise_post 외래 키, user_id: user 외래 키 

#### comment_like

- 댓글에 추가되는 좋아요

- comment_id: comment 외래 키, user_id: user 외래 키 

 
