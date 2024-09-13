# branch_test
branch_test 프로젝트

## Git 명령어 정리

### 기본 명령어
1. `git clone`  
   - 원격 저장소를 복제합니다.

2. `git status`  
   - 현재 프로젝트 상태를 확인합니다.

3. `git log --pretty`  
   - 커밋 기록을 다양한 형식으로 출력합니다.
   - `git log --pretty=oneline --graph`: 한 줄 요약 및 그래프 출력
   - `git log --pretty=format:"%h %an %s"`: 해시, 작성자, 커밋 메시지 출력

### 사용자 설정
- Git 사용자 이름과 이메일 설정 후 확인

### Git 브랜치 명령어
1. 브랜치 목록 보기
   - `git branch -l`: 로컬 브랜치 목록 확인
   - `git branch -r`: 원격 브랜치 목록 확인
   - `git branch -a`: 로컬 및 원격 브랜치 전체 목록 확인

2. 브랜치 삭제
   - `git branch -d 브랜치명`: 로컬 브랜치 삭제

3. 브랜치 생성 및 병합
   - 브랜치 생성 후 작업을 완료하고 병합
   - 병합 방식: Fast-forward 병합

### 원격 브랜치 관련
1. 원격지 동기화
   - `git remote update`: 원격 저장소의 상태와 동기화

2. 원격 브랜치 체크아웃
   - `git checkout -t 브랜치명`: 원격지 브랜치를 로컬로 가져옴
   - `git checkout 브랜치명`: 특정 브랜치로 위치 이동

3. 브랜치 푸시
   - `git push origin 브랜치명`: 로컬 브랜치를 원격 저장소에 푸시

### 병합 충돌 해결
- Fast-forward 방식으로 병합:


### 추가 정보
1. `dir`: 한글 지원 확인
2. 코드 편집기로 이동
   - `C:\javaStudy\git_test\branch_test>code`: Visual Studio Code로 이동
