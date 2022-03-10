# <img src="./images/covengers_logo.png" width="40px" /> Return Z3RO; 

* : MES 생산관리 모니터링 시스템 개발
* : calendar : 2022.03.07 ~ 2022.05.26

## :family_man_boy_boy: 팀원 소개
|진혜린(PM)|김선혁|마상우|백성문|임한나
|:---:|:---:|:---:|:---:|:---:
|<img src="" width="100px" />|<img src="" width="100px" />|<img src="" width="100px" />|<img src="" width="100px" />|
|<img src="" width="100px" />|
|[진혜린 github 주소](https://github.com/fascinate98)|[김선혁 github 주소](https://github.com/shk4548)|[마상우 github 주소](https://github.com/masangwoo)|[백성문 github 주소](https://github.com/100SM)|[임한나 github 주소](https://github.com/luster1031)|

## :heavy_check_mark: Rules

<img src="./images/covengers_보드.jpg" width="20%" />

+ 9시출근
+ 매일 : 일지 - 9:10 인당 1~2 10분정도 짧회의. : 오늘할일, 어제한일 
+ 금요일 : 주간회의 피드백 조율 → 질문사항, 진행사항(맨토랑얘기할거)
+ 프로젝트 설계 계획 틀 ← 확실히 하자 (변수명 규칙,,) 모든 업무 완벽 숙지 및 이해
+ 업무 분담 : 하되 개인의 로직 지적 코드 지적 금지.
+ 1일 1커밋(주말제외) 
야근하지말자. 주말근무없음. (단, 평일에 할일 다 끝냈을 시)




- Commit Rules
  - 형식

      ```
      #name [commit-type]: (scope) message
      ```
  - commit type
      - FEAT : 새로운 기능의 추가
      - FIX: 버그 수정
      - DOCS: 문서 수정
      - STYLE: 스타일 관련 기능(코드 포맷팅, 세미콜론 누락, 코드 자체의 변경이 없는 경우)
      - REFACTOR: 코드 리펙토링
      - TEST: 테스트 코트, 리펙토링 테스트 코드 추가
      - CHORE: 빌드 업무 수정, 패키지 매니저 수정(ex .gitignore 수정 같은 경우)
      - ADD: 추가이긴 한데 새로운 기능 추가가 아닌 경우(애매한 추가인경우)
      - DELETE: 없앤 경우
      - MODIFY : 수정했을때
      - SET: config 수정등
  - scope
      - 기능 중심
  - message (본문)
      - 변경내용 요약
      - 최대한 자세히
  - 예시

      ```
      feat(board): search api 추가
      add(board): search api 예외사항 코드 작성
      chore: server IP 변경
      style(main): 코드 포맷R팅
      docs: server readme 수정 

      #Dr.[FEAT]: (chat)first commit 
      #Cap.[FIX]: (chat)스크롤 기능 수정
      #Hul. [DOCS] : README.md
      #Tho. [STYLE] : thunder!
      ```


## :bulb: Project Architecture

|구성도|세부 구성도|ERD|
|---|---|---|
|<img src="" width="500px" />|<img src="" width="700px" />|<img src="" width="500px" />


* [Notion(협업도구)](https://www.notion.so/MES-Project-89e0c7d3fb4840adad8451d4be2ec475)