# my_smartfarm_database_MFC


connected failed 뜰 시 연락바람. :: 해결책: mysql connector 64비트, 32비트 둘 다 설치
5_7View : 메인 화면 : ODBC 연결함
create : 비모달형 : ODBC 연결함
report : 비모달형 : ODBC 연결함

변수명 정리:
create ; 다이얼로그 1: 

작물 이름 : edit control : m_name // edit1
라인 : combobox : m_line  //combo1
적정온도 : combobox : m_temp //combo2
적정습도 : combobox : m_moist //combo3
적정일조량 : combobox : m_light //combo5
물주는주기 : combobox : m_cycle //combo4
리스트컨트롤 : 현재 내가 심은 작물 내역 볼 수 있게 함. : m_create
생성하기 : IDOK --> 데이터베이스 생성하기 + 불러오기
---> 주키 : 라인

취소 : IDCANCEL --> 현재 다이얼로그 닫을 수 있게 함.

-----------생성하기 버튼을 눌렀을 때-----------------

create 테이블에 생성됨



변수명 정리:
report ; 다이얼로그 2: 



 
내 농장 전체 리포트 : 제약조건 없음 //button2
리포트 검색하기 : 제약조건 위에 있음. 체크박스나 시작날짜, 종료 날짜에 의해 워크벤치에서 검색해옴 //button 1
작물 성장 기록 : 파일 저장하기 엑셀로?//button 3


시작날짜 ; m_start
종료날짜 : m_end


https://server-talk.tistory.com/279 : 디비 타입 간단 정리

동적 메뉴, 서브 메뉴 등 넣기.
이 저장된 파일 다 불러올 수 있게하기
--

회원가입할 때 이메일 유효검사하기

--> 전국 농사 단위로 수확할 때 상품성이랑 언제 수확했는지 유의미한 결과 추출하기



전체리포트 만들기:  --> 날짜, 2020211061,30, 작물 이름, 아이디, 라인


