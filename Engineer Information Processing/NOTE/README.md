# [정보처리기사 - 필기]

<table>
    <tr>
        <td><a href="#tit1" style="text-decoration: none;">1. 소프트웨어 설계</a></td>
        <td><a href="#tit2" style="text-decoration: none;">2. 소프트웨어 개발</a></td>
        <td><a href="#tit3" style="text-decoration: none;">3. 데이터베이스 구축</a></td>
        <td><a href="#tit4" style="text-decoration: none;">4. 프로그래밍 언어 활용</a></td>
        <td><a href="#tit5" style="text-decoration: none;">5. 정보 시스템 구축 관리</a></td>
    </tr>
</table>

## <p id="tit1">1️⃣ 소프트 웨어 설계</p>
### 1. 현행시스템 분석
✏️ 현행 시스템 파악<br><br>
✔️ 현행시스템 파악의 정의<br>
🔸현행 시스템이 어떤 하위 시스템으로 구성되어 있는지<br>
🔸제공하는 기능이 무엇인지<br>
🔸다른 시스템들과 어떤 정보를 주고받는지 ➡️ 인터페이스<br>
🔸어떤 기술요소를 사용하고 있는지<br>
🔸사용하고 있는 소프트웨어 및 하드웨어는 무엇인지<br>
🔸네트워크는 어떻게 구성되어 있는지
<br><br>
✔️ 플랫폼 기능 분석<br>
✅ 플랫폼 정의<br>
🔸어플리케이션을 구동시키는데 필요한 하드웨어와 소프트웨어의 결합<br>
🔸공급자와 수요자등이 참여하여 각자가 얻고자 하는 가치를 공정한 거래를 통해 교환할 수 있도록 구축된 환경<br>
✅ 기능<br> 
🔸연결<br>
🔸비용감소<br>
🔸브랜드 신뢰<br>
🔸커뮤니티<br>
✅ 종류 <br>
🔸하드웨어<br>
🔸소프트웨어<br>
🔸서비스<br>
✅ 유형 <br>
🔸거래<br>
🔸생태계<br>
🔸다면<br>
✅ CPND <br>
🔸콘텐츠를 플랫폼에 맞게 가공하고 네트워크를 통해 사용자의 단말기로 서비스가 이루어짐을 표현하는 무선 인터넷 서비스의 가치사슬<br>
🔸**C**ontent, **P**latform, **N**etwork, **D**evice
<br><br>

✔️ 플랫폼 성능 분석<br>
✅ 성능 특성 분석 기법<br>
🔸사용자 인터뷰<br>
🔸성능 테스트<br>
🔸문서 점검<br>
✅ 성능 특성 분석 측정 항목<br>
🔸반환시간(Turnaround Time)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;요청된 시간부터 처리가 완료될 때 까지 걸린 시간<br>
🔸응답시간(Response Time)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;요청을 전달한 시간부터 응답이 도착할 때 까지 걸린 시간<br>
🔸가용성(Abailability)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;정보시스템이 정상적으로 사용 가능한 정도<br>
🔸사용률(Utiliztion)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;요청을 처리하는 동안 CPU, 메모리 등의 자원 사용률<br>
<br><br>
✔️ 운영체제 분석<br>
🔸컴퓨터 시스템 자원을 효율적으로 관리하여 사용자가 컴퓨터를 편리하게 사용할 수 있도록 환경을 제공해주는 시스템 소프트웨어
<br><br>
✔️ 네트웨크 분석<br>
✅ 개념<br>
🔸노드(컴퓨터)들이 자원을 공유할 수 있게 하는 디지털 전기 통신망<br>
✅ 프로토콜<br>
🔸데이터를 교환하기 위해 사용하는 통신 규칙<br>
🔸구문(Syntax), 의미(Syntax), 타이밍(Timing)
<br><br>
✔️ DBMS 분석<br>
✅ 개념<br>
🔸사용자, 애플리케이션 등의 상호 작용을 위해 데이터를 저장하고 분석하는 소프트웨어<br>
✅ 구축 시 고려사항<br>
🔸가용성, 성능, 기술지원, 상호 호환성, 구축 비용<br>
✅ 종류<br>
🔸Oracle, Microsoft SQL Server, MySQL, SQLite
<br><br>
✔️ 비지니스 융합분석<br>
✅ 모형<br>
🔸제품의 서비스화 - 제품에 자사 또는 타사의 서비스를 부가하여 서비스 제공<br>
🔸서비스의 제품화 - 서비스를 제품화 또는 장비, 기기로 전환<br>
🔸제품과 서비스 통합 - 사용자의 요구에 부합하는 시스템 또는 솔루션<br>
🔸O2O(Online to Offline) - 온라인가 오프라인 소비채널을 융합
<br><br><br><br>


