# Git 명령어

## CLONE

- git clone [REPO_URL] [DIR] → 클론
- git **clone** -b {branch_name} --single-branch {저장소 URL} → 특정 브랜치만 클론

## PULL

- git pull [https://github.com/williamkevin/Sp-ACE.git](https://github.com/williamkevin/Sp-ACE.git) main

## PUSH

- git init → **깃**을 사용할 수 있도록 **폴더**를 초기화
- git status
- git add . 또는 git add “폴더명” →  tracked 파일로 변경
- git commit -m "무엇을 했는지에 대한 짧막한 서술"
- git push origin master(main) → 파일 업로드

## 깃 원격저장소 등록과 해제

- git remote add origin [https://github.com/williamkevin/Java-Project.git](https://github.com/williamkevin/Java-Project.git)
- git remote remove origin
- git remote -v → 로컬 저장소와 원격 저장소가 연결되었는지 확인

## 깃 폴더 삭제

- git rm {디렉토리명 또는 파일명}
- **git rm --cached -r 폴더명**

git ls-files → 깃에 올라가 있는 파일과 폴더를 확인할 수 있다.

## 사용자 등록

- git config —global [user.name](http://user.name) williamkevin
- git config --global [user.email](http://user.email) prepared7913@naver.com

## 브랜치 생성과 삭제

- git branch <branchname> → 브랜치 생성
- `git branch -d <branchname>` → 브랜치 삭제
- git branch → 현재 있는 브랜치를 확인하는 명령어
- git branch -M [되고싶은 branch name]
- git branch -m [현재 branch name] [바꾸고싶은 branch name]
- **git checkout [전환하고싶은 브랜치명] → 브랜치 전환**