# Java-Menual

- 안녕하세요 오늘은 자바 프로그래밍의 첫 시간으로 자바 개발 환경 세팅을 해보겠습니다. 

- 자바 프로그래밍을 하기 위해서는 JDK와 IDE(통합 개발 환경)이 필요한데요.

- 통합 개발 환경의 종류는 Eclipse, jetbrains의 IDEA, Netbeans등 다양한 소프트웨어가 있습니다.(편하신 걸 사용하시면 됩니다.)

- 여기서 JDK와 JRE의 차이점에 대해서 궁금한 분들이 계실 수도 있습니다. 이를 설명한다면 다음과 같습니다.
> JDK : JDK는 JAVA Development Kit의 약자로 자바 개발자 환경을 의미합니다.
JRE : JAVA Runtime Environment로 JAVA 실행 환경을 의미한다.

- 자, 그럼 제일 먼저 JAVA 개발환경에서 가장 필요한 JDK를 설치해보겠습니다.

- 해당 사이트로 이동해주세요(jdk16) -> https://www.oracle.com/kr/java/technologies/javase-jdk16-downloads.html

![](https://images.velog.io/images/dsph9245/post/e1f9d53e-43b1-41e5-8ee6-0b84b88df37f/1.PNG)

- 그런 다음에 자신의 운영체제에 호환되는 설치 파일을 다운 받습니다. 

![](https://images.velog.io/images/dsph9245/post/31d6d9c2-4f93-4a4f-a080-f7c83eab7342/2.PNG)

- 동의를 해주고 계속 진행해줍니다.

![](https://images.velog.io/images/dsph9245/post/085d346e-eab6-465e-b53f-0d4c60c3081e/3.PNG)

- 계속 Next를 눌러서 설치를 진행해줍니다.
![](https://images.velog.io/images/dsph9245/post/30f50b28-e5fb-46dd-9f28-7ac14a673bc0/4.PNG)![](https://images.velog.io/images/dsph9245/post/fda1a06e-8d3b-4e42-8767-2eeaf6ee7650/4.PNG)

![](https://images.velog.io/images/dsph9245/post/5db9aefa-0084-4a21-a321-aa61573c0071/5.PNG)

![](https://images.velog.io/images/dsph9245/post/f90427a4-039c-4e67-ba42-8ec943523b17/6.PNG)

- 그 다음으로 IDE(통합 개발 환경을 설치해보겠습니다.
- 저는 jetbrains의 IDEA를 기준으로 설치하겠습니다.

- 먼저 jetbrains의 사이트에 접속해줍니다. -> https://www.jetbrains.com/

- Developer Tools에서 IDEA를 클릭해줍니다.

![](https://images.velog.io/images/dsph9245/post/b3b0b2cc-f328-4a91-a6e1-a9703929cc9e/1.PNG)

- Download를 눌러줍니다.

![](https://images.velog.io/images/dsph9245/post/5d26e18b-495c-41a2-b4ff-1d8f622ea1f5/2.PNG)

IDEA는 무료 버전인 Community버전과 유로 버전인 Ultimate버전이 있습니다. 원하는 버전으로 다운받아줍니다. (저는 Ultimate버전으로 진행하였습니다.)

- 그리고 나서 앞에서 JDK를 설치했던 것처럼 설치를 진행해줍니다.

![](https://images.velog.io/images/dsph9245/post/07195d90-67ac-4dae-a496-0ad1eab553a7/3.PNG)

- 다음으로는 프로젝트 생성 및 코드 실행을 해보겠습니다.

- 아이콘을 실행해서 열어본 후 New Project를 눌러줍니다.
![](https://images.velog.io/images/dsph9245/post/2e3f7be2-aa5e-4f46-b0e8-d91152a1714c/4.PNG)

- New Project에 들어오면 다양한 언어 및 다양한 환경의 개발 환경을 지원하는데 저희는 Java를 선택하고 Next를 눌러 진행해주겠습니다.

![](https://images.velog.io/images/dsph9245/post/a1737ff6-1e06-4d45-9fe4-c32626fee403/5.PNG)

- Next를 눌러 계속 진행해줍니다.

![](https://images.velog.io/images/dsph9245/post/f4d94186-1612-40db-aed0-9c3802ebf955/6.PNG)

- Project name의 경우 자신이 원하는 이름을 지정하면 되고 전에 만들었던 프로젝트명 즉, 동일한 프로젝트명은 사용할 수 없습니다.

![](https://images.velog.io/images/dsph9245/post/54ff520b-0c05-4556-8a4e-fab6a727ee3d/7.PNG)

- 프로젝트 생성을 완료하면 다음과 같은 UI를 볼 수 있습니다. (앞으로 우리가 개발을 진행할 통합 개발 환경입니다.)

![](https://images.velog.io/images/dsph9245/post/56b90aa3-039b-4359-b5aa-4cc9ef6c4344/8.PNG)

- src를 우클릭해서 New -> Java Class를 클릭해서 자바 클래스(.java파일)를 생성할 수 있습니다. (첫 글자는 대문자를 사용한다.)

- 저는 Main이라는 이름으로 Class를 생성하겠습니다. 

![](https://images.velog.io/images/dsph9245/post/dcec2315-ec85-4f13-b5dc-c754ac72079b/9.PNG)

- Class를 생성하고 나서 Main.java 파일을 확인해보면 이렇게 작성이 된 것을 볼 수 있습니다.

![](https://images.velog.io/images/dsph9245/post/b861419c-ed63-489c-8f89-6ed7c9c1c7f2/10.PNG)

- 그럼 닉네임을 출력하는 코드를 빠르게 작성해보겠습니다.

- 아래를 보면 닉네임을 출력하는 소스가 작성되어 있습니다.


![](https://images.velog.io/images/dsph9245/post/beda0002-bb2b-48d6-b1a5-872d4a7b368a/11.PNG)

- 이를 실행시키기 위해서는 Add Configuration을 통해서 JDK와 연결을 해주어야 합니다.

- Add Configuration을 눌러줍시다.

![](https://images.velog.io/images/dsph9245/post/0c1034b6-b013-4f1f-93c1-fbb8bd9f1617/12.PNG)

- Add Configuration을 눌러 설정 창에 들어왔다면 좌측 상단의 +를 눌러서 추가를 해줍니다.

![](https://images.velog.io/images/dsph9245/post/896452ee-c462-4d0d-b475-81d3a3213f71/13.PNG)

- Application을 클릭하고 Name은 사용자지정 Main Class는 아까전에 만들었던 Class name으로 지정해줍니다.

![](https://images.velog.io/images/dsph9245/post/ad4a8a1f-2789-4974-836c-cff5ed4985e1/14.PNG)

![](https://images.velog.io/images/dsph9245/post/643395f4-d94e-4181-a326-994bfc749e2c/15.PNG)

- 이제 실행을 해보겠습니다. 우측 상단의 RUN 버튼을 눌러줍니다.

![](https://images.velog.io/images/dsph9245/post/fb42bf1a-a870-49e3-9738-bfb2e5afc453/16.PNG)

- RUN 버튼은 다음과 같이 생겼습니다.

![](https://images.velog.io/images/dsph9245/post/45d69d6d-3f96-4e1f-b307-203c40bd5df8/17.PNG)

- 실행결과를 확인해보면 정상적으로 나오는 것을 확인할 수 있습니다. 

![](https://images.velog.io/images/dsph9245/post/55b65c44-2823-4f20-acdd-6a9a130e1c96/18.PNG)

