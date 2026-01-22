# 🗂️ QA Workflow Workspace

> **실제 QA 프로젝트를 수행하며 사용한 실행 중심 워크스페이스**  
> 테스트 설계 이전의 판단부터,  
> 테스트 수행·결과·의사결정까지 하나의 흐름으로 관리합니다.

<br>

**Docs → Workspaces → Test Design → Reports → Examples**  

---

## 📁 Workspace Structure
```
📁 docs/
|  # QA의 판단 기준과 설계 사고를 정리하는 문서 영역
|  |
|  ├─ overview/
|  |  # 워크스페이스 목적과 QA 기본 관점
|  |
|  ├─ qa-plan/
|  |  # 일정 · 테스트 범위 · 환경 · 주요 리스크 정의
|  |
|  ├─ spec-review/
|  |  # 기획 명세 QA 리뷰 기록
|  |  # 질문 / 답변 / 반영 여부
|  |
|  ├─ test-design-guide/
|  |  # 테스트 케이스 설계 기준
|  |  # 데이터 · 상태 · 정책 · 모드
|  |
|  └─ decision-log/
|     # 테스트 범위 · 우선순위 · 배포 여부
|     # QA 의사결정 기록
|
📁 workspaces/
|  # 프로젝트 단위 실제 테스트 작업 공간
|  |
|  ├─ test-cases/
|  |  # 데이터 · 상태 · 정책 기준 테스트 케이스
|  |
|  ├─ test-data/
|  |  # 테스트 계정 · 구독 상태 · 더미 데이터
|  |
|  └─ test-environment/
|     # 단말 · OS · 서버 Phase · 테스트 세팅 정보
|
📁 test-design/
|  # 테스트 설계 산출물 관리
|  |
|  ├─ test-case/
|  |  # 기능별 / 상태별 테스트 케이스
|  |
|  └─ change-impact-note/
|     # 변경사항이 기존 기능에 미치는 영향 분석
|     # 회귀 테스트 범위 판단 근거
|
📁 reports/
|  # 테스트 결과 및 품질 상태 요약
|  |
|  ├─ test-result/
|  |  # Coverage · Pass Rate · 환경별 테스트 결과
|  |
|  ├─ coverage/
|  |  # 테스트 커버리지 지표
|  |
|  └─ known-issues/
|     # 배포 시점 기준 잔존 이슈

```

