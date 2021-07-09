# Touch My Body

## DB 테이블 설명

### 사용 데이터 베이스

- mysql

---

### 테이블 설명

#### user

- 해당 서비스의 유저를 나타내는 테이블 

- email: 유저의 이메일 주소, password: 비밀번호, first_name: 이름, last_name: 성

  nick_name: 서비스에서 표시되는 닉네임, role: 유저의 권한 (관리자, 매니저, 일반 유저)

#### user_exercise 

- 유저의 웨이트 트레이닝(이하 운동) 기록 

- date: 해당 운동한 날짜, description: 해당 기록에 대한 짧은 설명, laps: 몇 회 반복했는지, 

  sets: 몇 세트 했는지, weight: 몇 kg으로 했는지, exercise_id: exercise 외래키 

  user_id: user 외래키 




 
