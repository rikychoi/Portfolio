📜Portfolio
최윤기(Richard Yoonki Choi) 포트폴리오

# 📝 목차
각 항목을 클릭하면 해당하는 위치로 이동합니다.
### 1. [Intro](#intro)
### 2. [Skills](#skills)
### 3. [experience](#experience)
### 4. [Education](#education)
### 5. [Qualifications](#qualifications)
### 6. [Projects](#projects)

# Intro
기술을 이해하고 직접 구현할 수 있는 보안 엔지니어를 지향합니다.
주어진 보안 업무에 머무르지 않고 필요한 개선점을 찾아 실행합니다.
개발 역량을 활용해 반복 업무를 자동화하고 보안 문제를 구조적으로 해결합니다.
기술적 판단뿐 아니라 서비스와 운영 환경에 미치는 영향까지 함께 고려합니다.
문제를 발견하는 데서 끝나지 않고 실제 대응과 개선으로 연결하는 보안 엔지니어가 되고자 합니다.
# Skills

| Category       | Skills                                          | Notes                                    |
| -------------- | ----------------------------------------------- | ---------------------------------------- |
| Programming    | C, C++, Go, Python                              | 서버 기능 구현, 데이터 처리, 네트워크 프로그래밍 및 보안 도구 개발  |
| Security       | IDA Pro, x64dbg, Nmap, Metasploit, Nuclei, YARA | 리버스 엔지니어링, 악성코드 분석, 취약점 및 네트워크 분석        |
| Infrastructure | AWS, Linux, Docker, VMware                      | 서버 구축 및 운영, 분석 환경 구성, 서비스 배포 및 가상화 환경 활용 |
| Backend        | Django, SQL, Git                                | API 서버 개발, 데이터 처리 및 형상 관리                |

# Experience

### 소만사

#### Security Engineer

* 2026.07~
* CTI 서버 개발
* EDR 서버 유지보수
* Go, Python 기반 서버 기능 개발 및 데이터 처리
* 보안 서비스 운영 과정에서 발생하는 이슈 분석 및 개선

#### Security Engineer

* 2025.08~2025.10
* 악성코드 분석 및 리버스 엔지니어링
* 정적 및 동적 분석을 통한 악성 행위 분석
* Windows 프로세스 실행 흐름과 메모리 동작 분석
* 분석 결과 기반 주요 행위 및 특징 정리

#### Security Intern

* 2025.01~2025.02
* EDR 팀 근무
* IDA Pro, x64dbg를 활용한 리버스 엔지니어링
* 훅킹과 인젝션 등 Windows 기반 공격 기법 분석
* 악성코드 분석 및 분석 보고서 작성

# Education
* 동국대학교 정보통신공학전공 
* 2019.03~2025.08

# Qualifications
- 정보처리기사
- 정보보안기사
- SQLD
- ADsP
- AWS certified solution architect - associate
- TOEIC
- TOEIC SPEAKING
# Projects

