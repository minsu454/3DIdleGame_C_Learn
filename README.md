# 2D 클릭커 게임

### 필수 기능 가이드
    * 클릭 이벤트 처리
        * Input System을 사용
    * 자동클릭
        * 코루틴으로 구현
    * 점수 시스템
        * 점수 시스템을 통화와 합쳐버렸다.
    * 아이템 및 업그레이드 시스템
        * 업그레이드시 데미지가 쌔집니다.
    * 게임 내 통화 시스템

### 사적 도전
    * UIManager (Addressable사용)
    * SceneLoader를 사용해 로드 우선순위 결정
    * Addressable을 사용해 데이터 저장 및 불러오기
    * baseScene을 이용한 동적 생성 구현(Manager 분할이 나을 수도?)