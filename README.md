# 개발을 못해 슬픈 감자
이 프로젝트는 플레이어의 기본 이동 및 점프, 체력바 UI, 아이템 데이터를 구현한 게임 프로젝트입니다.


# <구현 기능>

## 1. 기본 이동 및 점프
플레이어의 이동과 점프 기능을 설정했습니다.

- Input System과 Rigidbody ForceMode를 사용하여 다음과 같은 동작을 구현했습니다:
- 플레이어 이동 (WASD): W, A, S, D 키를 사용하여 플레이어를 앞, 뒤, 좌, 우로 이동시킬 수 있습니다.
- 점프 (Space): Space 키를 눌러 플레이어가 점프할 수 있습니다.




## 2. 체력바 UI
플레이어의 체력을 나타내는 UI를 설정했습니다.
UI 캔버스에 체력바를 추가하고 플레이어의 체력 변화에 따라 UI가 갱신되도록 했습니다.

- 체력바 추가: UI 캔버스에 체력바를 추가했습니다.
- 체력 UI 갱신: 플레이어의 체력이 변할 때마다 체력바가 실시간으로 업데이트됩니다.

<img width="403" alt="image" src="https://github.com/mwomwo1/Chapter03-2-3D/assets/167048411/6200f907-4891-4f6a-98c6-09c46478a9e7">





## 3. 아이템 데이터
다양한 아이템 데이터를 ScriptableObject로 정의했습니다.
각 아이템은 이름, 설명, 속성 등을 포함하며, 이를 통해 아이템을 효율적으로 관리할 수 있습니다.

- 아이템 정의: ScriptableObject를 사용하여 아이템의 데이터를 정의했습니다.
- 속성 관리: 각 아이템의 이름, 설명, 속성 등을 ScriptableObject로 관리합니다.

<img width="280" alt="image" src="https://github.com/mwomwo1/Chapter03-2-3D/assets/167048411/b57bff5a-2e29-4ebf-a088-d4a1871eeb4c">

