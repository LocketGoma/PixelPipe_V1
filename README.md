# PixelPipe_V1
자체 엔진 PixelPipe Version 1 개발용. 

### 목표

상용엔진... 급은 아니라도 에디터 기반의 개발이 가능한 엔진 개발


### 예상 기간
엔진 개발 및 샘플 게임 개발 완료까지 약 6개월 ('22 6~7월 완료 예정)


### 기술 스택

##### Base Graphics Engine : DirectX 12
##### Base Physics Engine : PhysX
##### Base Sound Engine : Wwise


### To do list

1. 기본적인 멀티 스레드 구축
2. FBX Loader
3. 파티클 툴, 오브젝트 배치 툴
4. 네비매시 자동 구축 (실제 맵 좌표에 따라 작동으로 구축해주기)
5. 파일 외부 입출력을 통한 비 고정형 키 입력 시스템 구축 (키 설정 변경기능 추가) / Config 설정 가능하게 추가
6. 고정 FPS, 가변 FPS 기능 추가
7. DeltatTme 기반 타임스탬프 
8. Debug (/DevMode), Release (/ProductionMode) 구별해서 개발하기.


### 하고 싶은것
1. 물 표현 넣기 (물리 포함!)
2. (총기 사용시) 설정에 따른 비 고정형 / 고정형 반동패턴 구현
3. 쉽게 사용가능한 충돌체 처리 (기본 OBB, 고정형은 AABB)
4. RenderGraph 적용
5. 로딩스레드가 포함된 스레드 풀 구축
6. 물체 드래그 & 드랍 배치
7. 멀티플레이어 (네트워크) 


### V2 개발시 들어갈것
1. 자연스러운 애니메이션 전환 (V1에서는 대부분 정적 오브젝트 / 단순 애니메이션만 사용 예정)
