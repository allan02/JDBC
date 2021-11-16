# JDBC
<br>
<ul>

  <li>JDBC(Java Database Connectivity)의 정의</li><br>
  
  <ul>
    <li>자바를 이용한 데이터베이스 접속과 SQL 문장의 실행,<br><br>그리고 실행 결과로 얻어진 데이터의 핸들링을 제공하는 방법과 절차에 관한 규약입니다.</li><br>
    <li>자바 프로그램 내에서 SQL문을 실행하기 위한 자바 API입니다.</li><br>
    <li>SQL과 프로그래밍 언어의 통합 접근 중 한 형태입니다.</li><br>
  </ul>
 
  <br>
  <li>JDBC 클래스의 생성 관계</li><br>
  
  <ul>
    <li><strong>DriverManager</strong><br><br>
        데이터베이스 드라이버들을 로딩하고, 데이터베이스에 연결을 책임지는 클래스입니다.<br><br>
        -> DriverManager를 이용해 Connection인스턴스를 얻습니다.
    </li><br>
    <li><strong>Connection</strong><br><br>
        자바와 데이터베이스를 연결하기 위한 클래스입니다.<br><br>
        -> Connection을 통해서 Statement를 얻습니다.
    </li><br>
    <li><strong>Statement</strong><br><br>
        SQL 구문을 실행하기 위한 클래스입니다.<br><br>
        -> Statement를 이용해 ResultSet을 얻습니다.
    </li><br>
    <li><strong>ResultSet</strong><br><br>
        명령에 대한 반환값입니다.
    </li>
  </ul>
</ul>
  
