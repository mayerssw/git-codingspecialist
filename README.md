# git-codingspecialist


-----------------------------------------

## 지옥에서 온 관리자 Git 13강 - Git branch 기본개념

- 3-way merge
- fast-foward merge
- 
-----------------------------------------


## 지옥에서 온 관리자 Git 12강 - Git 최종 로그 변경하기

git commit --amend -m "test1.txt 생성완료"

git rebase(브랜치 정리)





-----------------------------------------

## 지옥에서 온 관리자 Git 11강 - Git 복구왕 Reflog

두번째 사진으로 돌아가고 싶다~~~

git reflog

오...

-----------------------------------------

## 지옥에서 온 관리자 Git 10강 - Git Reset 명령어

ex03

git reset(soft, mixed, hard)

hard(다 날린다)

mixed(git add . 전 상태)(작업영영의 내용변경이 필요할 시)

soft(헤더만 지운상태)(커밋로그 변경)

$ git reset --soft 7775(커밋 로그 변경)

$ git reset --mixed 7775 (잘 안씀)(차라리 다시 찍음)

$ git hard --hard (파일까지 다 날라감...)













-----------------------------------------

## 지옥에서 온 관리자 Git 9강 - Git 기본기 실습 세번째

.git\refs\heads



-----------------------------------------


## 지옥에서 온 관리자 Git 8강 - Git 기본기 실습 두번째

git init (작업영영 생성)

git status

untrackted

git add . (SNAPSHOT)(인덱스)

tracked

.git - object - ad (hash) <- 볼 필요X

git commit -m "첫번째 사진" (스냅샷을 사진첩으로 이동)(헤더)

git log

-----------------------------------------

## 지옥에서 온 관리자 Git 7강

SCM

SNAPSHOT

-----------------------------------------

## 지옥에서 온 관리자 Git 6강

git init

working directory

변경 감지

------------------------------작업영역

git add

------------------------------인덱스영역

tree

git commit(영구히 기록)

HASH CODE로 관리

BLOB

------------------------------헤더영역
