# 게임 클라이언트 프로그래머 포트폴리오

C++을 중심으로 게임 클라이언트 개발을 공부하고 있습니다. WinAPI와 DirectX를 활용한 프로젝트에서 캐릭터 액션·애니메이션, 전투 시스템, UI와 맵 편집 도구를 구현했습니다.

**학습·사용 기술:** C++ · WinAPI · DirectX 9 · DirectX 11<br/>
**GitHub:** [hyeons820](https://github.com/hyeons820)

## 프로젝트

각 프로젝트의 **상세 포트폴리오**에서 시연 GIF, 담당 기능의 구현 설명과 코드 샘플을 확인할 수 있습니다.

| 프로젝트 | 형태 · 기술 | 주요 구현 및 담당 업무 |
| --- | --- | --- |
| [Zenless Zone Zero](https://github.com/hyeons820/DX11_ZenlessZoneZero_Portfolio#readme) | 개인 · C++ / DirectX 11 | 맵·내비게이션 에디터, 캐릭터 애니메이션·전투, 카메라 연출, 툰 셰이딩 |
| [Dave the Diver](https://github.com/hyeons820/DX9_DaveTheDiver_Team_Portfolio#readme) | 4인 팀 · C++ / DirectX 9 | 맵 제작, 잠수맵 ESC 인벤토리, 초밥집 운영·일부 UI |
| [Cuphead](https://github.com/hyeons820/WinAPI_Cuphead_Portfolio#readme) | 개인 · C++ / WinAPI | 플레이어 액션, 보스·런 앤 건, 씬 간 데이터 연동, 상점·인벤토리 |

## Zenless Zone Zero

**캐릭터 액션과 제작 도구를 구현한 DirectX 11 개인 프로젝트**

캐릭터의 조작·애니메이션을 전투 판정과 연결하고, 맵과 내비게이션을 제작할 편집 도구를 함께 구현했습니다.

- **편집 도구:** 오브젝트 생성·피킹·Transform 편집과 맵 저장·로드, 내비게이션 셀 제작을 구현했습니다.
- **애니메이션·전투:** 애니메이션 블렌딩과 루트 모션, 입력 버퍼를 통한 콤보 연결, 차지 스택, 패링·저스트 회피와 타격별 피해 계산을 구현했습니다.
- **카메라·렌더링:** 캐릭터 추적, 등장·궁극기 카메라 연출과 추적 복귀, G-buffer 기반 조명 합성과 툰 셰이딩을 구현했습니다.
- **게임 흐름:** 레벨 간 플레이어 상태 유지, 데미지 숫자 표시, 행동별 효과음·보이스와 BGM 전환을 연결했습니다.

[**상세 포트폴리오 보기 →**](https://github.com/hyeons820/DX11_ZenlessZoneZero_Portfolio#readme)

## Dave the Diver

**잠수 탐색과 초밥집 운영을 구현한 DirectX 9 팀 프로젝트**

맵 제작과 잠수맵 ESC 인벤토리 UI, 초밥집 운영 및 일부 UI를 담당했습니다.

- **맵 제작:** 잠수맵·초밥집 공간 구성과 오브젝트 배치. 맵 저장·로드, 피킹과 속성 편집 도구는 팀원과 공동 구현했습니다.
- **잠수맵 인벤토리:** 목록 스크롤, 슬롯 선택, 물고기 버리기와 UI 갱신을 구현했습니다.
- **초밥집 운영·UI:** 주문 큐, 조리·서빙 연동, 판매 결과 집계와 손님·반쵸의 상태 표시를 구현했습니다. 플레이어 기반 코드에는 본인 담당 상호작용을 추가했습니다.

[**상세 포트폴리오 보기 →**](https://github.com/hyeons820/DX9_DaveTheDiver_Team_Portfolio#readme)

<!-- 대표 GIF는 촬영·업로드 후 추가합니다. -->

## Cuphead

**플레이어 액션과 스테이지 진행을 구현한 WinAPI 개인 프로젝트**

**개발 기간:** 2025.10.27 ~ 2025.11.07 (약 2주)

[![Cuphead 플레이어 액션 시연](https://raw.githubusercontent.com/hyeons820/WinAPI_Cuphead_Portfolio/main/docs/Images/Player_01.gif)](https://github.com/hyeons820/WinAPI_Cuphead_Portfolio#readme)

- **플레이어 액션:** 점프·낙하 상태 분리, 공중 패링, 이동·사격·대시를 구현했습니다.
- **전투와 스테이지:** 체력에 따른 보스 페이즈 전환과 공격 패턴, 런 앤 건 진행을 구현했습니다.
- **데이터 연동:** 씬 이동 시 월드 위치·카메라와 코인·아이템 정보를 유지하고, 구매·장착·전투 적용 흐름을 연결했습니다.

[**상세 포트폴리오 보기 →**](https://github.com/hyeons820/WinAPI_Cuphead_Portfolio#readme)

---

프로젝트는 게임 개발 학습을 위한 비영리 교육용 모작입니다. 원작 리소스의 권리는 각 권리자에게 있으며, 코드 공개 범위와 공동 구현 여부는 각 프로젝트 README에 기재했습니다.
