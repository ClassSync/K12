# 클라우드 통합 계정 만들기
### 교육용 Microsoft 365 계정과 Google Workspace 계정을 하나로 통합
**통합 계정 SSO 구축을 완료한 경우 교육용 Microsoft 365 계정으로 교육용 서비스와 콘텐츠 및 디바이스에 SSO 됩니다.**
![image](https://github.com/ClassSync/K12/assets/16409151/ccc96d3e-65c9-416e-8fb9-7785838e553b)



### A. 통합 계정 만들기  

**1. 앱 설치 및 초기설정**    
> 1.1 클래스싱크 앱 설치  
> https://apps.microsoft.com/store/detail/classsync/9PJ792P907Q9?hl=ko-kr&gl=kr
> ![image](https://github.com/ClassSync/K12/assets/16409151/9985fbd4-25e1-4b34-bead-94d5867614d1)
> 1.2 [School Admin Login] 버튼 선택 후 학교 관리자 계정으로 로그인
> ![image](https://github.com/ClassSync/K12/assets/16409151/beee0887-d0e1-4e36-8fd2-c62ceb5f5673)   
> 1.3 [설정] 메뉴 선택 후 설정 화면에서 학년도, 소속 교육청, 학교명 검색후 학교를 선택하고 학교도메인 사용등록, 초기 비번 설정
> ![image](https://github.com/ClassSync/K12/assets/16409151/aaa15489-69da-4cda-92a4-e4176d8f3cc3)   

**2. 통합 계정 만들기**     
> 2.1 통합 계정 가져오기 (클라우드에 저장된 기존 계정 정보를 가져와서 정리합니다.)
> ![image](https://github.com/ClassSync/K12/assets/16409151/b2dc0533-4772-45ec-899f-6eba727d7628)   
> 2.2 CSV 내보내기 
>  ![image](https://github.com/ClassSync/K12/assets/16409151/e9768ee4-ce5d-4bb9-9798-10c5a1e2205c)   
> 2.3 액셀에서 CSV 파일을 편집하고 저장 **(CSV 쉼표로 분리)** , 편집이 완료된 파일 [Read CSV File] 또는 CSV 가져오기    
> ![image](https://github.com/ClassSync/K12/assets/16409151/ab0eb25d-c581-47c3-b9d9-c041439e682a)   
> 2.4 통합 계정 만들기   
> **OneID 목록을 기준으로 MS 계정 만들기를 를 선택하면 Microsoft 365에 계정이 생성되고 구글 계정 만들기를 선택하면 구글 계정이 생성됩니다. Google Workspace와 SSO를 구성한 경우 계정이 동기화 됩니다.**   
> **이미 계정이 있고 학번과 이름이 변경된 경우 변경된 내용으로 표시이름이 갱신됩니다.**       
> ![image](https://github.com/ClassSync/K12/assets/16409151/964c477f-dab4-4d98-a96f-bfe72b09ea20)


### B. 통합 계정 SSO 구축하기

> **학교 전용 Google 테넌트와 Microsoft 365 테넌트를 보유하고 있어야 합니다.**   
> **통합 계정에 연결할 도메인에 대해 DNS 레코드 변경이 가능해야 합니다.**   
> **통합 계정 SSO 무료 구축문의 : hjshin@dongseo.com**

### * 장치별 SSO 로그인 

> **크롬 OS가 설치된 장치에 통합 아이디로 로그인**


https://github.com/ClassSync/K12/assets/16409151/96aea36f-a44d-4f9f-b24e-350eabd42f2f


> **윈도우 OS가 설치된 장치에 통합 아이디로 로그인**


https://github.com/ClassSync/K12/assets/16409151/4d9798e6-7cf0-4883-97f8-d004c5127cf8

