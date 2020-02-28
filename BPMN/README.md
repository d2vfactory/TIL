# TIL - BPMN 공간
> BPMN에 대한 스터디 

## Business Process Modeling Notation
BPM 관점에서 UML의 복잡성을 단순화시킨 새로운 표준
> Actibity Diagram이 가진 부족한 점을 보완하기 위해.
> > UML은 Business Process 보다 S/W 개발 관점에서 접근하기 때문에 다소 부족한 점이 있었음.  
- 2005 : BPMN 1.0
- 2011 : BPMN 2.0

## 기본 구성
| | 내용|
:-: | :--
Basic | 가장 기초적인 구성 <br/> 도형도 간단하기 때문에 기술자가 아니어도 적용하기 쉬움.
Core | S/W 엔지니어들이 보는 기본적인 단계 <br/> Basic 보다 세분화된 구성으로 시스템 구현의 Actibity에 대한 세부 분류 및 예외 처리 표현 가능.
Advanced | 실제 코드를 다이어그램으로 표현하는 수준 <br/> Core 보다 더 S/W 엔지니어링에 가깝도록 세분화 되어있음.


## BPMN의 요소들.
BPMN은 무조건 Start Event로 시작해서 Activity를 표현하고 End Event로 종료한다.

### Event
- Start
- Intermediate
- End

### Activity (Task)

### Connections
- Sequence Flow
 <br/> 프로세스의 흐름. Activity를 비롯한 Element들을 이어준다.
 <br/> ![SequenceFlow](SequenceFlow.png)
- Message Flow

- Association
  
### Gateway



## 참고 링크
> [비즈니스 프로세스를 그리자](https://medium.com/@goldfing/%EB%B9%84%EC%A6%88%EB%8B%88%EC%8A%A4-%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4%EB%A5%BC-%EA%B7%B8%EB%A6%AC%EC%9E%90-bpmn-2-0-3730b3295dcf
)