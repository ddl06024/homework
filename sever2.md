- 서버 운영 체제
  - 솔라리스
     - 간단한 설명 : 썬 마이크로시스템에서 개발한 컴퓨터 운영 체제.
     - 회사/ 개발자 : 오라클
     - 소스 형태 : 오픈 소스, 클로즈드 소스
     - 프로그래밍 언어 : C, C++
     - 역사 
        - 1990년대 초 : 썬은 자신들의 운영체제인 SunOS 4를 가지고 있었는데 솔라리스 2가 나오면서 SunOS 4는 솔라리스 1이 라는 이름을 가지게 됨.
        - 현재 발표되어 있는 최신 버전은 솔라리스 11.3
        - 2010년 초에 오라클에서 썬 마이크로 시스템을 인수하면서 모든 자산이 오라클의 소유가 됨. 
        - 2017년 9월 3일 전 썬마이크로시스템 임원이 해고됐다는 소문이 있음
     - 솔라리스의 장점
        - 확장성이 좋음 : 솔라리스 멀티 프로세싱 환경을 고려하여 설계되어 확정성이 뛰어남
        - 관리가 쉬움 : 솔라리스는 많은 관리 도구를 제공하므로 오히려 관리가 용이
        - 신뢰성이 높음 : 산업계 표준인 Kerberos V5, IPSec 등의 암호화 프로토콜을 지원
        - 네트워크가 강력함 : 솔라리스는 현존하는 대부분의 전통적인 네트워크 포로토콜과 IPv6, LDAP, XML,J2EE등 최신 표준을 OS에서 지원
        - 범용성이 뛰어남 : 솔라리스에서는 PDA,PC,워크스테이션, 메인 프레임등을 손쉽게 연동해서 쓰는 기능 제공, 그리고 단일 제품 내에서 세계의 모든 언어를 지원, 오픈소스로 누구나 소스 코드를 볼 수 있음.
  - 리눅스 (UNIX)
     - 간단한 설명 : 리눅스는 다중 사용자, 다중 작업(멀티태스킹), 다중 스레드를 지원하는 네트워크 운영 체제.
     - 소스 형태 : 오픈 소스
     - 프로그래밍 언어 : C, 어셈블리어
     - 역사 
        - 1990년대 : 초반 썬은 자신들의 운영 체제인 SunOS 4
        - 1991년 : 리눅스라는 이름의 또 다른 커널이 극적으로 등장. 리눅스는 핀란드 헬싱키 대학의 대학원생인 리누스 토발즈가 취미 삼아 개발한 커널. 토르발스는 원래 앤드루 스튜어트 타네바움 교수가 교육용인 미닉스를 사용하는데, 다른 사람이 함부로 개조하지 못하도록 제한을 두는 미닉스의 기능에 만족하지 못했던 토르발스는 새로운 운영 체제를 개발하고자 함. 
        - 이후에 디스크의 파일도 일고, 쓰게 하도록 개발 -> 이를 기반으로 리눅스 개발
        - 1991년 9월 17일 : 인터넷을 통해 공개
        -> 이후 지속적으로 개발
     - 특징   
        - 현재에도 지속적으로 개발하여 발전시킨다는 점 -> 오픈소스 개발 방식을 사용하면서 급 속도로 성장.
        - 64비트 CPU 지원 : 이전 64비트 지원하는 리눅스가 존재했지만 그 사용 빈도 미약 -> AMD 64비트를 기본으로 지원되는 64비트 운영체제로 발전하여 상당한 점유율을 보임.
        - LUMA지원해 병목현상 없앰 : LUMA는 지역적으로 메모리를 공유하여 성능을 높이고, 시스템 확장성이 가능하도록 한 클러스터를 구성하는 방식.
        - 쓰레드 모델 강화 : 시스템 호출을 시키면 프로세스 당 생성할 수 있는 쓰레드가 생성되는데 , 이때 시스템에 부하를 주지 않으면서 쓰레드 개수를 8192개, 거의 무한대로 증가시켰다는 점이 큰 장점이다. -> 불필요한 행동을 없애고, 공간을 적절하게 사용하여 쉽게 사용 가능
        - 신형 VM : 가상머신을 이용하면 가상 페이지에 대해 페이지 테이블 엔트리가 해당하는 물리 페이지를 반환하거나 존재하지 않는다고 알려줌 -> 상당한 작업 단축의 효과
        - 네트워크 프로토콜 기능 강화 : 보안기능을 강화한 네트워크 프로토콜을 지원하면서, 멀티캐스트, 스택 분리 등 추가적인 개선      
  - 유닉스 
     - 간단한 설명 : 교육 및 연구 기관에서 즐겨 사용되는 범용 다중 사용자 방식의 시분할 운영체제
     - 개발자 : 켐 톰프슨, 데니스 리치, 브라이언 커니핸, 더글러스 매클로이, 조 오산나, 벨 연구소
     - 역사 
        - 개발 원인 : 1969년 미국 벨 연구소에서  Ken Tompson이 어셈블리어로 DEC 사의 PDP- 7용 운영체제를 개발한 후 계속 발전하여 1972년 C-언어로 만든 유닉스 운영체제 탄생
     - 특징  
        - 처음부터 다양한 시스템 사이에서 서로 이식 가능
        - 멀티 태스킹과 다중 사용자를 지원하도록 설계
        - 뛰어난 이식성 : 유닉스는 특정한 컴퓨터에 한정되어 사용되지 않으며, 종류가다른 기종에서 유용하게 사용가능.
        - 단순하지만 강력한 명령어 : 유닉스의 운영체제 목표는 간단하게 구성하면서 최소한의 기능마을 지원하고, 다른 여러가지 복잡한 기능을 사용자 프로그램으로 구현하도록 한 것. ( 교육 및 연구 기관에서 즐겨 사용되는 이유 )이런 구성원칙은 명령어들을 매우 간단하면서도 일관성 있도록 만들어주며, 배우기 쉽고, 기억이 쉬운 단어들을 사용
        - 계층적 파일 구조 : 유닉스의 모든 파일은 루트라고 부르는 하나의 점으로부터 시작해서 검색할 수 있는 나무형 구조( tree-structure)를 이루고 있음. 나무형 구조에서 나뭇잎은 파일에 해당, 가지는 디렉토리에 해당
        - 주변장치를 하나의 파일로 처리 : 유닉스의 모든 주변기기를 하드웨어 자체로 다루지 않고 파일 형식으로 다룰 수 있도록 함으로써, 하드웨어의 자세한 사항을 모르더라도 하드웨어에 대한 이질감을 갖지 않고 사용할 있도록 함. 
        - 수많은 유틸리티 프로그램 : 유닉스 시스템은 대규모 프로젝트를 개발한 경우, 필요한 모든 프로그램을 새로 만들어 새로 만들어 제공하기 보다는 기존에 있는 작은 유틸리티 프로그램을 조합하여 해결할 수 있는 환경을 만드는데 많은 비중을 두고 개발. 프로그래머에 의해서 고안되었으므로 항상 대화식으로 진행. 프로그램 개발을 효과적으로 수행할 수 있도록 도구를 만드는데 역점을 둠 -> 개발시간을 단축
        - 다중프로세스 : 여러 프로세서를 동시에 지원, 하나의 프로세스가 아주 쉽게 새로운 프로세스를 만들 수 있음. -> 각각의 프로세스는 하나의 작업을 처리 할 수 있는데 여러개의 포르세스가 지원되므로 동시에 여러가지 작업 처리 가능 -> 각 프로세스를 원활하게 수행하기 위해 CPU 시간을 여러 프로세서로 분재하여, 우선순위에 따라 시스템내에 조정
     - 장점 
        - 안전 및 보호 기능
        - 입출력의 방향전환, 파이프 기능
        - 시스템과 사용자 사이의 명령어 번역기인 쉘은 확장성과 조작성이 풍부
        - 각종 부대 장치는 각각의 독립성을 지님
        - 유연하게 통신 가능
     - 유닉스 시스템의 개념
        - 일반 텍스트 파일, 명령행 인터프리터, 계층적인 파일 시스템, 장치 및 특정한 형식의 프로세스 간 통신을 파일로 취급
        - 소프트웨어 공학 측면에서, 유닉스 C의 사용과 유닉스 철학이라는 부분
     - 유닉스 상표권 : 오픈 그룹이 갖고 있음
        - 오픈 그룹?
           - 설명 : 현재 300개가 넘는 단체가 소속해 있는 업체 및 기술 중립 산업 연합체
           - 설립 연도 : 1996년 설립
     - 유닉스 소스 코드에 대한 저작권 : 노벨이 소유
        - 노벨?
           - 설명 : 미국의 컴퓨터 소프트웨어 관련 기업
     - 프로그래밍 언어 
       - C
       - 어셈블리어
- (1-2) 선택 기술
   - 게임 개발 엔진에서의 선택 : Node.js
      - 이유 : 이벤트 기반의 비동기 방식으로 서버측에서 지속적인 메세지가 왔는가를 확인하는 클라이언트의 작업이 축소 되어 서버에 무리를 적게 준다. -> 빠른 일처리가 가능하므로
   - 운영 체제에서 선택 : 유닉스
      - 이유 : 뛰어난 이식성으로 다양한 컴퓨터에서 사용이 가능하므로 조원 내에 컴퓨터가 다다르므로 좋고, 단순한 명령어를 사용하기 때문에 구현하기에 더 쉬울것으로 생각된다. 또한, 안전 및 보호기능으로 우리가 개발하는 게임의 안전성을 보장한다.
