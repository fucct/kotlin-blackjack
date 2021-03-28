# 블랙잭 🃏

## 용어 정리
hit: 처음 2장의 상태에서 카드를 더 뽑는 것
stay: 카드를 더 뽑지 않고 차례를 마치는 것 
bust: 카드 총합이 21을 넘는 경우
blackjack: 카드 점수가 21점

## 기능 요구사항

- [x] 카드의 숫자 계산은 카드 숫자를 기본으로 하며, 예외로 Ace는 1 또는 11로 계산할 수 있으며, King, Queen, Jack은 각각 10으로 계산한다.
  - [x] 각 카드에는 `suit`, `denomination` 이 있다.
    - [x] `suit` 에는 heart, club, diamond, spade 가 있다.
    - [x] `denomination` 에는 ACE, 2 ~ 10, Jack, Queen, King 이 있다.
- [x] 랜덤한 카드를 deck에서 뽑아 준다.
- [x] 플레이어는 이름을 가진다.
  - [x] 이름은 공백이 될 수 없다.
- [x] 게임을 시작하면 플레이어는 두 장의 카드를 지급 받는다.
- [x] 두 장의 카드 숫자를 합쳐 21을 초과하지 않으면서 21에 가깝게 만들면 이긴다.
- [x] 21을 넘지 않을 경우 원한다면 얼마든지 카드를 계속 뽑을 수 있다.

- [x] 딜러는 처음에 받은 2장의 합계가 16이하이면 반드시 1장의 카드를 추가로 받아야 하고, 17점 이상이면 추가로 받을 수 없다.
- [ ] 딜러가 21을 초과하면 그 시점까지 남아 있던 플레이어들은 가지고 있는 패에 상관 없이 승리한다.
- [x] 게임을 완료한 후 각 플레이어별로 승패를 출력한다.