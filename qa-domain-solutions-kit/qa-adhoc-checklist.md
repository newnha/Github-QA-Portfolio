## 📁 qa-adhoc-checklist/

> QA Ad-hoc & Edge Case 체크리스트입니다.
> QA가 항상 추가로 확인하는 **기본 모드·환경·상태 조건**을 정리합니다.
> 또는 테스트 설계 시 누락 방지용으로,테스트 마무리 단계에서 해당리스트를 **최종 품질 점검 체크리스트**로 사용됩니다.

<br>

```

📁 test-design-guide/
|  # 테스트 케이스 설계 기준 (QA 공통 기준)
|  |
|  ├─ ui-state/
|  |  # 화면 상태 기준
|  |  |
|  |  ├─ light-dark-mode
|  |  |  # 라이트 / 다크 모드 전환
|  |  |
|  |  ├─ orientation
|  |  |  # Portrait / Landscape
|  |  |
|  |  └─ accessibility
|  |     # 폰트 크기, 스크린 리더, 대비
|  |
|  ├─ network-state/
|  |  # 네트워크 상태 기준
|  |  |
|  |  ├─ offline
|  |  |  # 네트워크 미연결
|  |  |
|  |  ├─ unstable
|  |  |  # 지연, 패킷 손실
|  |  |
|  |  └─ reconnect
|  |     # 끊김 후 재연결
|  |
|  ├─ user-state/
|  |  # 사용자 상태 기준
|  |  |
|  |  ├─ paid
|  |  |  # 유료 구독 상태
|  |  |
|  |  ├─ free
|  |  |  # 무료 사용자
|  |  |
|  |  ├─ expired
|  |  |  # 구독 만료
|  |  |
|  |  └─ blocked
|  |     # 이용 제한 / 차단 상태
|  |
|  ├─ device-context/
|  |  # 디바이스 환경 기준
|  |  |
|  |  ├─ os-version
|  |  |  # OS 종류 및 버전
|  |  |
|  |  ├─ device-model
|  |  |  # 단말 모델별 차이
|  |  |
|  |  └─ multi-device-sync
|  |     # 복수 디바이스 동기화
|  |
|  └─ data-state/
|     # 데이터 상태 기준
|     |
|     ├─ exists
|     |  # 데이터 정상 존재
|     |
|     ├─ empty
|     |  # 데이터 없음
|     |
|     ├─ partial-sync
|     |  # 일부만 동기화된 상태
|     |
|     └─ expired
|        # 만료된 데이터

```
