

# AWS RDS에서 사용할 MySQL 쿼리문

## 추가 명령어
 - sql 접근
   ```bash
   mysql -h <RDS_endpoint> -P <Port> -u <username> -p
   ```
 - 데이터베이스 추가
   ```mysql
   CREATE DATABASE 생성할DB이름 DEFAULT CHARACTER SET UTF8;
   USE seniorbuddy_db;
   ```
 - 테이블 목록
   ```sql
   SHOW TABLES;
   ```
 - 테이블 구조 확인
   ```sql
   DESCRIBE <tablename>;
   ```
 - 데이터 일부 확인 (N개)
   ```sql
   SELECT * FROM <tablename> LIMIT <N>;
   ```
 - 테이블 삭제
   ```sql
   DROP TABLE <tablename>;
   ```
 - 테이블 비우기 (구조 유지)
   ```sql
   TRUNCATE TABLE <tablename>;
   ```
   
