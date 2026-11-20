# 사용자 보안 설정
## 사용자가 다단계 인증으로 로그인하기 어려운 경우 아래 설정을 변경합니다.
초·중·고등학교에서는 수업 시간 중 학생의 휴대전화 사용이 제한되거나 Microsoft Authenticator를 사용할 수 없어 다단계 인증을 수행하기 어려울 수 있습니다. 학생이 원활하게 Microsoft 365에 로그인하여 수업에 참여할 수 있도록 학교 환경에 맞게 보안 기본값을 변경할 수 있습니다. 

보안 기본값은 특정 학생이나 그룹만 제외하도록 설정할 수 없습니다. **보안 기본값을 사용 안 함으로 변경하면 학생뿐만 아니라 교직원과 관리자를 포함한 조직 전체에서 보안 기본값이 제공하던 다단계 인증 보호가 해제됩니다.** 전역 관리자는 Microsoft Entra 관리 센터, Azure Portal, Microsoft Intune 관리 센터 및 Microsoft 365 관리 센터에 접속할 때 Microsoft의 필수 다단계 인증 정책에 따라 계속 인증을 요구받을 수 있습니다. Outlook, Teams 등 일반 Microsoft 365 서비스의 모든 로그인까지 다단계 인증이 항상 적용되는 것은 아닙니다.

보안 기본값에서 제공하는 다단계 인증은 계정 손상 위험을 크게 낮추는 데 도움이 됩니다. Microsoft는 다단계 인증이 일반적인 계정 공격의 99.9% 이상을 차단할 수 있으며, 보안 기본값을 사용하는 조직은 계정 손상 비율이 낮아지는 것으로 안내하고 있습니다.   

**학생의 로그인 환경에 문제가 없는 테넌트에서는 보안 기본값을 사용(권장)으로 유지하십시오. 보안 기본값을 사용 안 함으로 변경한 후 관리자 계정에 별도의 다단계 인증 보호를 적용하지 않으면 계정 탈취와 관리자 권한 악용 위험이 커질 수 있습니다. 관리자 계정에는 다단계 인증 보호를 반드시 적용하십시오.**   

### 1. 보안 기본값 변경 (다단계 인증 해제)
Entra 관리 센터 화면에서 개요 > 속성 탭에서 하단의 보안 기본값에서 보안 기본값 관리를 선택하면 표시되는 우측 화면에서 **보안 기본값 비활성화(권장하지 않음)** 선택 후 저장    
바로가기 : https://entra.microsoft.com/#blade/Microsoft_AAD_ConditionalAccess/SecurityDefaults?Microsoft_AAD_IAM_legacyAADRedirect=true
![image](https://github.com/ClassSync/K12/assets/16409151/6ca63aaa-9120-4de0-a6f6-803f0c0aaf49)

### 2. 계정 보안 유지 해제
Entra 관리 센터 화면에서 보호 > 암호 재설정 > 등록을 선택하면 표시되는 화면에서 **'사용자가 로그인 시 등록하도록 요구하시겠습니까?' 아니오** 선택 후 저장   
바로가기 : https://entra.microsoft.com/#view/Microsoft_AAD_IAM/PasswordResetMenuBlade/~/Registration/fromNav/Identity?Microsoft_AAD_IAM_legacyAADRedirect=true
![image](https://github.com/ClassSync/K12/assets/16409151/c27b3189-b7aa-47cb-a894-13e4e21da2f6)

### 3. 암호 만료 정책 설정
Microsoft 365 관리 센터 화면에서 설정 > 조직설정을 선택하면 표시되는 화면에서 보안 및 개인 정보 탭을 선택 > 암호 만료 정책을 선택하면 표시되는 화면에서 **암호가 만료되지 않도록 설정(권장)** 선택 후 저장   
바로가기 : https://admin.microsoft.com/Adminportal/Home?#/Settings/SecurityPrivacy/:/Settings/L1/PasswordPolicy
![image](https://github.com/ClassSync/K12/assets/16409151/7f29224f-06a2-40ca-8a7e-ad7beb843db7)

### 4. 다단계 인증을 해제한 경우 관리자 암호 변경 
바로가기 : https://go.microsoft.com/fwlink/?linkid=2224198   
![image](https://github.com/ClassSync/K12/assets/16409151/ad948fa9-3aa5-4654-90ed-655a6dc5e1d9)

### 5. 보안 기본값을 비활성화 하는 경우 모든 전역관리자에 다단계 인증을 필수 설정
Microsoft Entra 관리 센터 화면 > 사용자 단위 다단계 인증 화면에서 전역관리자 검색 후 MFA 사용 선택
바로가기 : https://entra.microsoft.com/#view/Microsoft_AAD_IAM/MultifactorAuthenticationConfig.ReactView
![image](https://github.com/user-attachments/assets/05c0a72e-6286-41ce-9420-db64d1ea25c5)
