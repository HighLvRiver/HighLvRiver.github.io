---
layout: post
title:  "Basic Concept of Scrum"
date:   2017-10-07 21:00:00
categories: Python
---

# 1. Role of team member

## 1) Product Owner
- helps make sure the right features make it into the product backlog. 
- representing the users and customers of the product.
- helps set the direction of the product.

## 2) Scrum Master 
- makte sure the project is progressing smoothly and that every member of the team has the tools they need to get their job done.
- sets up meetings, monitors the work being done and facilitates release plnanning.

## 3) Developer 
- build the product.

## 4) Tester 
- test it to makte sure it works right.

## 5) Customer 
- use it.

# 2. Concept of Scrum with JIRA

## 1) User Story : As a (role), I want (feature) { , so that (benefit) }.
- like Use-Case.
- Key point of creating feature list
  - Story (Flow or sequence) : Lv1 Feature 들을 순서대로 이어 놓으면 사용자가 서비스를 사용하는 흐름 형태가 되어야 한다.
  - Testable : 각 Feature는 테스팅이 가능한 수준으로 디테일하게 서술되어야 한다. 스토리대로 각 기능 등이 정의 되어 있으면 스토리를 따라서 테스트 케이스로 만들 수 있다.
  - Designable : 디자이너가 기능에 있는 스토리에 따라서 UX를 만들 수 있는 정도로 충분히 기술되어야 하며, 특히 입력이나 출력을 받을 수 있는 필드가 충분히 기술되어야 한다.

## 2) Agile board : To Do / In Progress / Done
- Epic : 하나의 Sprint에 걸쳐서 끝나지 않고, 여러 Sprint에 걸쳐서 종료되며, 여러 Story들의 집합이다. 주로 Major Feature들을 중심으로 정의한다.
- Story : “as a {user}, I want to {do something}”에 해당하는 사용자 직접적으로 사용하는 기능이다. 이 때 Story Point라는 것을 입력할 수 있는데, Story Point는 개발에 걸리는 시간 또는 난이도 등으로 지정할 수 있다. 
- Chore : 개발을 해야 하는 부분이지만 사용자와 직접적으로 관계되지 않는 개발 내용을 정의한다. 예를 들어 “Server Logging 구현”, “데이타 베이스 분리”와 같은 작업등을 정의한다. Chore 역시 Story와 마찬가지고 Story Point를 부여할 수 있다.
- Task (Optional) : Task는 해야하는 일이지만, 구현에 관련되지 않으며, 일정이 없는 경우에 해당한다. 예를 들어 디자인 문서 작성, 기획과 업무 협의 등이 해당한다.
- Issue : Issue 는 말 그대로 Issue이다. 메니져들이 관리하는 Issue, 예를 들어서 클라우드 계약, 서버 Hang up, 솔루션 결정 들과 같이 메니져들이 관리해야 하는 항목이다.
- Bug : 버그는 테스트 엔지니어에 의해서 테스팅 되고, 버그로 리포팅 된 타입이다.
- Sub Task : Sub Task가 중요한 내용인데, Story나 Chore를 개발하기 위해서는 여러 가지의 실제적인 개발 작업이 필요하다. 예를 들어 “as a user, I want to read posting”이라는 Story가 있을때, “OPEN API를 호출하여 최근글을 JSON으로 호출하여 출력한다.” “API 호출을 로깅한다” 와 같이 디테일한 개발 테스크로 나뉘어 지는데, 이를 Story나 Chore같은 Issue 아래 Child (Sub) Task로 등록할 수 있다.
이때 하나의 팁은 이 Sub Task는 각 개별 개발자에게 할당되며 0.5일~2일 정도에 끝날 수 있는 테스크로 정의되어야 하며, 만약 2일 이상이 될 경우 다른 Sub Task로 나누어 주는 것이 좋다.

## 3) Product Backlog (like wish list) : The collection of all user-stories 

## 4) Release Planning
- identify the user-stories they want to put into this release.
- these user-stories then become part of the release backlog.
- the team then prioritizes the user-stories and estiates the amount of work involved for each item.

## 5) Sprint
- short-duration milesones that allow teams to tackle a manageable chunk of the project and get it to a ship-ready state.

## 6) Burndown Chart
- is the number one reason for Scrum's popularity.
- provies a day-by-day measure of the amount of work that remais in a given sprint or release.

## 7) Daily Scrum
- an essential tool to having communication flow freely between team members.

## 8) Grooming
- 다음 스프린트에 들어가기전에, PO가 다음 스프린트에 개발할 기능에 대해서 대략적으로 리뷰를 하는 행위
- 스프린트 진행 중 일어남
- why. 
   - 다음 스프린트에 대한 가시성 확보 ( 미리 생각할 시간을 준다 )
   - 개발 개시 전 리뷰를 통해서 개발 가능성, 기획 상 구멍들을 찾아서 수정할 시간을 갖는다.

## 9) Story Voting 
- 개발팀 전체가 모여서, 각각의 사용자 스토리에 대해 개발 기간을 투표
- 1 스토리 포인트 = ??? 

## 10) 개발범위(일정) 
- 산출된 포인트로 개발 일정 지정(2~4주)
- 버퍼(회의, 문서, 배포, 오류 수정 등) 배정 필요(1.5배)
- 4주가 넘는 일정은 우선순위에 따라 자름

## 11) Backlog meeting
- 3개월 이상의 장기 제품 개발 로드맵을 정의
- 방법 
   - 매주 또는 격주에 한번 진행
   - 우선 순위 조정 및 주요 기능에 대한 사전 리뷰
   - 에픽 단위의 기능을 정의하고, 우선 순위를 비즈니스 상황에 따라서 변동
- 운영
   - JIRA에 백로그 프로젝트를 별도 구성하거나, 별도 닥스에 정리
   - 위아래 순서로 우선 순위 지정
   - 릴리즈 버전을 부여함으로써 릴리즈에 대한 대략적인 일정 예측