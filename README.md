<<<<<<< HEAD
=======
# branch_test
branch_test


>>>>>>> test/fastforward
dir
디렉터리

git clone

git status
현재 프로젝트 상태확인

cd branch_test

branch_test>dir

git log --pretty
커밋 기록 형식
git log --pretty=oneline --graph
git log --pretty=format:"%h %an %s" 

C:\javaStudy\git_test\branch_test>git config user.name "papepopopy"
C:\javaStudy\git_test\branch_test>git config user.email "hapohee@naver.com
이메일과 유저 이름을 설정 후 확인


git log --pretty=oneline
한줄 요약
short, full, fuller

git remote update
서버 변경 상태 동기화

git branch 생성

git branch -l 로컬
git branch -r 원격지
git branch -a 전체

git branch -d 삭제

브렌치 병합
새로운 작업 



C:\javaStudy\git_test\branch_test>git branch -a
* main
  origin/main
  test/remote-branch
  remotes/origin/HEAD -> remotes/origin/main
  remotes/origin/main
  remotes/origin/test/remote-branch

C:\javaStudy\git_test\branch_test>git branch -l
* main
  origin/main
  test/remote-branch

C:\javaStudy\git_test\branch_test>git branch -r
  origin/HEAD -> remotes/origin/main
  origin/main
  origin/test/remote-branch



git checkout -t  브랜치 명 : 원격지를 지역 저장소에 설정
git checkout 브랜치 명 : 위치 변경

git push origin 브랜치명 : 생성 브런치 반영 (지역 => 원격지)

<<<<<<< HEAD
C:\javaStudy\git_test\branch_test>code => 비주얼스튜디오 이동

브랜치 병합
fast foward 빨리감기 (main 기준)병합

=======
C:\javaStudy\git_test\branch_test>code => 비주얼스튜디오 이동
>>>>>>> test/fastforward
