> # Markdown
## 1. Markdown 개념
* 텍스트 기반의 가벼운 마크업 언어
* 문서의 구조와 내용을 같이 쉽고 빠르게 적고자 탄생함
* 마크업 - 태그를 이용하여 문서의 구조를 나타낸 것    
## 2. 작성방법 및 활용
* README.md 파일을 통해 오픈 소스의 공식문서 작성
* 개인 프로젝트의 소개 문서 작성
* 매일 학습한 내용 정리 = 개발 문서의 시작과 끝
## 3. 내용정리
1. #헤딩
   - #은 문서의 제목이나 소제목으로 사용
   - #의 개수에 따라 제목의 수준을 구별
   - *글자의 크기를 위해 사용*을 **금지**!!
2. 1.2.3. 리스트
   - 순서가 있는 리스트(1.2.3.)와 순서가 없는 리스트(*-)
   - 목록을 표시하기 위해 사용
   
  ```code block``` `inline code block`

3. 코드 블럭(code block) -일반 텍스트와 다르게 코드를 이쁘게 출력
   - 개발자가 마크다운을 사랑하는 이유 중 하나
   - 사용하는 프로그램에 따라 특정언어를 명시하면 구문강조(syntax highlightinh) 지원


4. 링크(link) - *[설명]*(주소)
   - string은 보여지는 부분, url은 연결할 곳을 나타낸다.
   - 다른 페이지로 이동하는 링크를 삽입
   - 필요하다면 파일의 경로를 넣어 다운로드 가능한 링크로 만들 수 있다.


5. 이미지(image)  *![설명]*(이미지주소)
   - 링크와 비슷하지만 이미지를 삽입합니다.
   - 이미지의 너비와 높이는 조절 불가

6. 텍스트 강조 - 순서대로 굵게, 기울임, 취소선을 이용해 텍스트 강조
   - *를 _로 대체 가능

7. --- 수평선 - 가로로 긴 수평선을 작성합니다. 대개 단락 구분할 때 사용
   - 을 *나 _로 대체가능하다.
   - 3개 이상만 적으면 똑같이 작용

참고자료 https://www.markdownguide.org/cheat-sheet/


> # Git/Github
## 1. Git 개념
* 분산버전 관리시스템
* 코드의 히스토리(버전)를(을) 관리하는 도구
* 개발되어온 과정 파악가능
* 이전버전과의 변경사항 비교 및 분석
 
## 2. 작성방법 및 활용

# Git 기본기

## 1. readme.md
  - 프로젝트에 대한 설명 문서
  - github 프로젝트에서 가장 먼저 보는 문서
  - 일반적으로 소프트웨어와 함께 배포
  - 작성 형식은 따로 없으나, 일반적으로 마크다운을 이용해 작성

## 2. repository
  - 특정 디렉토리를 버전 관리하는 저장소
  - git init 명령어로 로컬 저장소를 생성
  - .git 디렉토리에 버전 관리에 필요한 모든 것이 들어있음(.이 있으면 숨김파일이 된다.)
  - ~/Desktop/git_test (master) 이 디렉토리가 git으로 관리 된다는것을 나타낸다.

## 3. 특정버전으로 남긴다 = 커밋(commit)한다(3가지 영역을 바탕으로 동작)

  - working directory - 작업영역(실제로 작업하는 위치 )
  - staging area - commit으로 남기고 싶은 내용
  - repository - commit을 만들면 저장되는 곳
## 순서 흐름 및 명령어
  - working directory -> staging area 
  - git add: working -> staging
  - staging area -> repository
  - git commit : staging area -> repository
  - git status : 현재 상태 확인

  - github(remote repository)
  - git branch -M main -> master를 -> main으로 바꿔주는 명령어(master, main 확인 잘 하기)

  - git push -> online으로 올려주는것

  - bash에서 q가 종료의 약자이므로 q를 눌러볼것
  - 잘못눌러서 unix로 들어갔을 때 esc로 누르면 명령모드로 바뀐다 :q!입력하면 탈출 가능하다.

  - 저장 ->  add -> commit ->push

  - 클론과 다운로드의 차이로 다운로드는 이력을 가지고 오지않는다. 

  * git hub repo
  * Local Repo
  * 파일 수정
  * Commit - git init이 필요없음
