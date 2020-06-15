# TFT 관련 진행해야할 이슈들 필터링 후 진행

## 2020.7

### BUG

#### 테이블 매니저

- 테이블 목록 조회

  - (BACKLOG) [일반 사용자 계정이 해당 스키마에 권한이 있음에도 불구하고 노트북에서 생성한 테이블이 보이지 않음](http://jira.nexrcorp.com/browse/CON-3896)

- 로컬에서 HDFS에 파일 업로드(200M 제한)

  - (BACKLOG) [동일한 이름의 파일을 업로드할 때 엎어치기 됨](http://jira.nexrcorp.com/browse/CON-3898)

- HDFS 파일을 스파크 테이블로 등록

  - (BACKLOG) [데이터, 테이블코멘트, 컬럼코멘트 한글깨짐](http://jira.nexrcorp.com/browse/CON-3826)

- HDFS CSV 파일을 스파크 테이블로 등록
  - (BACKLOG) [csv로 스파크 테이블 생성시, 첫 행에 null이 포함된 컬럼은 제외됨 테이블매니저, 대시보드 등에서는 해당 컬럼이 나오지 않음 노트북에서 해당 컬럼 조회하면 수행됨 / 한글데이터 깨짐](http://jira.nexrcorp.com/browse/CON-3901)
- 테이블 코멘트 등록
  - (BACKLOG) [한글 깨짐](http://jira.nexrcorp.com/browse/CON-3826)
- KAFKA XSV 데이터의 스파크 테이블 등록

  - (BACKLOG) [virtual view 테이블이 사용자에게 보이지 않음 managed 임시테이블만 보임 admin 계정은 보임](http://jira.nexrcorp.com/browse/CON-3905)

- KAFKA JSON 데이터의 스파크 테이블 등록
  - (BACKLOG) [virtual view 테이블이 사용자에게 보이지 않음 managed 임시테이블만 보임 admin 계정은 보임](http://jira.nexrcorp.com/browse/CON-3905)

#### 환경설정 및 현황

- 역할 비활성화

  - (BACKLOG) [역할에 사용자가 포함되어 있음에도 불구하고 역할이 비활성화됨](http://jira.nexrcorp.com/browse/CON-4118)

- HDFS 저장소 접속 테스트

  - (BACKLOG) [HDFS 저장소 계정을 아무거나 입력해도 접속가능함](http://jira.nexrcorp.com/browse/CON-4119)

- JDBC 저장소 접속 테스트

  - (BACKLOG) [존재하지 않는 스키마를 입력해도 접속가능함](http://jira.nexrcorp.com/browse/CON-3959)

- 저장소 비활성화

  - (BACKLOG) [저장소를 참조하고 있는 스파크 테이블이 있음에도 불구하고 비활성화 됨](http://jira.nexrcorp.com/browse/CON-3965)

- 사용자 추가

  - (BACKLOG) [메뉴권한만 있는 사용자가 사용자를 추가할 수 있음. 사용자가 사용자를 추가하는 것이 올바른 기능인지?](http://jira.nexrcorp.com/browse/CON-3946)

- 사용자 기본정보 수정 (이름, 휴대폰번호, 이메일, Slack, 역할)

  - (BACKLOG / 이슈 생성 필요) [이벤트 메일 수신 안 됨 / 슬랙채널 수신 안 됨 / 사용자 수정시 역할을 모두 삭제했을 때 에러가 나지 않음](http://jira.nexrcorp.com/browse)

- 사용자 이벤트 수신 설정 수정

  - (BACKLOG / 이슈 생성 필요) [이메일 및 슬랙 채널 수신 안 됨](http://jira.nexrcorp.com/browse)
