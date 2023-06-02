# HakSulJe
FIRE_MAZE

본 프로젝트는 세종대학교 소프트웨어학과 학술제에 참여하여 팀원들과 함께 만든 게임입니다.

[게임 개요]
- C언어로 개발된 2인용 게임입니다. (VS에서 콘솔창을 통해 게임을 실행할 수 있습니다.)
- 플레이어는 맵 내의 소화기/소화전 아이템을 습득하여 불을 끌 수 있습니다.
- 소화를 통해 길을 개척하여 맵에서 탈출하면 맵을 클리어할 수 있습니다.


[게임 방식]
- 제한 시간 내에 플레이어 모두가 해당 맵의 탈출구로 도착해야 성공
- (불에 뛰어들거나, 시간이 다 되었거나, 엘레베이터에 뛰어들 경우 gameover)

  <도착지점>
  - 도착지가 딱 2개인경우 : p1 p2 각각의 색과 동일한 색의 별로 들어가야 함
  - 도착지가 3개 이상인 경우 : 별 중 아무데나 들어가야함 (다만 서로 다른 별이어야함)

  <소화방법>
  - 소화기
      - 가지고 있는 소화기를 사용하여 상하좌우 불을 끌 수 있음
      - 소화기는 최대 5개까지 보유 가능
  - 소화전
      - 소화전을 먹는 순간, 먹은 뒤 10초간 소화전을 사용할 수 있음
      - 소화기를 보유하고 있더라도, 소화전을 먹은 10초간은 소화전을 우선 사용하게 됨

   - 플레이어1 (p1) : 조작 방식
      - 상하좌우 이동 : wasd키
      - 소화기, 소화전 : tap키

   - 플레이어1 (p2) : 조작 방식
      - 상하좌우 이동 : 키보드 방향키
      - 소화기, 소화전 : 숫자 0 입력

[개발 과정]
2022.11.02 ~ 2022.11.31
 - 표본 맵 제작 (11.02 ~ 11.23)
 - 게임 단계 제작 (11.13 ~ 11.26)
 - 분할 컴파일 및 UI 제작 (11.21 ~ 11.31)
