# git사용방법(주요 명령어)
1. 기본 설정
* (이름 설정) git config --global user.name "이름"
* (이메일 설정) git config --global user.email "이메일"
2. 로컬 저장소 생성 및 코드 반영
  * git init: 현재 디렉토리를 Git 저장소로 초기화합니다.
* git add <파일명>: 변경된 파일을 스테이징 영역(추적 대상)에 추가합니다.
* git commit -m "메시지": 스테이징된 파일들을 스냅샷으로 영구 기록합니다.
