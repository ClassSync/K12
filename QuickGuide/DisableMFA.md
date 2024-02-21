# 사용자 보안 설정
## 사용자가 2차 인증등 보안 설정으로 로그인에 어려움이 있는 경우 아래의 설정을 변경

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
