# 요구사항

## G1: 당신의 FOSS 책임을 이해하라.

### 1.1 문서로 만들어진 FOSS 정책이 존재하고, 이를 통해 Supplied Software 배포 시에 필요한 FOSS License Compliance를 관리한다. 이 정책은 최소 내부에서 접근할 수 있는 공간에 존재한다. 

#### Verification Artifact(s) (결과물 확인):
- 1.1.1 문서로 만들어진 FOSS 정책이 존재한다.
- 1.1.2 모든 Software Staff가 FOSS 정책의 존재를 인식할 수 있도록 문서로 만들어진 절차(예: Traning, 내부 wiki 혹은 기타 실잘직인 의사소통 방법)가 존재한다.

#### Rationale (방법) :
FOSS 정책을 생성 및 기록하고 이를 Software Staff가 인식하게 할 수 있는 조치가 취해졌는지 확인하라. 여기서는 정책 내에 무엇이 포함되어야만 하는지에 대해서는 요구하고 있지 않지만, 다른 섹션에서는 다른 요구사항이 있을 것이다.

### 1.2 모든 Software Staff 대상으로 하는 다음과 같은 필수 FOSS Training이 존재한다.: 
- Training은 최소한 다음 주제를 다룬다. 
  - FOSS 정책 및 사본을 찾을 수 있는 곳;
  - FOSS 및 FOSS License에 관한 IP 법의 기본;
  - FOSS Licensing 개념 (Permissive 및 Copyleft 개념 포함);
  - FOSS Project Licensing 모델;
  - 세부적인 FOSS Compliance 및 전반적인 FOSS 정책에 관한 Software Staff의 역할 및 책임; 
  - Supplied Software에 포함된 FOSS Component의 식별, 기록 및 추적을 위한 Process;
  - Software Staff는 지난 24개월(현재로 간주함)내 FOSS Training을 완료해야 한다.  때, Test를 통해 Software Staff가 Training 요구사항을 만족하는지 확인할 수도 있다. 

#### Verification Artifact(s) (결과물 확인):
- 1.2.1 위의 주제를 다루는 FOSS 과정 자료(예: Slide 자료, Online 과정 혹은 이외 Training 자료)가 존재한다.
- 1.2.2 모든 Software Staff가 과정을 완료하였는지 추적하는 방법
- 1.2.3 적어도 Software Staff의 85%가 현재 (위에서 정의한) 완료한 상태

#### Rationale (방법):
Software Staff가 최근 FOSS Training에 참석했는지, FOSS Training이 핵심 FOSS 주제를 다루는지를 확인한다. 이 의도는 핵심 기본 수준의 주제를 다루는 것이지만, 일반적인 Training Program은 여기서 요구하는 것보다 더 포괄적일 수도 있다. 




## G2: Compliance 달성을 위한 책임을 할당하라. 

### 2.1 FOSS Liaison (연락담당자)의 기능을 확인한다. 
- FOSS 관련 외부 문의 대응을 책임질 인원을 지정한다. 
- FOSS Liaison (연락담당자)는 타당한 FOSS Compliance 문의에 대응하기 위해 상업적으로 합당한 노력을 해야 한다. 그리고,
- 전자 통신을 통해 FOSS Liaison (연락담당자)에게 연락할 방법이 공개되어있는지 확인한다. 

#### Verification Artifact(s) (결과물 확인):

- 2.1.1 FOSS Liaison (연락담당자) 기능이 공개적으로 확인된다. (예: Email 주소 혹은 Linux Foundation의 Open Compliance Directory를 통해)
- 2.1.2 FOSS Compliance 문의에 대응하기 위한 책임을 할당하는 문서로 만들어진 절차가 존재한다. 

#### Rationale (방법):
제3자가 FOSS Compliance 문의와 관련하여 조직에 연락할 수 있는 합리적인 방법이 있는지 확인한다. 


### 2.2 내부 FOSS Compliance 담당을 확인한다. 

