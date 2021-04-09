# 김은호

웹 애플리케이션 서버 프로그래머 (Java, Spring)  
대한민국, 경기도 거주  
010-2778-5309  
[djkehh@gmail.com](mailto:djkehh@gmail.com)


## 학력

### 숭실대, 졸업 *(2005년 3월 ~ 2014년 2월)*

* 정보통신전자공학부


## 주업무 경험

### 카카오커머스 *(2018년 12월 ~ 현재)*

* 배치/웹 애플리케이션 백엔드 프로그래머
* Java, Groovy, Spring

카카오커머스는 카카오톡의 1억 유저와 모바일 교환권 서비스를 바탕으로 e-commerce 서비스 시장을 선도하고 있는 기업입니다. 2019년 연간 누적 거래액 1조, 월 거래액 2천억, 연간 매출 1천억 원으로 꾸준한 성장과 높은 성과를 내고 있습니다.

#### 회원개발파트

회원개발파트는 카카오커머스의 주요 고객인 구매자, 판매자 회원들의 정보 관리 및 인증 업무를 수행하는 개발 부서입니다.

##### 공휴일 관리 서비스 *(2020년 9월 ~ 2020년 11월)*

* 주 사용 기술: Java(Spring Boot), MySQL, Git(GitHub)

카카오커머스 전체 개발 조직이 이용할 목적으로 만든 공휴일 기록 관리 서비스입니다. 공휴일 정보는 주말과 국경일, 그리고 회사가 정하는 휴일 정보를 포함합니다. 관리자가 어드민 도구를 이용해 이를 편리하게 관리하고자 하는 니즈에 맞춰 기획된 서비스입니다. 입력한 휴일 정보는 영업일을 파악하여 정산 날짜를 계산하거나, 각종 알림과 같은 배치 업무를 처리하는데 사용됩니다.

저는 백엔드 위치에서 휴일 정보를 조작할 수 있는 API를 제공하는 업무를 맡아 프론트엔드 부서와 협업하였습니다. 일정과 내용 공유는 지라 스프린트로 관리하였습니다. 이 프로젝트를 통해, 저는 카카오커머스에서 정한 개발 규약에 맞춰 처음부터 개발 프로젝트를 구성하고, 도메인과 API 스펙과 비즈니스 로직을 설계하고, 서버 장비를 받아 서비스 가능한 상태로 초기화하고, 젠킨스와 깃허브를 이용해 자동화된 빌드 배포 환경을 구축하고, 기존 인증 시스템과 각종 모니터링 도구를 연결하는 등, 회원개발파트에서 하나의 신규 서비스를 런칭하기 위해 해야 하는 과정을 처음부터 끝까지 담당하였습니다.

#### 정산플랫폼개발파트

정산플랫폼개발파트는 카카오커머스에서 일어나는 모든 결제 데이터의 정산 업무를 처리하는 개발 부서입니다. 업무는 주로 배치 프로그램과 어드민 서비스에 집중되어 있습니다.

##### 프로젝트 내 민감 정보 처리 기술에 Vault 적용 *(2020년 1월 ~ 2020년 2월)*

* 주 사용 기술: Groovy(Spring Boot), MySQL, Hashicorp Vault, Git(GitHub)

정산 플랫폼은 배치 업무를 처리하거나 어드민 서비스를 제공하면서 db, 외부 api 등에 접근하기 위해 민감 정보를 사용합니다. 또한 사용자 데이터 안에도 계좌번호와 같이 사용자 식별이 가능한 민감 정보가 포함되어 있습니다. 이에 대한 보안성을 강화하기 위해, 민감 정보의 접근 방법에 Vault 기술을 적용하고 회원 정보 관리 부서와 협력하는 프로젝트입니다.

이를 위해 Vault 기술의 조사, 기존 프로젝트의 사용처 및 영향도 조사가 필요했습니다. 저는 이 프로젝트를 전담하면서 Vault 기술 적용 방법의 설계와 구현, 테스트를 하였습니다.

##### 정산 보정 시스템화 *(2019년 9월 ~ 2019년 10월)*

* 주 사용 기술: Groovy(Spring Boot), 웹프로그래밍(HTML/CSS/Javascript/JQuery/AxisJ), MySQL, Git(GitHub)

