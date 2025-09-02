## Welcome to My Github

### 학력
- 인하대학교, 항공우주공학과 4학년 재학 중

### 군경력
- 2020.01 ~ 2022.01 (육군)

### 학부 (연구) 인턴 경력
1. **KIST Research Intern (2023.09 ~ 2023.12)**
2. **Inha RCV Lab. Research Intern (2024.09 ~ 2025.02)**
3. **Aerosolutions Inc. Intern (2022.06 ~ 2022.08)**

### 수상 실적
1. 인하대학교 공과대학장상 (2019.12)
2. 인하대학교 프로젝트Lab 항공우주요소설계 경진대회 은상 (2025.06)
3. 항공우주시스템공학회 전국 대학생 캡스톤 경진대회 한화에어로스페이스대표이사상 (2025.09)

### 참여한 프로젝트
- **아두이노 기반 소형 드론 설계 (2019.08 ~ 2019.12)**
  - 아두이노 기반 기본적인 PID 제어기 튜닝 및 초소형 쿼드콥터 개발
- **제22회 로봇항공기 경연대회 (2024.03 ~ 2024.11)**
  - Depth Camera를 사용한 장애물 탐지 및 회피 구현 (PX4 Avoidance)
  - ROS2와 PX4를 통한 오프보드 비행 계획 및 비행 제어 구현
- **F1TENTH 대회 출전 (2024.09 ~ 2025.02)**
  - Cartographer 기반 Mapping 및 Localization 구현
  - 오픈소스 기반 Global Path Planning, Pure-Pursuit Controller 구현
  - Gazebo classic 기반 F1TENTH Simulation 구현
  - Gazebo Harmonic 기반 F1TENTH Simulation 구현

### 참여 중인 프로젝트
- **항공우주 종합설계 (2025.03 ~ present)**
  - 3차원 공간에 대한 자율 탐사를 수행하는 ROS2, PX4 기반의 실내 드론 시스템 개발
  - HW는 다음 내용을 포함할 예정임
    - RGB-D 카메라를 통합해 실내 VIO를 수행하는 헥사콥터 개발
    - 3D LiDAR를 통합해 실내 LIO를 수행하는 헥사콥터 개발
  - SW는 다음 내용을 포함할 예정임
    - Octomap 기반 3차원 Frontier 생성 및 평가
    - A* 기반 두 전역 경로점 사이 Path Planning
    - TSP 기반 최적의 Frontier 순회 경로 생성
    - APF 기반 Dynmaic Obstacle Avoidance 구현
    - 모든 SW를 LifeCycle로 구성하여, 사용자와의 손쉬운 상호작용 및 상태 천이 구현
  - 현재까지 구현된 내용은 다음과 같음
    - PX4 SITL (Gazebo Harmonic) 기반 자체적인 시뮬레이션 모델 구현
    - RTAB-MAP, m-Explore, Nav2에 기반한, 고도를 고정한 2차원 자율탐사/경로생성 소프트웨어 스택 구현
- **제 23회 로봇항공기 경연대회 (2025.03 ~ present)**
  - SW 팀장 담당
  - 다음과 같은 SW를 개발함
    - WGS84로 주어진 좌표점들에 대한 경로점 자율 비행
    - 단안 카메라, AprilTag 기반 멀티콥터, VTOL 기체의 정밀착륙
    - YOLO 기반 BBox를 기준으로, 탐지된 객체를 향한 접근 및 호버링
- **인하 종합설계 경진대회 (2025.04 ~ present)**
  - 시뮬레이션 상에서는 월면, 현실에서는 GPS 없는 실내에서 자율적으로 탐사를 수행하는 로버 개발
  - Gazebo Harmonic 기반 로버 시뮬레이션 환경 구성
  - Depth Camera, IMU, 2D LiDAR, Visual Odometry를 복합적으로 사용하는 로버 구현
  - Frontier - Based Autonomous Exploration과 Nav2를 결합해서 자율 탐사 기능 구현
  - YOLO와 MoveIt2!를 결합한, 로봇팔 통합 기획 진행 중
- **AuTURBO 드론 프로젝트 (2025.04 ~ present)**
  - PX4, ROS2 Humble, AirSim을 통한 드론 SW 개발 프로젝트
  - TBD

### 사용 가능 Tool
ROS1, ROS2, Gazebo(classic/Harmonic), Python, C++

### 대표 리포지터리 주소
- [F1TENTH_Simulation](https://github.com/kimhoyun-robotair/F1TENTH_Simulation) : Gazebo Classic 기반 자체적인 F1TENTH 시뮬레이션
- [Gazebo_Harmonic_Rover](https://github.com/kimhoyun-robotair/Gazebo_Harmonic_Rover) : 위의 시뮬레이션을 Gazebo Harmnoic으로 Migration한 자체적인 F1TENTH 시뮬레이션
- [RCV Formula Repositories](https://github.com/orgs/rcv-formula/repositories) : F1TENTH 관련 개발 코드, 이 중 SLAM / Global Path Planner / Pure Pursuit 기반 Controller 개발 주도
- [DOK4](https://github.com/kimhoyun-robotair/DOK4) : 2025년도 제 23회 로봇항공기 경연대회 참여 코드
- [DARAM-G](https://github.com/kimhoyun-robotair/DARAM-G) : 2025년도 인하 종합설계 경진대회 / 전국 대학생 캡스톤 경진대회 참여 SW 스택
