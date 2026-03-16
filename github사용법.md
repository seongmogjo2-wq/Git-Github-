# github사용방법
1. 기본 설정
* 회원가입:github사이트에서 계정생성
* Git 설치: Git 공식 사이트에서 git설치해서 로컬 pc에서 관리
* 사용자 설정: 터미널에서 이름과 이메일 설정
  + (이름 설정)
    ```md
    git config --global user.name "이름"
  + (이메일 설정)
  ```md
  git config --global user.email "이메일"
2. 로컬 저장소 생성 및 연결
* 저장소 생성: GitHub 웹사이트에서 'New' 버튼을 눌러 생성.(이름,비공개,공개 여부 설정)
* 로컬 프로젝트 연결: 로컬 폴더에서 터미널을 열고 아래 명령어 실행
  + (로컬 저장소 초기화)
  ```md
  git init
```md
  git remote add origin <저장소 URL>
```md
git clone <저장소 URL>
3. 코드 올리기
```md
git add .
```md
git commit -m "커밋 메시지" 
```md
git push -u origin main