**🔗 정보유출사고 알림 서비스** [<ins>(github 링크)</ins>](https://github.com/rikychoi/Threat_alert_service)
* **요약**: `ransomware.live` Pro API를 활용하여 최신 랜섬웨어 침해사고 데이터를 수집하고 실시간 알림을 제공하는 서비스
* **주요 역할**: 서비스 아키텍처 설계 및 백엔드 데이터 처리 로직 구현
* **핵심 구현**: **AWS 인프라 구축, 서버 관리 및 데이터 수집기(Crawler) 개발** 총괄
    * **데이터 수집 파이프라인**: Python 기반 APScheduler와 requests를 활용한 API 데이터 자동 수집기 구현 
    * **인프라 및 서버**: AWS 환경 내에서 FastAPI 백엔드 서버 및 MariaDB 데이터베이스 구축 및 운영 
    * **실시간 대응 체계**: 신규 유출 정보 발생 시 Slack API를 연동한 즉각적인 알림 전송 시스템 지원 
    * **데이터 가시화**: 수집된 위협 데이터를 대시보드 및 검색 기능을 통해 직관적으로 조회 가능하도록 설계 

---

**🔗 (캡스톤디자인 프로젝트)BidHub: 블록체인 기반 부동산 경매 플랫폼** [<ins>(github 링크)</ins>](https://github.com/rikychoi/Capstone_BidHub)
* **요약**: 스마트 컨트랙트를 활용하여 경매 과정의 투명성과 신뢰성을 확보한 부동산 경매 서비스
* **주요 역할**: 시스템 전체 구조 설계 및 블록체인 스마트 컨트랙트(Solidity) 개발 담당
* **핵심 기능**: 
    * 경매 입찰, 낙찰 및 대금 지불 로직 스마트 컨트랙트 구현
    * 블록체인 네트워크와 서비스 간의 연동 구조 설계 및 데이터 무결성 확보

---

**🔗 소프트웨어공학및설계 과목 프로젝트 : 커뮤니티 사이트 구현** [<ins>(github 링크)</ins>](https://github.com/rikychoi/SW_Project)
* **요약**: 사진 업로드 및 개인 메시지(DM) 기능을 포함한 커뮤니티 플랫폼
* **역할**: 프론트엔드를 제외한 백엔드 로직, DB 설계 및 서버 인프라 전체 담당
* **핵심 기능**: 
    * **사진 업로드 시스템**: 멀티미디어 데이터 처리 및 저장 로직 구현
    * **개인 메시지(DM) 기능**: 사용자 간 실시간 메시지 전송 및 데이터베이스 관리

---


# 📂 악성코드 분석/위협 추적

**1. 📄 북한계 악성코드 분석보고서** [<ins>(보고서 링크)</ins>](https://rikychoi.github.io/Portfolio/북한계%20악성코드%20분석보고서.pdf)
* **요약**: 바로가기 파일로 위장한 국가 공공기관 대상의 인포스틸러
* **핵심 기법**: .lnk 확장자를 이용한 피해자 기만 및 다중 간접 실행과 난독화로 인한 탐지/분석 난이도 악화
* **주요 동작**: 
    * 클라우드 서버를 활용한 C2 통신과 시스템 정보의 유출
    * 총 4개의 파일을 사용한 간접 실행과 2중 난독화 및 암호화로 사전 탐지 방지


---

**2. 📄 Contagious Interview campaign 분석보고서** [<ins>(보고서 링크)</ins>](https://rikychoi.github.io/Portfolio/Contagious%20Interview%20campaign%20분석보고서.pdf)
* **요약**: IT 구직자들을 대상으로 암호화폐 유출을 시도하는 북한의 피싱 악성코드 캠페인
* **핵심 기법**: 유명 기업의 채용담당자를 사칭하여 피해자를 대상으로 악성코드 설치 및 실행 유도
* **주요 악성코드**: 
    * BeaverTail : 사용자 브라우저의 정보에 접근해 암호화폐 지갑 정보를 유출, 아래의 InvisibleFerret 악성코드를 드롭
    * InvisibleFerret : BeaverTail과 마찬가지로 암호화폐 정보를 유출하고 키로깅 및 공격자의 명령을 수신하여 추가 동작


---

**3. 📄 Phorpiex 악성코드 분석 보고서** [<ins>(보고서 링크)</ins>](https://rikychoi.github.io/Portfolio/Phorpiex%20분석.pdf)
* **요약**: 스팸 메일 대량 발송 및 추가 페이로드 유포 특화 봇넷(Botnet)
* **핵심 기법**: `Zone.Identifier` 삭제를 통한 외부 유입 흔적 은폐 및 XOR+NOT 복호화
* **주요 동작**: 
    * HTTP 기반 C2 통신을 통한 킬스위치 확인 및 악성 페이로드(`Document.zip`) 다운로드
    * SMTP 프로토콜 직접 구현을 통한 타겟 대상 피싱 메일 대량 발송

---

**4. 📄 악성코드 샘플 상세 분석 보고서** [<ins>(보고서 링크)</ins>](https://rikychoi.github.io/Portfolio/악성코드샘플%20분석보고서.pdf)
* **요약**: Windows 32bit RAT+Worm
* **핵심 기법**: 자가 복호화 및 `explorer.exe` 대상 프로세스 할로잉(Process Hollowing)
* **주요 동작**: 
    * 하드코딩된 3개 도메인과 UDP 암호화 통신 및 데이터 유출
    * 쉘코드(1)과 (2)의 상호 감시를 통한 프로세스 유지 및 자가 전파
