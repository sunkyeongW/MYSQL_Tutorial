# 데이터 베이스
    컴퓨터 언어를 통해서 제어.
    데이터 베이스에 저장된 데이터를 웹이나 앱을 통해서 공유 가능.

# 데이터 베이스 장점
    보안 : 데이터 베이스는 자체적인 보안체계가 있어 안전하게 데이터 보관 가능.
    권한 : 여러 사람을 등록하여, 원하는 사람만 접근 가능하게 설정 가능.
    
# MySQL 구조
    데이터 저장 -> 표(table)
    표(table) grouping -> 데이터 베이스(=스키마)
    데이터 베이스 grouping -> 데이터 베이스 서버

# MySQL 접속
    mysql -uroot -p 입력 후 비밀번호 설정.
    "Welcome to the mysql monitor." 이란 문장이 나오면 접속 성공.

# MySQL 스키마(=db)의 사용
    db 생성 : CREATE DATABASE 이름;
    db 삭제 : DROP DATABASE 이름;
    db 목록 : SHOW DATABASES;
    db 사용 : USE 이름;

# SQL(Structured Query Language)
    Structured : 표 구조화(table)
    Query : 데이터 요청
    Language : 데이터베이스 서버에게 요청

    관계형 데이터베이스에 공통적으로 데이터 베이스 서버를 제어할 때 사용하는 언어.

# table 구조
    table : 표
    row, record(행) : 각각의 데이터
    column(열) : 데이터의 타입 (ex)id, title ...)

# table 생성
    INT : 정수만 등록 가능
    NOT NULL : 공백 등록 불가
    AUTO_INCREMENT : 값 자동 증가
    VARCHAR(값) : 최대 글자 개수
    DATATIME : 날짜와 함꼐 시간까지 저장하는 타입
    PRIMARY KEY : 고유한 값을 지정.