주문, 결제, 정산 사이에는 고객의 니즈에 따라 다양하고 복잡한 정산 흐름이 존재합니다. 떄문에 고객 CS 처리, 정산 오류 보정 등 평소의 정산 규칙을 따르지 않는 특별한 정산 처리 업무가 수시로 존재합니다. 이런 업무는 운영팀에서 수기로 직접 처리하곤 했는데, 이를 각종 특이 정산을 시스템화하여 운영툴에서 처리할 수 있도록 합니다.

이 프로젝트는 새로운 도메인 설계, 배치 프로그램 개발, 어드민 서비스 개발, 권한 처리 등으로 이루어졌습니다. 저는 설계와 어드민 서비스(API, 인증과 데이터 검증을 포함한 서비스 로직, 프론트엔드 등), 권한 처리 로직 개발을 담당하였습니다.

### 카카오페이 *(2017년 9월 ~ 2018년 12월)*

* 배치/웹 애플리케이션 백엔드 프로그래머
* Java, Spring

카카오페이는 누적 가입자 2250만 명, 가맹점 약 240만 개, 월 거래액 약 1조원의 지표를 가진 간편결제 서비스입니다.

#### 수퍼셀 (정산개발팀)

수퍼셀은 카카오페이에서 일어나는 주요 결제 내역의 정산 작업을 담당하는 시스템을 개발 및 유지 보수합니다.

##### 통합 정산 플랫폼 *(2018년 4월 ~ 2018년 12월)*

* 주 사용 기술: Java(Spring Boot), 웹프로그래밍(HTML/CSS/Javascript/React), MySQL, Git(GitHub)

카카오페이의 구 정산 플랫폼을 대체할 차세대 정산 플랫폼을 설계하는 업무입니다. 기존의 정산 플랫폼 운영을 통해 배웠던 경험을 토대로 온라인, 오프라인, 카드, 포인트 등 다양한 채널을 통해 보다 넓은 사용자 요구 사항에 유연하게 대응할 수 있는 시스템을 설계하는 것을 목표로 작업하였습니다. 초기 버젼의 정산 플랫폼 완성 작업을 설계 기간 2주, 개발 기간 2주를 합쳐 총 1달 동안 진행하였고, 이후 새로운 요구사항을 계속 반영하며 운영 중입니다.

통합 정산 플랫폼은 도메인 및 도메인 관계, 데이터 흐름, 배치 업무, api 및 운영자용 관리 페이지로 구성되어 있습니다. 이 내용의 초기 도메인 설계부터 기술 선택, 개발까지 전체 과정을 팀원들과 함께 논의하고, 서로 나누어 담당하였습니다.

### NHN 엔터테인먼트 *(2015년 1월 ~ 2017년 9월)*

* 웹 애플리케이션 백엔드 프로그래머
* Java, Spring

#### O2O서비스개발팀

##### TOAST Meetup *(2017년 4월 ~ 2017년 9월)*

* 주 사용 기술: Java(Spring Boot), 웹프로그래밍(HTML/CSS/Javascript), MySQL, Git(GitHub)

TOAST Meetup은 NHN 엔터테인먼트에서 운영하는 기술 블로그입니다. 외부 개발자 트래픽 유입 및 TOAST Cloud 상품 이용을 유도하려는 목적을 가지고 있습니다. TOAST 상품군 중 유저 이용이 가장 작은 서비스이고, 별도의 지표 관리는 하고 있지 않습니다.

