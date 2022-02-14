# Git 기초

.git 폴더는 무엇인가요 ?
    - 커밋이 담겨져있는 폴더
.git 폴더를 만드는 방법 
    - git init

Project 폴더 -> C:\Users\pc-007\Documents\workspace\leacure
project 폴더에서 src 를 가라! ->  C:\Users\pc-007\Documents\workspace\leacure\src
src 에있는 상태에서 root 디렉토리로 가라! -> C:\Users\pc-007\Documents\workspace\leacure

Project 폴더에서 git init 을 써라
앞으로 leacure 디렉토리는 git로 관리하겠다. 

source tree GUI 
CLI git 관리할줄아는사람이 썻을때 빛을 

git 도움을 주는 확장앱 설치
> Git Graph

git log


알파벳 j 눌러도 내려가고 방향키 내려도 내려갑니다.

- 1 gitignore git init .git 폴더 생성생성
내가 굳이 이폴더는 올릴필요가없는 파일 혹은 디렉토리
아이디와 패스워드를 저장하는 text파일
node_modules 코드가 많다.
package-lock.json <--


- 2 Reset , Revert 커밋을 뒤로 돌아가는 행위

git reset --hard [돌아갈커밋]
git revert [취소할커밋hash값]

- 3 branch 커밋을 나누는 행위

나는 master 브랜치이다!

- 4 merge, rebase 커밋을 합쳐주는 행위

