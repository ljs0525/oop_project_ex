# 2019-2 객체지향 프로그래밍 프로젝트 - **SNU_GOD_J**
구성원: 3-2 이준성 | 3-6 이제현

## 1. 주제
더 지니어스: 인디언 홀덤 게임

## 2. 동기
평소에 자주 접하던 프로그램인 더 지니어스에서 플레이되는 게임인 '인디언 홀덤'에 관심을 가지게 되었다.
객체지향 프로그래밍을 새로 접하면서 이를 구현할 수 있을 것이라 생각했고, 따라서 프로젝트로 인디언 홀덤 게임 제작을 진행하게 되었다. 

## 3. 프로그램 사용 대상
내기 형식의 게임을 즐기거나 필요한 사람들

## 4. 목적
인디언홀덤 게임의 딜러 역할을 컴퓨터에게 맡김으로써 게임을 별도의 카드 세트나 칩 등을 준비하지 않아도 해당 프로그램을 통해 진행할 수 있게 한다. 
이를 통해 사용자의 게임 접근성을 증진한다. 또한 도박적 요소 외에 게산을 통해 게임을 유리하게 끌고 갈 수 있도록 암호를 도입하였다. 게임 초반은 심리전을 통한 도박으로 기존의 인디언 홀덤 게임과 다를 바 없이 진행되나, 게임이 진행됨에 따라 서로의 암호를 유추함으로써 이를 베팅에 이용할 수 있다.

## 5. 주요기능
1. 게임이 시작되면 플레이어 1, 2의 이름이 입력된다.
2. 게임 진행을 위해 플레이어 1, 2가 각자 자신의 암호를 입력한다.
3. 각자에게 칩이 40개 씩 할당되며, 이후부터 각자는 라운드마다 상대방의 카드를 확인한다.
4. 상대방의 카드를 확인한 이후 첫 순서인 플레이어는 베팅할지 죽을지 결정한다. 또한 베팅 칩 수를 입력한다.
5. 두번째 순서인 플레이어는 상대방이 베팅한 수와 상대방의 카드를 고려하여 베팅할지 죽을지 결정한다.
6. 자신의 카드가 10일 때 죽으면 15개를 잃는다.
7. 이러한 방식으로 라운드가 반복되며, 한 명의 칩이 0개 이하가 되면 게임이 끝난다.
 
## 6. 프로젝트 핵심
암호를 통한 계산 규칙 도입
객체를 통한 각 플레이어 구현
한 컴퓨터에서 멀티 플레이 기능

## 7. 구현에 필요한 라이브러리나 기술
random, class


## 8. **분업 계획**
이제현: 게임 중 에러 관련 코딩
이준성: 게임 규칙 관련 코딩

## 9. 기타

입시 끝나고 할게요! ㅎㅎㅎㅎㅎㅎ
->했어요! ㅎㅎㅎㅎㅎㅎ

* 107, 108줄은 개발자가 확인하기 위한 용도이니 실제 게임 플레이 과정에서는 삭제 바람.
* 146, 147줄을 삭제하는 경우 게임의 난이도가 어려워지니, 이전의 게임이 쉽다고 생각한다면 삭제 바람.
<hr>

#### readme 작성관련 참고하기 [바로가기](https://heropy.blog/2017/09/30/markdown/)

#### 예시 계획서 [[예시 1]](https://docs.google.com/document/d/1hcuGhTtmiTUxuBtr3O6ffrSMahKNhEj33woE02V-84U/edit?usp=sharing) | [[예시 2]](https://docs.google.com/document/d/1FmxTZvmrroOW4uZ34Xfyyk9ejrQNx6gtsB6k7zOvHYE/edit?usp=sharing) | [[예시 3]](https://github.com/goldmango328/2018-OOP-Python-Light) | [[예시4]](https://github.com/ssy05468/2018-OOP-Python-lightbulb) | [[모두보기]](https://github.com/kadragon/oop_project_ex/network/members)