- 내부 FOSS Compliance를 관리할 인원을 지정한다. FOSS Compliance 담당과 FOSS Liaison (연락담당자)는 동일 인원이 될 수 있다.
- FOSS Compliance 관리 활동에는 충분한 자원이 있다. 
  - 담당자로서 임무를 수행할 시간이 할당되고, 
  - 상업적으로 합당한 예산이 배정된다. 
- FOSS 정책 및 Process를 개발하고 유지할 책임을 할당한다.  
- FOSS Compliance 담당은 FOSS Compliance에 대한 (내외부) 법률 전문 지식에 접근할 수 있다. 
- FOSS Compliance 이슈의 해결을 위한 Escalation이 가능하다. 

#### Verification Artifact(s) (결과물 확인):
- 2.2.1 지정된 FOSS Compliance 담당자, 조직 혹은 직무 이름
- 2.2.2 FOSS Compliance 담당이 사용할 수 있는 법률 전문 지식의 제공처를 확인한다. 
- 2.2.3 FOSS Compliance에 대한 책임을 할당할 수 있는 문서로 만들어진 절차가 존재한다. 
- 2.2.4 이슈 해결을 위한 Escalation 경로를 확인하는 문서로 만들어진 절차가 존재한다. 

#### Rationale (방법): 
FOSS 책임이 효과적으로 할당되었는지 확인한다. 



## G3: FOSS Content를 Review하고 승인하라. 

### 3.1 Supplied Software가 포함하는 모든 FOSS Component(및 각각 식별된 License)를 확인, 추적 및 보관하는 Process가 존재한다.  

#### Verification Artifact(s) (결과물 확인):
- 3.1.1 Supplied Software가 포함하는 FOSS Component 및 식별된 License 목록을 확인, 추적, 보관하는 문서로 만들어진 절차가 존재한다. 

#### Rationale (방법): 
Supplied Software를 구성하기 위해 사용된 모든 FOSS Component를 확인 및 나열하기 위한 Process가 존재하는지 확인한다. 이는 Supplied Software에 적용되는 각 Component의 배포 의무 및 제한 사항을 이해하기 위해 License 조항을 체계적 Review 할 수 있도록 존재해야 한다. 또한, 이 기록된 목록은 Process가 수행되었다는 증빙으로 사용된다. 


### 3.2 FOSS Program은 Supplied Software에 대해 Software Staff가 접하게 되는 일반적인 FOSS Use Case를 처리할 수 있어야 하고, 여기에는 다음과 같은 Use Case가 포함될 수 있다. - (아래 리스트가 모든 경우를 포함하지는 않으며 또한, 조직에 따라 아래의 모든 사항이 적용되는 것은 아님) Supplied Software의 일부가 :   
- Binary Form으로 배포되는 경우 
- Source Form으로 배포되는 경우
- 다른 FOSS와 통합되어 Copyleft 의무 사항을 유발하는 경우
- 수정한 FOSS를 포함하는 경우
- FOSS 혹은 Supplied Sofware 내 다른 Component와 상호 작용하면서 호환되지 않는 License 하에 있는 다른 Software를 포함하는 경우
- 저작자 표시 요구사항이 있는 FOSS를 포함하는 경우

#### Verification Artifact(s) (결과물 확인):
- 3.2.1 Supplied Software에 대해 Software Staff가 접할 수 있는 일반적인 FOSS Use Case를 처리할 수 있는 Process가 구현되었다. 

#### Rationale (방법): 
FOSS Program이 해당 조직의 Business 업무를 고려했을 때, 전형적인 User Case를 다루기에 충분히 견고하도록 만든다. 

## G4: FOSS Content 문서 및 Artifact(결과물)을 제공하라.

### 4.1 해당하는 식별된 License에서 요구하는 대로 Supplied Software와 함께 제공하기 위한 다음의 Distributed Compliance Artifact을 준비한다. 여기에는 다음 내용이 포함될 수 있지만, 이에 국한되지는 않는다.: 
- 저작권 고지(Copyright Notices)
- 식별된 License의 사본
- 수정 고지
- 저작자 표시 (Attribution Notices)
- Prominent Notice
- Source Code
- 요구되는 Build 방법 및 Script
- Written Offer

