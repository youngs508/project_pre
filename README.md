# Team Rules
### Commit message : git add . => git add 파일명, 커밋메세지 세분화
### Branch name : 슬래시 사용
### Code convention : prettier 사용
### Task allocation : 알아서 잘 딱 센스있게

## project schedule(dev)
### 09:00 - 09:30 : 미팅 전날 작업한 현황 공유/오늘 할 일 공유 
### 09:30 - 12:00 : 작업
### 12:00 - 13:00 : 점심 시간
### 13:00 - 13:30 : 미팅 현황 브리핑
### 13:30 - 17:00 : 코딩 작업
### 17:00 - 18:00 : 코드 리뷰

## Issue Sharing Guide
### 질문이 있거나 도움이 필요한 경우 망설이지는 않지만 생각을 충분히 한 후 질문하기
### 답변은 최선을 다하여 해주기

## Git Rule
### feature branch에서 작업
### develop에서 branch 생성
### develop과 master에 직접 푸시 X / 풀 리퀘스트 O
### Pull Request 생성 전 리베이스하는 동안 잠재적인 충돌 제거
### 병합 후, 로컬과 원격에 있는 feature 브랜치 삭제
### feature 브랜치의 빌드 검사 / 코드 스타일 체크 등 모든 테스트 통과 검증 후 Pull Request
### .gitignore 사용
### develop과 master 브랜치 보호

## Commit
### 동명사X 관사X 명사O
### 부정문 Don't 사용
### 줄 바꿈을 통해서 제목과 본문을 구분
### 제목에 대문자를 사용
### 제목을 마침표 사용 X
### 제목에 명령법(imperative mood) 사용
### 오타 수정 = Fix typo

## Type Commit
### FIX : 올바르지 않은 동작을 수정
### ADD : 코드나 테스트, 예제, 문서 등의 추가
### REMOVE : 코드의 삭제
### USE : 특별히 무언가를 사용해 구현
### REFACTOR : 전면 수정
### SIMPLIFY : 복잡한 코드를 단순화
### UPDATE : 개정이나 버전 업데이트, FIX와는 달리 UPDATE는 잘못된 것을 바로잡는 것이 아님
### IMPROVE : 호환성, 테스트 커버리지, 성능, 검증 기능, 접근성 등 향상
### MAKE : 기존 동작의 변경
### IMPLEMENT : 코드가 추가된 정도보다 더 주목할 만한 구현체를 완성, Add에 비해 더 큰 단위의 코드 추가에 사용
### REVISE : 문서의 개정
### CORRECT : 문법의 오류나 타입의 변경, 이름 변경
### ENSURE : 무엇이 확실하게 보장받는다는 것을 명시
### PREVENT : 특정한 처리를 못하게 방지
### AVOID :  특정한 처리를 못하게 회피, 'Prevent'는 못하게 막지만, 'Avoid'는 회피
### MOVE : 코드의 이동
### RENAME : 이름 변경
### ALLOW : 허용 표현
### VERIFY : 검증 코드
### SET : 변수 값을 변경하는 등의 작은 수정  
### PASS : 파라메터를 넘기는 처리

# Workflow
## Leader
### 초기 레포지토리를 받아 local에 클론
### master 브랜치에서 초기 세팅
### 그대로 dev 브랜치 생성
### dev에 푸시 후 master에 merge

## Member
### fork 후 로컬에 clone
### dev 브랜치를 기반으로 feature 브랜치 생성
### feature 브랜치에서 완성되면 해당 브랜치로 푸시
### P/R을 upstream dev에 요청
### (업데이트가 있을 때) upstream으로부터 pull하여 최신화된 정보 동기화 