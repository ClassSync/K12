# 클라우드 통합 계정 만들기
### 교육용 Microsoft 365 계정과 Google Workspace 계정을 하나로 통합
**통합 계정 SSO 구축을 완료한 경우 교육용 Microsoft 365 계정으로 교육용 서비스와 콘텐츠 및 디바이스에 SSO 됩니다.**
![classsync_v2](https://github.com/ClassSync/K12/assets/16409151/854868fb-7845-47c8-920f-44bf12f12c7c)


### A. 통합 계정 만들기  

**1. 앱 설치 및 초기설정**    
> 1.1 클래스싱크 앱 설치  
> https://apps.microsoft.com/store/detail/classsync/9PJ792P907Q9?hl=ko-kr&gl=kr
> ![image](https://github.com/ClassSync/K12/assets/16409151/9985fbd4-25e1-4b34-bead-94d5867614d1)
> 1.2 [School Admin Login] 버튼 선택 후 학교 관리자 계정으로 로그인
> ![image](https://github.com/ClassSync/K12/assets/16409151/4d00fbb6-e885-4c76-9a32-6116c066dd27)
> 1.3 [설정] 메뉴 선택 후 설정 화면에서 학년도, 소속 교육청, 학교명 검색후 학교를 선택하고 학교도메인 사용등록, 초기 비번 설정
> ![image](https://github.com/ClassSync/K12/assets/16409151/561bd4e3-b441-4498-a685-30b614c85c53)

**2. 통합 계정 만들기**     
> 2.1 통합 계정 가져오기 (클라우드에 저장된 기존 계정 정보를 가져와서 정리합니다.)
> ![image](https://github.com/ClassSync/K12/assets/16409151/7dff22d1-624d-4c09-b7b5-dcfa46a11ba1)
> 2.2 CSV 내보내기 
> ![image](https://github.com/ClassSync/K12/assets/16409151/670cbb58-e394-43ae-bc69-97c841c5f6a9)
> 2.3 액셀에서 CSV 파일을 편집하고 저장 **(CSV 쉼표로 분리)** , 편집이 완료된 파일 [Read CSV File] 또는 CSV 가져오기    
> ![image](https://github.com/ClassSync/K12/assets/16409151/d41a171a-14f5-4ee3-919a-7549ead894fe)
> 2.4 통합 계정 만들기   
> **Microsoft 365에 계정이 생성됩니다. 기존 계정은 표시 이름을 변경할 수 있습니다. Google Workspace와 SSO를 구성한 경우 계정이 동기화 됩니다.**   
> ![image](https://github.com/ClassSync/K12/assets/16409151/f153899f-77c9-4208-835c-02658259fb8e)

### B. 통합 계정 SSO 구축하기

> **학교 전용 Google 테넌트와 Microsoft 365 테넌트를 보유하고 있어야 합니다.**   
> **통합 계정에 연결할 도메인에 대해 DNS 레코드 변경이 가능해야 합니다.**   
> **2023년 11월 30일 까지 모든 교육청에 통합 계정 SSO 구축을 무료 지원할 예정입니다. 무료 지원은 당사 사정에 따라 조기 종료될 수 있습니다.**
> **통합 계정 SSO 무료 구축문의 : hjshin@dongseo.com**

### 장치별 SSO 로그인 

> **크롬 OS가 설치된 장치에 통합 아이디로 로그인**


https://github.com/ClassSync/K12/assets/16409151/96aea36f-a44d-4f9f-b24e-350eabd42f2f


> **윈도우 OS가 설치된 장치에 통합 아이디로 로그인**


https://github.com/ClassSync/K12/assets/16409151/4d9798e6-7cf0-4883-97f8-d004c5127cf8

