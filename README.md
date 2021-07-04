# Certificate_Learn
자격증 공부 정리 Repo

퇴근 후 최소 한 시간은 공부하자!

### 2021 년 기준 정보처리기사 실기 개념 정리

# 1장

### Chapter 3

요구사항 개발 프로세스 : 도 분 명 확

1. 요구사항 도출
2. 요구사항 분석
3. 요구사항 명세
4. 요구사항 확인 및 검증

* 요구사항 도출 단계 주요기법

인터뷰, 브레인스토밍, 델파이기법, 롤플레잉, 워크숍, 설문 조사

```text
델파이 기법 : 현실에 일어나는 장면을 설정하고 여러 사람이 각자가 맡은 역을 연기함으로써 요구사항을 분석하고 수집하는 방법
```

* 요구사항 분석 단계

요구사항 분석 단계는 추출된 요구사항에 대해 충돌, 중복, 누락 등의 분석을 통해 완전성과 일관성을 확보하는 단계

요구사항 분석 단계 절차

요구사항 분류 -> 개념 모델링 생성 및 분석 -> 요구사항 할당 -> 요구사항 협상 -> 정형 분석

```text
정형분석 : 형식적으로 정의된 의미를 지닌 언어로 요구사항을 표현하는 활동
구문(Syntax)과 의미(Sementics)를 갖는 정형화된 언어를 사용하여 수학적 기호로 표현
요구사항 분석의 마지막 단계에서 이루어짐
```

요구사항 분석 단계 기법

자료흐름 지향 분석(데이터 흐름도 및 자료 사전으로 부터 소프트웨어 구조를 유도), 객체지향 분석(UML로 표준화)

* 요구사항 명세 단계

비정형 명세 기법 : 사용자이 요구를 표현할 때, 자연어를 기반으로 서술하는 기법

정형 명세 기법 : 사용자의 요구를 표현할 때 수학적인 원리와 표기법으로 서술하는 기법

명완검 일수 추개

명확성, 완전성, 검증 가능성, 일관성, 수정 용이성, 추적 가능성, 개발 후 이용성

* 요구사항 확인 및 검증 단계

요구사항 확인 및 검증 절차

1. 요구사항 목록 확인
2. 요구사항 정의서 작성 여부 확인
3. 비기능적 요구사항의 확인
4. 타 시스템 연계 및 인터페이스 요구사항 확인

상세 정형 기술 검토 기법

관리 리뷰, 기술 리뷰, 인스펙션, 워크 스루, 감사

* 요구사항 관리 단계

1. 요구사항 협상
2. 요구사항 기준선 설정
3. 요구사항 변경 관리
4. 요구사항 확인 및 검증



요구사항의 기술적 타당성 검토

- 요구사항의 기술적 타당성 검토는 성능 및 용량 산정의 적정성, 시스템 간 상호 운용성, IT 시장 성숙도 및 트렌드 부합성, 기술적 위험 분석의 4단계를 거친다.

성능 및 용량 산정의 적정성 : 목표 시스템의 용량이 산정되면, 과거 유사 프로젝트 경험치를 적용하여 필요시 재조정한 후, 성능 관련 비기능 요구사항과 비교하여 적정성 여부 판단

시스템 간 상호 운용성 : 요구사항 중에서 목표 시스템이 조직 내외 타 시스템과의 연동을 요구하는 경우, 상호 운용이 가능한지 여부를 판단

IT 시장 성숙도 및 트렌드 부합성 : 시스템 구축 시 요구되는 영역별 기술들의 시장 성숙도 및 발전 방향을 파악하고, 요구사항이 이에 부합하는지 판단. 향후 사용되지 않을 가능성이 높은 시스템들은 향후 유지보수가 어려운 상황이 발생

기술적 위험 분석 : 요구사항을 만족시키기 위하여 적용한 기술의 복잡성, 검증 여부, 의존성 등에 대하여 위험 발생 가능성, 영향도 파악



---

#### 2021 1회 기출 문제 정리

1.

```text
1) IP호스트가 자신의 물리 네트워크 주소(MAC)는 알지만 IP주소를 모르는 경우, 서버로부터 IP주소를 요청하기 위해 사용하는 프로토콜
답 : RARP
2) TCP/IP 네트워크에서 연결된 시스템은 논리주소인 IP주소를 가지고 있으며, 이 IP주소를 물리주소인 MAC 주소로 변환하는 프로토콜
답 : ARP
```

2.

```text
1) 비즈니스 서비스를 기술하여 비즈니스들끼리 전자적으로 서로 접근하는 방법을 제공하기 위해 사용되는 확장성 생성 언어(XML) 기반의 언어로 웹 서비스의 구체적 내용이 기술되어 있어 서비스 제공 장소, 서비스 메시지 포맷, 프로토콜 등이 기술된다.
답 : WSDL

2) 웹 서비스 관련 정보의 공개와 탐색을 위한 표준이다. 서비스 제공자는 ( )라는 서비스 소비자에게 이미 알려진 저장소에 그들이 제공하는 서비스 목록들을 저장하게 되고, 서비스 소비자들은 그 저장소에 접근함으로써 서비스들의 목록을 찾을 수 있게 된다.
답 : UDDI

3) 일반적으로 널리 알려진 HTTP, HTTPS, SMTP 등을 통해 XML 기반의 메시지를 컴퓨터 네트워크 상에서 교환하는 프로토콜이다.
답 : SOAP
```

3.

```text
요구사항의 종류
( ) 요구사항 : 기능, 입력, 출력, 저장, 수행 등
( ) 요구사항 : 성능, 품질, 제약사항, 호환성, 보안 등
답 : 
기능적
비기능적
```

4.

```text
1) 정규화된 엔터티, 속성, 관계에 대해 시스템의 성능향상과 개발과 운영의 단순화를 위해 중복, 통합, 분리 등을 수행하는 데이터 모델링의 기법
```