[http://meetup.toast.com](http://meetup.toast.com/)

우선 순위가 밀려 그간 잘 운영되지 못했던 서비스의 운영 및 리뉴얼을 기획, 개발하는 업무를 맡았습니다. 기존 프로젝트는 외주를 맡겨 개발했는데, 여러 가지 버그로 문제가 많았지만 소스코드를 소유하지 않아 유지 보수가 불가능했습니다. TOAST Meetup의 리뉴얼은 처음부터 완전히 새로운 기획과 개발로, 기존 프로젝트의 코드 참조 없이 처음부터 소스코드를 작성하는 방향으로 결정되었습니다.

본 프로젝트를 다음의 단계로 진행하였습니다.

1. 새로운 기술 문서를 발굴하여 콘텐츠 확보
2. 발굴한 기술 문서들을 검수하여 일정 수준 이상의 콘텐츠 품질 확보
3. TOAST Meetup V2 프로젝트 기획: 현재 블로그의 문제점과 사용성을 개선한 웹서비스 설계, 기획
4. TOAST Meetup V2 개발

##### 운수도원, 친구 추천 이벤트 *(2017년 1월 ~ 2017년 3월)*

* 주 사용 기술: Java(Spring), 웹프로그래밍(HTML/CSS/Javascript), Shell Script, Python, MySQL, Git(GitHub)

운수도원은 사용자에게 사주/운세/손금/관상/궁합 정보를 제공하는 앱 서비스이며, 회원 관리를 위해 페이코 회원 시스템을 사용합니다. 가입자 약 10만, DAU 약 1만 명 규모의 서비스이며, 지표 수집 솔루션으로 AceCounter와 자사 솔루션인 TOAST Analytics를 연동하여 사용하였습니다.

* Android: [https://play.google.com/store/apps/details?id=com.nhnent.unse&hl=ko](https://play.google.com/store/apps/details?id=com.nhnent.unse&hl=ko)
* iPhone: [https://itunes.apple.com/app/id1177304977](https://itunes.apple.com/app/id1177304977)

본 프로젝트의 목표는 페이코 신규 회원을 효과적으로 끌어들이기 위해, 운수도원 앱의 설날 명절 이벤트를 진행하여 신규 운수도원 가입 유저와 그 추천인들에게 경품을 제공하는 것입니다. 이에 다음과 같이 프로젝트를 진행하였습니다.

* 이벤트 페이지 개발 (4일)
  * 웹, 웹뷰에 보이는 화면 및 내부 API 개발
  * 페이코 회원 정보 조회를 위해 타부서의 페이코 회원 API 연동
* 추첨 및 당첨자 리스트 출력 로직 개발 (4일)
  * DB로부터 당첨자를 뽑아 배송을 위한 개인정보를 매칭하여 출력하는 스크립트 개발
* 배포 및 운영

#### 클라우드개발팀

##### TOAST Cloud Health Dashboard 외 *(2016년 8월 ~ 2016년 12월)*

* 주 사용 기술: Java(Spring), 웹프로그래밍(HTML/CSS/Javascript), MySQL, Git(GitHub)

TOAST Cloud Health Dashboard는 TOAST Cloud([https://cloud.toast.com](https://cloud.toast.com/)) 서비스의 인프라를 포함해 내부에 있는 모든 부가 상품들의 서버 가용 상태를 모니터링하는 서비스입니다. TOAST Cloud의 하위 서비스 형태로 진행했으며, 상품 기획부터 서버 - 프론트엔드까지 직접 설계하였습니다. 모니터링 기능은 사전에 개발하여 운영 중인 별도의 사내 모니터링 API를 활용하였습니다.

[https://cloud.toast.com/dashboard](https://cloud.toast.com/dashboard)

이 외에 TOAST Cloud CS&BBS, Email 등 클라우드 부속 상품들의 자잘한 유지 보수 업무를 수행하였고, 수시로 팀원들과 함께 코드 리뷰를 진행하였습니다.

#### 검색기술팀

##### 맞춤법 검사기 API *(2016년 1월 ~ 2016년 7월)*

* 주 사용 기술: C/C++(아파치 모듈 프로그래밍), Java(Spring), 웹프로그래밍(HTML/CSS/Javascript), Git(GitHub)

TOAST Cloud 부속 상품인 맞춤법 검사기 API 개발 프로젝트입니다. Dooray 부서의 기능 추가 요청으로 개발을 시작하였고, 주요 고객은 Dooray 및 사내 부서와 협력사들입니다.

기존 네이버 맞춤법 검사기의 소스코드를 분석한 뒤 프로젝트 요구사항에 맞춰 RESTful한 아파치 모듈 API로 개발하였습니다. 이 외에 토스트 클라우드의 콘솔 화면에 보이는 제품 사용 화면, 제품 소개 및 샘플 화면을 개발하였고, 업무를 위한 내부 위키 문서와 사용자를 위한 설명 문서를 작성하였습니다. 개발 이후는 지속적인 서비스 운영 업무를 맡았습니다.

* 제품 설명: [https://cloud.toast.com/service/spellchecker](https://cloud.toast.com/service/spellchecker)
* 사용자 도움말: [http://docs.cloud.toast.com/ko/Upcoming%20Products/Spell%20Checker/ko/Overview](http://docs.cloud.toast.com/ko/Upcoming%20Products/Spell%20Checker/ko/Overview)

##### 페이코 초기 사용자 결제/질의 로그 분석 *(2015년 10월 ~ 2016년 1월)*

* 주 사용 기술: Java(Hadoop MR, Streaming), 웹프로그래밍(HTML/CSS/Javascript), Python, Shell Script, Git(GitHub)

페이코 결제 기록과 제휴사들의 상품 검색 질의로부터 가치 있는 통계를 수집하여 이용자에게 맞춤형 광고 제공 등 수익 창출 및 효율 증대를 목적으로 페이코 서비스 초기 로그와 제휴 서비스들의 로그를 분석하여 유의미한 데이터 추출하는 작업입니다. 대형 결제 로그의 분석을 위해 하둡 초기 버젼과 맵리듀스를 공부하고 사용해본 작지만 소중한 기회였습니다.

또한, 상부 보고용 단발성 프로젝트로 검색 질의 로그의 분석 결과 화면을 설계하였습니다.

##### 도로명 주소 통합 검색 API *(2015년 4월 ~ 2016년 7월)*

* 주 사용 기술: C++(넥서스 검색엔진), Java(Spring Boot), 웹프로그래밍(HTML/CSS/Javascript), Python, Shell Script, Git(GitHub)

TOAST Cloud 부속 상품인 도로명 주소 통합 검색 API 개발 프로젝트입니다.

15년 8월 관련 법령에 의거 지번 주소가 모두 도로명 주소로 대체되었습니다. 이에 대응하면서 기존 타 서비스들과는 달리 지번 주소와 도로명 주소를 한 검색창에서 편리하게 검색할 수 있는 새로운 주소 검색 서비스를 만들어, 자사 클라우드 솔루션 TOAST Cloud의 고객들에게 제공하려는 목적으로 본 프로젝트를 진행하였습니다.

서비스의 주된 사용 고객은 사내 부서, 계열사, 협력사와 TOAST Cloud 제품을 이용하는 외부 고객들이며, 주로 고객 정보에 배송지 주소를 입력해야 하는 부분에서 API 형식으로 활용되고 있습니다. 체계적인 지표 수집을 위한 시스템은 갖추지 않고 로그를 직접 분석하여 대략적인 이용률을 가늠하였으며, 현재는 월 API 호출이 약 180만 건 규모인 서비스가 되었습니다.

도로명주소 API는 다음과 같은 서비스 논리 구성을 가지고 있습니다.

* 행자부에서 지번/도로명 주소를 주기적으로 긁어오는 배치 스크립트
* 주소 데이터를 검색 엔진용 컬렉션으로 덤프하기 위한 스크립트
* 검색 엔진
* 스프링 API
* TOAST Cloud Console 제품 사용 화면, 제품 소개 및 샘플 화면

이밖에 업무를 위한 내부 위키 문서와 사용자를 위한 설명서를 작성하였고, 개발 이후는 계속 서비스 운영 업무를 맡았습니다.

* 제품 설명: [https://cloud.toast.com/service/addresssearch](https://cloud.toast.com/service/addresssearch)
* 사용자 매뉴얼: [http://docs.cloud.toast.com/ko/Common/Address%20Search/ko/Overview](http://docs.cloud.toast.com/ko/Common/Address%20Search/ko/Overview)


## 기타 업무 경험 (인턴쉽 & 기타)

### BC 카드, 인턴 *(2014년 6월 ~ 2014년 8월)*

### NAVER, 자연어처리팀, 인턴 *(2013년 9월 ~ 2014년 1월)*

### NAVER 소프트웨어 멤버쉽 *(2013년 2월 ~ 2013년 8월)*

### Concept One Accessories, MIS/Operations, 인턴 *(2010년 7월 ~ 2011년 2월)*


## 과외 활동

### 오픈소스 컨트리뷰터, gitignore.io *(2018년 12월 ~ 현재)*

[gitignore.io](https://www.gitignore.io/)는 언어, 프레임워크 및 도구 별로 보편적인 `.gitignore` 설정을 템플릿으로 모아두었다가 손쉽게 작성할 수 있도록 도와주는 유명 웹서비스입니다. 트위터, 아마존, 구글, 페이스북, 마이크로소프트, airbnb 등 최고의 IT 기업들이 이 서비스를 사용하였습니다. 저는 본 프로젝트를 한글화하고, 이슈 [#435](https://github.com/joeblau/gitignore.io/issues/435)를 해결하는 코드를 제출하여 컨트리뷰터가 되었습니다. 현재 지속적으로 이 프로젝트에 관심을 가지고 참여하고 있습니다.

[https://github.com/joeblau/gitignore.io](https://github.com/joeblau/gitignore.io)

### 오픈소스 컨트리뷰터, Flybook *(2017년 6월 ~ 현재)*

[Flybook](https://flybook.js.org/)은 마크다운 문서로부터 정적 웹사이트를 생성해주는 도구로, [Rhio Kim](https://github.com/rhiokim) 님이 개발한 오픈소스 프로젝트입니다. [funbook](https://funbook.js.org/)과 [next.js](https://zeit.co/blog/next)에서 아이디어를 얻었으며, React와 React DOM Server를 사용하였습니다. 저는 본 프로젝트에 사용자 피드백과 윈도우 환경을 포함한 테스트([https://github.com/rhiokim/flybook/issues/13](https://github.com/rhiokim/flybook/issues/13)), 버그 리포트, 문서 업데이트를 통해 컨트리뷰터로 참여하였습니다.

[https://github.com/rhiokim/flybook](https://github.com/rhiokim/flybook)

본 이력서는 Flybook을 이용하여 만들어졌습니다.

### 한글화, 비트비커 *(2016년 11월 ~ 2017년 5월)*

비트비커(Bitbeaker)는 Atlassian Bitbucket의 안드로이드 클라이언트입니다.

[https://play.google.com/store/apps/details?id=fi.iki.kuitsi.bitbeaker](https://play.google.com/store/apps/details?id=fi.iki.kuitsi.bitbeaker)

이 안드로이트 클라이언트의 전체 내용과 구글 플레이 스토어의 제품 설명 페이지를 한글화하는 작업입니다. 100% 직접 번역 완료하여 v3.3 릴리즈와 함께 배포하였습니다.

* 이슈: [https://bitbucket.org/bitbeaker-dev-team/bitbeaker/issues/366/korean-translation](https://bitbucket.org/bitbeaker-dev-team/bitbeaker/issues/366/korean-translation)
* 번역 도구: [https://crowdin.com/project/bitbeaker/ko#](https://crowdin.com/project/bitbeaker/ko#)

### 오픈캠프 해커톤, 중앙대 제로페이지 *(2014년 4월)*

대학교 컴퓨터동아리배 해커톤 행사에서 안드로이드 앱을 이용한 아이디어 앱으로 1위를 하였습니다.

* 12팀 중 1위, 안드로이드 앱
* 프로젝트: 하모니, 길거리 소음을 기반으로 한 동적 볼륨 조절기
* 역할: 팀장
* 상세
  * 프로젝트 아이디어를 설명
  * 아이디어를 이용해 3명의 팀원을 선발(2 앱 개발자, 1 디자이너)
  * 전체 업무 지휘 및 분배
  * 코어 알고리즘 개발: 로우 패스 필터를 이용한 동적 볼륨 조절 알고리즘


## 언어

* 한국어, 모국어
* 영어, 유창함
  * latest TOEIC: 880, 2020-01-19
  * latest OPIc: IH, 2012-09-22


## 관심사

* 피아노 연주
  * [Send in the Clowns - Yuna Kim, piano cover](https://youtu.be/8gB9X7pdGgw)
* 운동: 헬스, 배드민턴, 스포츠 클라이밍
* 기술 블로그 글 읽기/수집하기/쓰기
  * 개인 기술 블로그: [https://djkeh.github.io](https://djkeh.github.io/)
  * 관심 있는 블로그: [TOAST Meetup](http://meetup.toast.com/), [Kakao Tech Blog](http://tech.kakao.com/), [Naver D2 Hello World](http://d2.naver.com/helloworld), 개인 블로그 [Outsider's Dev Story](https://blog.outsider.ne.kr/), [MartinFowler.com](https://martinfowler.com/), [Just hack'em](https://justhackem.wordpress.com/) 등


## 기타

* 병역: 육군, 만기제대
