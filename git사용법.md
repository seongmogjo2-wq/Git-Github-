# git사용방법(주요 명령어)
1. 기본 설정
* (이름 설정)
```md
git config --global user.name "이름"
```
* (이메일 설정)
```md
git config --global user.email "이메일"
```
2. 로컬 저장소 생성 및 가져오기
* (저장소 만들기)
```md
git init
```
* (기존 저장소 가져오기)
```md
git clone 저장소주소
```
3. 파일 관리
* (변경된 파일 확인)
```md
git status
```
* (파일 추가)
```md
git add 파일이름
```
  + (모든 파일 추가)
```md
git add .
```
* (변경기록 저장)
```md
git commit -m "변경 내용"
```
4. 원격 저장소
* (원격 저장소 연결)
```md
git remote add origin 저장소주소
```
  + (원격 저장소 확인) git remote -v
* (코드 업로드)
```md
git push origin main (원격 저장소로)
```
* (코드 가져오기)
```md
git pull (원격 저장소에서 최신 변경 내용 가져오기)
```
