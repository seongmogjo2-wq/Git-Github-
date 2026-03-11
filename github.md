# github사용방법
1. 기본 설정
* 회원가입:github사이트에서 계정생성
 * Git 설치: Git 공식 사이트에서 git설치해서 로컬 pc에서 관리
  * 사용자 설정: 터미널에서 이름과 이메일 설정
    + (이름 설정)git config --global user.name "이름"
     +  (이메일 설정)git config --global user.email "이메일"
2. 로컬 저장소 생성 및 연결
* 저장소 생성: GitHub 웹사이트에서 'New' 버튼을 눌러 생성.(이름,비공개,공개 여부 설정)
* 로컬 프로젝트 연결: 로컬 폴더에서 터미널을 열고 아래 명령어 실행
 + (로컬 저장소 초기화)git init
  + (원격 저장소와 연결)git remote add origin <저장소 URL>
   + (기존 저장소 가져올때) git clone <저장소 URL>
3. 코드 올리기
* 변경 사항 추가:(모든 파일 추가) git add .
*  커밋 생성:(변경 내용 기록) git commit -m "커밋 메시지" 
* 원격 저장소 반영:(로컬의 변경 사항을 GitHub에 업로드) git push -u origin main
