## 📁 test-design-guide/

> 테스트 케이스 설계 기준 (QA 공통 기준)

>실제 QA 프로젝트에서 테스트 케이스를 만들 때 공통적으로 고려하는 기준과 관점을 정리합니다.
>기능별 테스트뿐 아니라 데이터 상태, 사용자 상태, 디바이스 환경, 화면 모드, 네트워크 조건 등 다양한 상황에서의 품질을 구조적으로 검증하기 위해 사용됩니다.
>각 폴더는 테스트 케이스 설계 시 체크리스트처럼 참고할 수 있습니다.

<br>
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