### 2. 요구사항 확인<br>
✔️ 요구분석 기법<br>
✅ **요구사항 개발 프로세스**<br>
![](https://velog.velcdn.com/images/soyoon36/post/fbaf239b-9237-4c8f-a422-3ee827ca487b/image.png)<br>
✅ 요구분석 분석 기법<br>
🔸요구사항 분류<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;기능/비기능 분류<br>
🔸개념 모델링<br>
🔸요구사항 할당<br>
🔸요구사항 협상<br>
🔸정형 분석<br>
<br><br>
✔️ UML(Unified Modeling Language)<br>
✅ 개념<br>
🔸프로그램 설계를 표현하기 위해 사용하는 표기법<br>
🔸시스템 개발 과정에서 이해관계자 사이에 의사소통을 원활하게 이루어지게 하기 위하여 표준화한 모델링 언어<br>
✅ **특징**<br>
🔸가시화 언어<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;소프트웨어의 개념 모델을 시각적인 그래픽 형태로 작성한다.<br>
🔸명세화 언어<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;분석, 설계, 구현 단계의 각 과정에서 필요한 모델을 명세화할 수 있는 언어<br>
🔸구축 언어<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;명세화된 설계 모델은 다양한 언어의 소스코드로 변환하여 구축할 수 있다.<br>
🔸문서화 언어<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;일련의 과정을 문서로 남겨 계속 유지 보수한다.<br>
✅ **구성요소**<br>
🔸사물<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;모델을 구성하는 가장 중요한 기본 요소<br>
🔸관계<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;사물과 사물 사이 연관성<br>
🔸다이어그램<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;사물과 관계를 도형으로 표현<br>
✅ 사물<br>
🔸구조사물<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;시스템의 개념적, 물리적 요소<br>
🔸행동사물<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;시간과 공간에 따른 요소들의 행위<br>
🔸그룹사물<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;요소들을 그룹으로 묶은 것<br>
🔸주해사물<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;부가적 설명이나 제약조건<br>
✅ 관계<br>
🔸일반화 관계<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;한 클래스가 다른 클래스를 포함하는 상위 개념일 때의 관계(상속관계)<br>
![](https://velog.velcdn.com/images/soyoon36/post/12522525-0b70-4fdc-ba1f-66e85b9e8815/image.png)<br>
🔸연관 관계<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2개 이상 사물이 서로 관련된 관계를 말하며 한 클래스가 다른 클래스에서 제공하는 기능을 사용할 때 표시<br>
🔸의존 관계<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;연관 관계와 비슷하나 두 클래스의 관계가 한 메서드를 실행하는 동안과 같이 매우 **짧은 시간**만 유지<br>
🔸실체화 관계<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;인터페이스를 구현받아 추상 메서드를 오버라이딩 하는 것을 의미 <br>
🔸집합 관계 - 집약 관계(Aggregation)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;한 객체가 다른 객체를 소유하는 'has a'관계<br>
🔸집합 관계 - 합성 관계(Composition)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;부분 객체가 전체 객체에 속하는 관계로 **긴밀한 필수적 관계**<br>
✅ 다이어그램<br>
🔸구조다이어그램<br>
🔸행위다이어그램<br>
✅ 주요 다이어그램<br>
🔸클래스 다이어그램<br>
🔸**유스케이스 다이어그램**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;시스템, 엑터, 유스케이스, 관계 등으로 구성<br>
✖️ 유스케이스 관계 : 연관관계, 포함 관계, 확장 관계, 일반화 관계<br>
🔸시퀀스 다이어그램<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;객체와 생명선, 활성 박스, 메시지로 구성<br>
🔸상태 다이어그램<br>
<br><br>
✔️ 애자일(Agile)<br>
✅ XP(eXtream Programming)<br>
🔸문서보다는 코드를 중시하고, **5가지 핵심가치**와 **12개의 실천 항목**이 존재<br>
✖️ 5가지 핵심가치 : 용기, 존중, 의사소통, 피드백, 단순성 <br>
✅ 스크럼(SCRUM)<br>
🔸소프트웨어에 포함될 기능과 개선점에 대한 우선순위를 부여<br>
🔸개발 주기는 30일 정도로 조절하고 개발 주기마다 실제 동작할 수 있는 결과를 제공<br>
🔸개발주기마다 적용할 기능이나 개선에 대한 목록을 작성<br>
🔸항상 팀 단위로 생각하고, 날마다 15분 정도의 회의<br>
✅ 그 외의 애자일 방법론<br>
🔸크리스털(Crystal)<br>
🔸FDD(Feature-Driven Development)<br>
🔸ASD(Adaptive Software Development)<br>
🔸린(Lean)