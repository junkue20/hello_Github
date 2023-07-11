# Git/GitHub
## 23.07.11 (화)

- cli 개념 학습
- powercell 명령어 학습
```
cd 폴더명          : 폴더 들어가기
cd ..             : 뒤로가기
mkdir 폴더명      : '폴더명'으로 폴더 생성
dir(ls)           : 현재 위치의 모든 파일들 표시
pwd(Get-Location) : 현재 경로 파악
```
---

- VScode 활용, Git 저장소 생성 및 Github 연동 명령어 학습
```
/* 깃 저장소 생성시 한번만! */
git config --global user.email (메일주소)
git config --global user.name (이름)
git remote add origin (원격저장소 주소)
/* ---------------------- */

git add (파일명)      : 해당 파일 하나만 추가 
git add .            : 현재 폴더 위치 내의 모든 파일들 추가
git status           : 현재 git 등록 대상 파일 보기

git commit -m "커밋타입: 동작 기능이름/함수이름"            : "커밋 메세지"의 내용으로 커밋 
git commit --amend -m"커밋타입: 동작 기능이름/함수이름"     : 이전 커밋 메세지를 변경

git revert  (앞 6자리 커밋코드)       : 버전 되돌리기
git reset   (앞 6자리 커밋코드)       : 해당 커밋 초기화
git reset --soft (앞 6자리 커밋코드)  : 커밋 기록만 되돌림.
git reset --hard (앞 6자리 커밋코드)  : 파일 자체도 되돌림. 
```

