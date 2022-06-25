# 객체지향의 사실과 오해 : 2022.05.28 ~ 
<img src='http://image.yes24.com/momo/TopCate511/MidCate005/51040273.jpg' width="200"/>






## 목차

|챕터|제목|키워드|
|---|---|---|
|1장|협력하는 객체들의 공통체|자율적인 객체들의 협력 / sw객체의 자율성 / 객체간 메시지 - 협력 / 완전연결성 / |
|2장|이상한 나라의 객체|객체란 상태와 행동, 식별자를 가진 존재|
|3장|타입과 추상화|추상화 = 동적인 객체들을 단순화, 정적인 타입으로 갈무리 = 클래스를 사용하는 이유|
|4장|역할, 책임, 협력|객체지향의 핵심 = 역할, 책임, 협력|
|5장|책임과 메시지|객체지향 설계의 기반 = 훌륭한 메시지 = 객체의 자율성과 설계의 유연성|
|6장|객체 지도|구조관점+기능관점 조화 / 도메인 모델|
|7장|함께 모으기||
|부록|추상화 기법||


---

## 기록

| 날짜 | 챕터 | 기록 |
|:------:|:------:|:--------:|
|22.06.26|1장#2|사회적 이벤트가 발생하는 어디에서나 [역할,책임,협력]이 존재하며 이는 객체지향 패러다임에서 가장 중요한 기반 개념이다. 커피주문이라는 공동의 '협력'이 필요할 때, 이에 참여하는 자들은 손님,캐시어,바리스타라는 '역할'을 갖게되며 이 협력의 달성을 위해 역할에 따른 '책임'을 수행한다.|
|-|1장#3|'협력'은 [요청,응답]으로 구성되어있다. 한 '역할'을 담당하는 구성원이 스스로 해결하지 못하는 문제를 마주치면 해당 책임을 수행할 수 있는 타 역할자에게 '요청(request)'하며, 이를 수행한 역할자는 요청자에게 '응답(response)'한다. 일반적으로 하나의 문제를 해결하기 위해 여러 역할의 참여가 요구되기 때문에, 하나의 요청은 또한 3자,4자에 대한 연쇄적 요청을 야기한다. 응답 또한 요청의 반대 방향으로 연쇄적으로 전달된다. 협력의 성공은 특정한 역할을 맡은 각 개인이 얼마나 요청을 성실히 이행하는가에 달려 있다.|  
|-|1장#4|'협력'을 위해 참여자들은 '역할'을 부여받는다. '역할'은 참여자가 협력 내에서 차지하는 ['책임' 혹은 '의무']를 의미한다. '역할'은 '책임'을 내포하며, 특정 역할은 특정 책임을 암시한다. 역할과 책임은 협력의 원활한 진행을 위한 필수요소이다. "다자는 동일한 역할을 수행할 수 있다 (N:1)" = "역할은 대체 가능성을 의미한다(substitutable)", "응답자에 따라 요청의 책임 수행하는 방법으로써 자율적으로, 서로 다른 방식을 사용할 수 있다.즉, 동일 요청, 다양한 방법의 응답(다형성:polymorphism = 1:N)", "한사람이 동시에 여러 역할을 수행할 수 있다"(1:N), 즉 역할과 사람은 N:N이다.
|
|22.05.29|1장#1|실세계의 모방. 즉, '실세계 객체 : SW 객체' 대응은 객체지향 설계의 핵심사상인 완전연결성(seamlessness)의 학습과 이해에 효과적이지만 그 본질이라고 할 수 없다. 오히려 실세계의 문제 해결을 위한 현실의 효과적 재구성이라고 보아야 할 것. / 객체는 자율성을 가지고 상태와 행위를 캡슐화 한다. 객체들은 메시지를 주고받으며 공동의 목표를 위해 협력하는 관계를 가진다.| 
|22.05.28|서문|객체지향은 추상화, 캡슐화, 상속, 다형성 이라는 중요한 특징을 가진 패러다임. SOLID 원칙을 사용하면 훌륭한 객체지향 코드를 작성할 수 있으나 많은 이가 객체지향이란 무엇인가에 대한 근본적인 이해가 부족할 수 있으며 클래스나 상속을 중심으로 객체지향을 바라보곤 한다고. 객체지향은 객체를 바라보고, 객체를 독립적인 존재가 아니라 기능을 구현하기 위해 '협력'하는 공동체의 존재로 바라보는 것. 마지막으로 협력에 참여하는 객체들에게 적절한 역할과 책임을 부여할 수 있는가에 달렸음. / 객체지향 패러다임의 핵심은 자율적인 객체들의 협력이다. 객체는 상태와 행동 식별자를 가진 존재이다. 추상화란 동적인 객체들을 단순화시켜 정적인 타입으로 갈무리하는 것이며 이를 위해 타입과 객체를 사용. 객체지향 설계의 가장 중요한 재료는 역할, 책임, 협력 이며 객체들은 협력에 참여하기 위해 특정한 역할을 맡고 역할에 적합한 책임을 수행한다. 훌륭한 메시지가 훌륭한 객체지향 설계의 기반이다. 객체의 자율성과 설계의 유연성은 얼마나 훌륭한 메시지를 선택하느냐에 달림. 구조는 기능에 비해 변화에 더 안정적이다. 따라서 객체지향 패러다임은 객체들의 구조 안에 기능을 녹임으로써 변화에 안정적인 SW개발을 가능하게 한다.|

