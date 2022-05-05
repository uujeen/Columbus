# Columbus (Metabus platform)

# 0. 개요

COVID-19 팬데믹 이후 많은 사람들이 해외뿐만 아니라 국내에서의 이동마저도 어려움을 겪고 있었습니다.

그래서 저희는 가상 공간에서 대리 만족을 느낄 수 있는 방법을 찾으려고 하였습니다.

그 방안으로 저희 프로젝트인 Columbus입니다.

현재 상황과 더불어 거동이 불편한 인원뿐만 아니라, 여러 이동에 제약이 있는 분들에게 도움이 될 수 있습니다.

많은 한국인분들께서는 울릉도를 한번이라도 가본 적이 있냐고 했을때 대부분이 없다고 말할 것 입니다. 그래서 첫번째 프로젝트 내용으로 울릉도를 구현하려고 했습니다. 

지형, 지물들을 생성하고 3D 아바타를 이용하여 울릉도를 탐험하고 미션을 완료하며 가상 화폐와 교환이 가능하게 하는 것이 1차적인 목표라고 할 수 있습니다.

# 0-1. TimeLine

21-9~10 - 아이디어 구상 및 정리

21-10~11 - 아이디어 1, 2, 3안 중 택 1 및 구체화 (지형, 콘텐츠, 가상화폐, Web-realtime-camera 등등)

21-12 - 개발 일정 수립 및 아이디어 구체화

22-1-17~23 - UnrealEngine 사용 연습 및 툴 연습

22-1-24 - 작업 분배 및 일정 토의 (동훈 - 지형 , 의진 - 아바타)

22-1-28 - 지형, 건축물 및 아바타 제작 관련 방안 탐색 ( Height Map, Maya program) 

22-2-7 - 지형 초안 제작, Columbus 코인 제작 , 코인 거래 방법 재구상, realtime- 적용 방법 모색)

22-2-15 - Realtime 수동 가능, 자동 방법 모색, 아바타 제작 난항 -> METAHUMAN 우회

22-2-28 - QGIS를 이용하여 Height 맵 추출 및 엔진에 적용하여 실제와 유사한 울릉도 모형 제작 진행, METAHUMAN 엔진에 적용시키기

22-3-7 - Heightmapper로 우회, InstantTerra를 이용하여 더 명확한 지형 제작 진행

22-3-15 - InstantTerra 제작 실패(HeightMap 적용 X -> 원하는 결과 도출 X), 150:1 사이즈로 지형 제작, METAHUMAN 엔진에 적용

22-3-24 - Metahumun의 동작 구현, 스켈레톤에 원활한 적용 

22-4-05 - 지형에 도로 1차 제작 및 캐릭터 연동 

22-5-04 - 캐릭터 완성 및 서버 연동 확인

# 1. 협업 (Slack)

- 협업 툴로는 Slack을 사용하고 있습니다. Slack을 통해 총 5개의 테마로 나눠 매 주 소통하고 정리하는 방향으로 나아가고 있습니다.

5개의 테마는 공지사항, 대화, 자료조사, 프로젝트, 회의록으로 나눠 사용하고 있으며
현재는 자료조사와 회의록만 사용하고 있습니다.

### 자료조사

![](https://images.velog.io/images/odh0112/post/a4cc6455-d9b0-480b-af13-4c16d4dacb5c/%EC%9E%90%EB%A3%8C%EC%A1%B0%EC%82%AC.PNG)


### 회의록

![](https://images.velog.io/images/odh0112/post/2196dd34-471b-4611-a324-58ec647d80f8/%ED%9A%8C%EC%9D%98%EB%A1%9D.PNG)

# 2. Content

### 가상화폐

- 코인명 : COLUMBUS
- 총 발행량 :  100,000,000 COL
- 가상화폐 지갑 주소 : 0xA8664f1256bDfF3473B42449a03d07e994053654 <br>

![columbus](https://user-images.githubusercontent.com/71745798/158739595-ea43cbe6-7bbf-483f-8c4c-37daee5cc185.PNG)

### 메타휴먼 

![METAHUMAN1](https://user-images.githubusercontent.com/70149604/158390320-f005c371-9593-40ea-a775-6dba97d3d025.gif)



아 진짜 뚜껑 열리네~!

![METAHUMAN2](https://user-images.githubusercontent.com/70149604/159852013-9620d27c-31e1-48b3-b672-c5424c90a88a.gif)


캐릭터 완성
![Metahuman3](https://user-images.githubusercontent.com/70149604/166860008-ac8b3ae0-59f1-4fa6-857e-8b4d237d0355.gif)


서버 연결 
![Metahuman4](https://user-images.githubusercontent.com/70149604/166860016-cec29591-82e5-471d-80e0-5cf5fc87ac94.gif)


### 지형

<img src="https://user-images.githubusercontent.com/71745798/158739550-a36b4556-8782-4013-af96-f7c5ebfc7406.PNG" width="600"/>

![도로 위 캐릭터](https://user-images.githubusercontent.com/70149604/162118489-28d2a18f-d143-4bcc-bc70-185f3a013d1a.png)


