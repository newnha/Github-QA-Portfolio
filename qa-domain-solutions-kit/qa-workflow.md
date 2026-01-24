# 🧭 QA Workflow

> 기능을 테스트하기 전에 **무엇을, 왜, 어디까지 검증할 것인지**를 먼저 판단하는 QA의 사고 흐름을 정리했습니다.

<br>

**Planning → Test Design → Execution → Decision**


```
QA-Workflow
|
├─ Planning/
|  # 기획 단계 QA 산출물
|  ├─ QA Plan.md
|  |  # 일정, 범위, 환경, 커버리지 정의
|  |
|  ├─ Spec Review.md
|  |  # 기획 명세 리뷰 & 질의응답 기록
|  |
|  └─ Decision Log.md
|     # 테스트/범위/배포 관련 QA 판단 근거 기록
|
├─ Test-Design/
|  # 테스트 설계 산출물
|  ├─ Test Case.xlsx
|  |  # 데이터·상태·정책 기준 TC
|  |
|  └─ Change Impact Note.md
|     # 변경사항이 기존 기능에 미치는 영향 분석
|
├─ Execution/
|  # 테스트 수행 & 결과
|  ├─ Test Result.md
|  |  # Coverage / Pass Rate / 환경별 결과
|  |
|  └─ Bug Tracking.md
|     # 결함 등록, 상태, Known Issue 관리
|
└─ Assets/
   # 반복 사용되는 기준·가이드·참고 자료
   ├─ Bug Management Guide.md
   |  # 이슈 작성 및 관리 규칙
   |
   ├─ Test Environment Guide.md
   |  # OS, 단말, 서버 Phase 기준
   |
   └─ Debug Tools.md
      # 로그, API, 서버 컨트롤 참고
```
