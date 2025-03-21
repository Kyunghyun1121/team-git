# 3조 git

## 구조

### 1. :house: index.html (메인 페이지) - 임형섭
"우리 팀의 맛집 추천" 소개
각 맛집 페이지로 이동하는 네비게이션 링크
### 2. :pizza: food1.html (첫 번째 맛집) - 이유진
맛집 1 소개 
위치, 인기 메뉴, 추천 이유 작성
### 3. :sushi: food2.html (두 번째 맛집) - 노경현
맛집 2 소개 
위치, 인기 메뉴, 추천 이유 작성
### 4. :ramen: food3.html (세 번째 맛집) - 김예영
맛집 3 소개 
위치, 인기 메뉴, 추천 이유 작성
### 5. :world_map: food4.html (네 번째 맛집) - 안세영
맛집 4 소개
위치, 인기 메뉴, 추천 이유 작성
### 6. :world_map: food5.html (네 번째 맛집) - 임형섭

맛집 5 소개
위치, 인기 메뉴, 추천 이유 작성

## 요구사항

주제 정하기

- 기능 정의 -> 이슈로 만들기
- 각자 역할 분담 -> 이슈에 담당자를 할당
- 각자 페이지를 개발
- main branch 를 base로 하는 feature branch 따서 작업(local)
- 1인당 커밋은 최소 3개 (PR 3개 올려 주셔야해요)
  - 파일 추가 하는 커밋
  - 파일 변경(mv) 혹은 삭제(rm)하는 커밋
  - html 요소 하나 추가할 때 마다 한개의 커밋 만들어보고, rebase -i 로 합쳐보기

:warning: 다른 사람의 PR이 main으로 머지되면, 현재 작업중인 feature branch를 origin/main 기준으로 rebase 한 뒤, 작업 재개
:warning: 작업하던 내용은 git stash 명령어로 잠시 스택에 넣어둘 수 있음. rebase 완료 후에는 stash에 있는 변경사항 꺼내서 작업 다시 하시면 됩니다~!

- 작업이 완료되면 마지막 커밋은 index.html 인덱스 페이지에 내가 개발한 페이지로 이동하는 링크
- 개발이 완료된 로컬 브랜치는, 원격으로 push -> Pull Request 팀원들 전부
- 코드리뷰 진행
- 코드리뷰 반영 커밋
- 충돌이 발생하면 해결 -> 머지
