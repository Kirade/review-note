# SQL 서버에서 장고를 추구하면 안될까?

### 배경
- Window server, SQL 서버를 사용하고 있음
- 장고에서는 SQL Server를 공식적으로 지원하지 않음
- 이런 환경에서 개발하는 분들의 시행착오를 줄이면 좋겠다.

### MS-SQL
- MS에서 만들고 관리함
- Linux, Mac에서도 사용가능함, 개발자 버전은 크기 제한 없고 무료
- Linux는 배포판 설치, Mac에서는 Docker 사용
- 명령줄 도구, pyodbc, jdbc를 사용해서 연결할 수 있다.

### ODBC
- DB접근을 위한 표준 규격
- 다양한 DBMS에 연결하기 해준다. 
