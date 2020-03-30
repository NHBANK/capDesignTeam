# capDesignTeam

```
저와 같이 카페에 자주 (1주 4~5회) 가는 사람들은 카페 자리에 많은 신경을 쓰게 됩니다.
왜냐하면 카페에서 커피를 시키고 개인 과제, 팀플, 공부, 일기쓰기 등 여러 작업을 오랫동안 앉아서 수행하기 때문입니다. 
특히, 요즘 온라인 개강으로 인해 점심 전에 일찍이 자리를 잡지 않으면 카페에서 위의 언급된 것들을 하기 힘든 상황입니다. 
그래서 최근 한 달 동안 카페에 자리가 남아 있는 지 없는 지에 대해 여부를 알 수 있다면 정말 편할 것 같다는 생각이 들곤 했고, 
마침 이번 학기에 수강하는 캡스톤디자인 수업에서 사물인터넷을 이용하여 프로젝트를 한다는 것을 떠올려 
제가 고민하던 것을 한 번 적용시켜 보면 어떨까 하는 생각을 해 보았습니다.

우선, 사물인터넷 핵심 기술 중 하나인 센싱 기술을 이용하는 방안이 있습니다.

1. 자리 확인용 센서 (버튼 센서 / 압력 감지 센서 / 열 감지 센서 등)
카페를 단순히 '커피를 시켜 마시는 곳'이 아니라 '자리를 이용하기 위한 곳'이라는 
패러다임의 전환을 통해 자리 확인용 센서를 만들 것입니다. 
>> 1-(1) 버튼 센서 이용 : 주문 전에 이용 고객이 자리를 먼저 잡고, 
앉게 되면 버튼을 누름으로서 자리 이용 중임을 서버에 알리게 됩니다.
>> 1-(2) 압력 감지 센서 이용 : 고객이 자리에 앉게 되면, 
압력 감지 센서를 통해 사람이 앉았다는 것을 인식하고 자동으로 자리 이용 중임을 서버에 알리게 됩니다.
>> 1-(3) 열 감지 센서 이용 : 고객이 자리에 앉게 되면, 
열 감지 센서를 통해 사물이 있는 것인 지, 사람이 앉았다는 것인 지에 대한 여부를 인식하고 
자동으로 자리 이용 중임을 서버에 알리게 됩니다. 

2. 음료 확인용 센서 (음향 센서)
고객이 주문한 음료가 나왔는 지 알려주는 센서를 만들 것입니다.
>> 음향 센서 + 압력 센서 + 버튼 센서 이용 : 주문을 하게 되었을 때 
제조자가 제조를 마치게 되면 해당 자리의 버튼을 누르고(버튼 센서), 
그 잔을 가져가는 곳에 두면(압력 센서) 버튼 센서와 압력 센서가 모두 입력이 된 상태면 
음향 센서로부터 음악이 해당 자리에 앉은 고객에게 들리게 합니다.


그리고, 사물인터넷의 또 다른 핵심 기술인 인터페이스 기술과 네트워킹 기술을 이용하는 방안이 있습니다.

3. 어떤 자리가 점유되어있는 지에 대한 데이터 통신 (서버 프로그래밍)
위에서 언급된 자리 확인용 센서로부터 어느 자리가 차 있는지에 대한 데이터를 
애플리케이션과 같은 프론트 쪽으로 쏴줍니다. 그러면, 그 데이터를 이용해 
카페 근거리에서는 카페 앞 모니터를 통해 좌석의 유무를 알 수 있고, 
집이나 원거리에 위치한 사람들은 애플리케이션을 통해 좌석의 유무를 알 수 있어, 
그 해당 카페를 이용하러 갈 지 말 지에 대한 판단을 하게 도와줍니다.


```
