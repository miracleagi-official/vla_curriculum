# Online Track Workspace

## 목적

이 디렉터리는 온라인 시뮬레이션 트랙의 상세 설계를 모듈 단위 문서로 분리해 관리하기 위한 작업 공간이다.

- 상위 개요 문서: [../online_curriculum.md](../online_curriculum.md)
- 기준 흐름: `LeRobot/SO101 맥락 -> Isaac Sim 실습 -> Isaac Sim/Omniverse 활용 확장`
- 현재 상태: 폴더 구조와 모듈별 상세 문서 골격 생성 완료

## 구조

- `modules/`: 모듈별 상세 설계 문서
- `references/`: 운영 공통 기준, 평가, 환경 메모

## 모듈 맵

| 모듈 | 차시 | 파일 | 역할 |
|---|---:|---|---|
| 1 | 1-3강 | [modules/module_01_lerobot_pipeline.md](./modules/module_01_lerobot_pipeline.md) | 이 수업 소개와 LeRobot 큰 흐름 보기 |
| 2 | 4-9강 | [modules/module_02_so101_task_and_evaluation.md](./modules/module_02_so101_task_and_evaluation.md) | SO101이 할 일 정하고 결과 판단하기 |
| 3 | 10-16강 | [modules/module_03_isaac_sim_foundations.md](./modules/module_03_isaac_sim_foundations.md) | Isaac Sim으로 장면 만들기 기초 |
| 4 | 17-25강 | [modules/module_04_mirror_task_design.md](./modules/module_04_mirror_task_design.md) | 로봇이 움직일 연습 장면 만들기 |
| 5 | 26-31강 | [modules/module_05_simulation_data_and_evaluation.md](./modules/module_05_simulation_data_and_evaluation.md) | 데이터셋 만들고 간단한 코드 써보기 |
| 6 | 32-35강 | [modules/module_06_mini_project.md](./modules/module_06_mini_project.md) | Omniverse와 Isaac Sim 활용 넓히기 |

## 공통 참조 문서

- [references/environment_and_delivery.md](./references/environment_and_delivery.md)
- [references/evaluation_and_outputs.md](./references/evaluation_and_outputs.md)

## 작업 원칙

- 상위 방향과 차시 수는 `online_curriculum.md` 기준을 유지한다.
- 세부 강의안, 과제, 실습 절차는 모듈 파일에서 확장한다.
- 공통 규칙은 모듈마다 중복 작성하지 않고 `references/`로 모은다.
