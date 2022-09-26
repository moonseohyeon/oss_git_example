# 오픈소스 소프트웨어
### **Week1-1 강의 개요 (강의계획서)**

#### 
-	Basic functional programming, _Haskell_
(기초 함수형 프로그래밍 하스켈)
-	Basic concepts and tools for _open-source software_ development
(오픈소스 소프트웨어 기본 개념과 도구)
-	Attitude to self-learn new _SW tools_ and environments
(새로운/낯선 소프트웨어 개발 환경 및 도구를 스스로 배우는 태도)
<br/>

<br/>


### **Week1-2 오픈소스소프트웨어 개요**

#### 
1. 오픈 소스 소프트웨어란? <br/>
 오픈 소스 소프트웨어는 누구나 검사, 수정 및 개선할 수 있는 소스 코드가 포함된 소프트웨어입니다. 소스 코드는 컴퓨터 프로그래머가 애플리케이션의 기능을 변경하거나 새로운 기능을 추가하기 위해 조작하는 소프트웨어의 일부입니다. 소프트웨어의 소스 코드에 액세스할 수 있는 사람은 누구나 기능을 추가하거나 기존 오류를 해결하여 애플리케이션을 개선하거나 사용자 지정할 수 있습니다. 오픈 소스 소프트웨어는 오늘날 사용하는 대부분의 웹 애플리케이션 및 디바이스에 있습니다. 오픈 소스 소프트웨어의 몇 가지 예로 오픈 소스 운영 체제인 Linux와 오픈 소스 인터넷 브라우저인 Mozilla Firefox가 있습니다.

<br/>

 2. 오픈소스 소프트웨어의 기능은?  [aws](https://aws.amazon.com/ko/what-is/open-source/)
 - 통합 소프트웨어 배포의 구성 요소로 소프트웨어를 판매하거나 양도하는 것에 대한 제한은 없습니다.
- 소스 코드를 포함하고 배포를 허용해야 합니다.
- 수정본과 파생 저작물을 허용해야 합니다.
- 프로그램에 부여된 권리는 차별 없이 모든 사람에게 적용되어야 합니다.

<br/>
<br/>

#### Week2-1 버전 관리 개요

1. 버전 관리란? <br/>
소스 코드 관리(SCM) 시스템이라고도 하는 버전 관리 시스템(VCS)을 사용하면 코드 베이스의 모든 변경 사항을 추적할 수 있습니다. 파일을 버전 관리 시스템에 보관하면 수정, 추가 또는 삭제 내역을 확인하고 언제, 어떤 사용자가 해당 작업을 수행했는지도 알 수 있습니다.
<br/><br/>


#### Week2-2 Git <br/>
1. Git이란? <br/> [git.seohyeon](https://github.com/moonseohyeon)

- Git이란 버전 관리 시스템의 한종류입니다.
- GIt은 형상 관리 도구중 하나입니다.
- Git은 소프트웨어를 개발하는 기업의 핵심 자산인 소스코드를 효과적으로 관리할 수 있게 해주는 무료, 공개 소프트웨어입니다.
- SVN보다 여러 장점이 있어 SVN을 쓰던 개발 조직들은 하나둘씩 Git으로 변화를 하고 있습니다.

[git.image](../Users/moon0/OneDrive/%EB%B0%94%ED%83%95%20%ED%99%94%EB%A9%B4/%EA%B9%83%ED%97%88%EB%B8%8C%20%EC%9D%B4%EB%AF%B8%EC%A7%80.png)


<br/>

#### Week2-3 Github, fork, pull request

#### 1. fork 

Fork란 타인 소유의(또는 공동 소유의) 프로젝트 소스와 commit 내역, branch 등 원본 Remote Repository의 구조를 그대로 복사하여 내 소유의 새로운 Remote Repository로 생성하는 기능이다.

Fork 작업은 CONTRIBUTING.md 파일에도 설명돼있지 않은 경우가 많지만, 일반적으로 Git 협업을 위한 첫 단추는 Fork 이다.

<br/>

#### 2. pull & request

Pull Request는 내가 수정한 Commit들을 원본 Repository에 반영(Pull)해줄 것을 요청(Request)하는 작업이다.

충돌 문제를 해결하고 안전하게 병합이 가능하다면 이제 Pull Request 방법으로 원본 Repository에 수정 내역을 반영하는 작업을 수행한다.


