# career

## Branch 전략
- main 
  - 완성품 형태
- develop
  - 기능 개발 완료 후 
  - 작은 단위로 나눠서 분기를 develop에서 시작
- feature/[구현기능]
  - 대단위 - 작은 단위로 나눠서 Task를 최대한 쪼개서
  - feature 단위를 더 작게 쪼개도 되지만, 기본 분기는 develop으로
  - feature 브랜치 자체를 push해서 중앙저장소에 반영
  - 구현이 다 됐다면 develop에 Pull Request해서 코드 리뷰하고 merge하기
  - 그리고 구현 완료된 브랜치 delete
  - feature/title_html

## Commit Convention
- 그 날 작업한 내용 요약해서 저장
- 개괄식으로 작성 `README 작성`

## Code Review
- 주석이 이해 안가거나 모르는 부분이 있다면 코멘트 남기기
- 그 외에 코드 퀄리티적인 부분 개선사항 코멘트 남기기(들여쓰기, 패키지 구조등)

## Issue & Project
- 구현하고자 하는 기능(Feature)
- 깃허브 상에서 충돌 혹은 오류가 발생시(BugFix)
- 제안 및 계획 추가(당장 구현하지 않더라도)(Docs)
- 코드 리팩토링(클린 코드, 도식화)(Refactor)
- Pull Request에도 필요한 경우 label을 달 수 있음
  - Question
  - Help