#### Verification Artifact(s) (결과물 확인):
- 4.1.1 식별된 License에서 요구하는대로 Supplied Software와 함께 Distributed Compliance Artifact가 배포되도록 보장하는 Process를 설명하는 문서로 만들어진 절차가 존재한다. 

- 4.1.2 Distributed Compliance Artifact의 사본이 보관되고 쉽게 검색할 수 있다 (예: Legal Notice, Source Code, SPDX 문서). 보관된 자료는 적어도 Supplied Software가 제공되는 한 혹은 식별된 License에서 요구하는 기한 동안 존재하여지도록 한다 (둘 중 더 긴 것을 따름). 

#### Rationale (방법):
Supplied Software에 적용되는 식별된 License에서 요구하는 대로 완전한 Compliance 산출물 집합이 Supplied Software와 함께 제공되는지 확인한다. 



## G5: FOSS Community로의 참여를 이해하라.

### 5.1 조직 대신 직원들이 공개적으로 접근 가능한 FOSS Project에 Contribution 하는 것을 관리하기 위한 문서로 만들어진 정책이 존재한다. 이는 최소 내부에서 접근할 수 있는 공간에 존재만 한다.


#### Verification Artifact(s) (결과물 확인):
- 5.1.1 문서로 만들어진 FOSS Contribution 정책이 존재한다.;

- 5.1.2 모든 Software Staff가 FOSS Contribution 정책의 존재를 알도록 하는 문서로 만들어진 절차(예: 교육, 내부 wiki, 혹은 다른 실제적인 의사소통 방법을 통해)가 존재한다.


#### Rationale (방법):
FOSS에 공개적으로 Contribution 하는 것과 관련한 정책 개발을 위해 조직이 합당한 고려를 하였는지 확인한다. 
FOSS Contribution 정책은 조직의 전체 FOSS 정책의 일부로 만들 수도 있고, 자체적인 별도의 정책으로 만들 수도 있다. Contribution이 전혀 허용되지 않는 상황이라면, 이를 명확히 하는 정책이 있어야 한다. 


### 5.2 FOSS Contribution 정책이 Contributiondㅡㄹ 허용하는 경우, Contribution이 FOSS Contribution 정책을 준수하는지 확인하기 위한 Process가 존재한다. 여기에는 다음과 같은 고려사항이 포함될 수 있지만, 이에 국한되지는 않는다. : 
- License 고려에 대한 법적 승인
- 사업상의 근거 또는 승인
- Contribution 할 Code의 기술적 검토
- Community 참여 및 소통 (Project의 행동 강령 혹은 이와 동등한 내용 포함)
- Project 별 Contribution 요구사항 준수


#### Verification Artifact(s) (결과물 확인):
- 5.2.2 FOSS Contribution 정책이 Contribution을 허용한다면, FOSS Contribution Process를 설명하는 문서로 만들어진 절차가 존재한다.

#### Rationale (방법): 
조직이 공개적으로 FOSS에 Contribution하는 방법에 대한 문서로 만들어진 Process가 있는지 확인한다. 
Contribution을 전혀 허용하지 않는 정책이 있을 수도 있다. 이러한 특정 상황에서는 Process가 존재하지 않을 수 있으며, 그럼에도 이 요구사항은 충족되는 것이다. 


## G6: OpenChain 요구사항을 준수하는지 인증하라.

### 6.1 조직이 OpenChain 인증을 받으려면, OpenChain Conformance Specification version 1.0의 기준을 충족하는 FOSS Program이 있음을 확약해야 한다. 

#### Verification Artifact(s) (결과물 확인):
- 6.1.1 조직은 이 OpenChain Conformance Specification version 1.0의 모든 요구 사항을 충족하는 Program이 존재함을 확약한다. 

#### Rationale (방법): 
OpenChain Conforming 하는 Program이 조직에 있음을 선언한다면, 해당 Program이 이 specification의 요구사항을 모두 충족하는지 확인한다. 이 요구사항의 일부만을 단순히 충족하는 것은 OpenChain 인증 Program을 보증하기에 충분하지 않을 수 있다. 
