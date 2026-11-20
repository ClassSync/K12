# 사용자 보안 설정
## 사용자가 다단계 인증으로 로그인하기 어려운 경우 아래 설정을 변경합니다.
초·중·고등학교에서는 수업 시간 중 학생의 휴대전화 사용이 제한되거나 Microsoft Authenticator를 사용할 수 없어 다단계 인증을 수행하기 어려울 수 있습니다. 학생이 원활하게 Microsoft 365에 로그인하여 수업에 참여할 수 있도록 학교 환경에 맞게 보안 기본값을 변경할 수 있습니다.    

보안 기본값은 특정 학생이나 그룹만 제외하도록 설정할 수 없습니다. **보안 기본값을 사용 안 함으로 변경하면 학생뿐만 아니라 교직원과 관리자를 포함한 조직 전체에서 보안 기본값이 제공하던 다단계 인증 보호가 해제됩니다.**

전역 관리자는 Microsoft Entra 관리 센터, Azure Portal, Microsoft Intune 관리 센터 및 Microsoft 365 관리 센터에 접속할 때 Microsoft의 필수 다단계 인증 정책에 따라 계속 인증을 요구받을 수 있습니다. Outlook, Teams 등 일반 Microsoft 365 서비스의 모든 로그인까지 다단계 인증이 항상 적용되는 것은 아닙니다.

보안 기본값에서 제공하는 다단계 인증은 계정 탈취와 무단 접근 위험을 낮추는 데 도움이 됩니다.

**학생의 로그인 환경에 문제가 없는 테넌트에서는 보안 기본값을 사용(권장)으로 유지하십시오. 보안 기본값을 사용 안 함으로 변경하더라도 관리자 계정을 다단계 인증 없이 운영해서는 안 되며, 별도의 다단계 인증 보호를 반드시 적용해야 합니다.**   


### 1. 보안 기본값 변경 (다단계 인증 해제)
[Microsoft Entra 관리 센터](https://entra.microsoft.com)에 로그인한 후 다음 경로로 이동합니다.

**Entra ID → 개요 → 속성 → 보안 기본값 관리**

보안 기본값 관리 화면에서 다음과 같이 설정합니다.

- **보안 기본값:** 사용 안 함
- **사용 안 함 사유:** 학교의 사용자 인증 환경에 해당하는 사유 선택
- 설정을 확인한 후 **저장**을 선택합니다.

보안 기본값은 특정 학생이나 그룹만 제외할 수 없습니다. **사용 안 함으로 변경하면 학생, 교직원 및 관리자를 포함한 조직 전체에서 보안 기본값이 비활성화됩니다.**

전역 관리자와 주요 관리자 계정에는 5번 절차에 따라 사용자 단위 다단계 인증을 반드시 설정합니다.   
     
[보안 기본값 변경 바로가기](https://entra.microsoft.com/#blade/Microsoft_AAD_ConditionalAccess/SecurityDefaults?Microsoft_AAD_IAM_legacyAADRedirect=true)   
![image](https://github.com/ClassSync/K12/assets/16409151/6ca63aaa-9120-4de0-a6f6-803f0c0aaf49)

### 2. 계정 보안 유지 해제
Entra 관리 센터 화면에서 보호 > 암호 재설정 > 등록을 선택하면 표시되는 화면에서 **'사용자가 로그인 시 등록하도록 요구하시겠습니까?' 아니오** 선택 후 저장   
[계정 보안 유지 해제 바로가기](https://entra.microsoft.com/#view/Microsoft_AAD_IAM/PasswordResetMenuBlade/~/Registration/fromNav/Identity?Microsoft_AAD_IAM_legacyAADRedirect=true)   
![image](https://github.com/ClassSync/K12/assets/16409151/c27b3189-b7aa-47cb-a894-13e4e21da2f6)

### 3. 암호 만료 정책 설정
암호 만료 정책을 변경할 때는 학생, 교직원 및 관리자 계정에 동일한 정책이 적용될 수 있다는 점을 고려해야 합니다.   
Microsoft 365 관리 센터 화면에서 **설정 → 조직 설정 → 보안 및 개인정보 → 암호 만료 정책**을 선택하면 표시되는 화면에서 **암호가 만료되지 않도록 설정(권장)** 선택 후 저장   
[암호 만료 정책 설정 바로가기](https://admin.microsoft.com/Adminportal/Home?#/Settings/SecurityPrivacy/:/Settings/L1/PasswordPolicy)   
![image](https://github.com/ClassSync/K12/assets/16409151/7f29224f-06a2-40ca-8a7e-ad7beb843db7)

### 4. 다단계 인증을 해제한 경우 관리자 암호 변경
암호 변경이 필요한 계정은 Microsoft 암호 변경 페이지에서 새로운 암호로 변경합니다.

[Microsoft 암호 변경](https://passwordreset.microsoftonline.com)

암호 변경 화면에서 다음 정보를 입력합니다.

- 사용자 계정
- 현재 암호
- 새 암호
- 새 암호 확인

새 암호는 기존 암호와 다르게 설정하고, 다른 서비스에서 사용 중인 암호를 재사용하지 않습니다.   

### 5. 보안 기본값 비활성화 후 전역 관리자 및 필요한 사용자에게 다단계 인증 설정
보안 기본값을 사용 안 함으로 변경하면 조직 전체에서 보안 기본값이 제공하던 다단계 인증 보호가 해제됩니다. **모든 전역 관리자와 주요 관리자 계정에는 사용자 단위 다단계 인증을 반드시 설정해야 합니다.**

교직원 등 다단계 인증이 필요한 사용자는 관리자가 사용자 단위 MFA 화면에서 계정을 직접 선택하여 수동으로 설정할 수 있습니다. 수업 시간에 다단계 인증을 사용하기 어려운 학생 계정은 **MFA 사용 안 함** 상태로 유지할 수 있습니다.

Microsoft Entra 관리 센터에서 다음 경로로 이동합니다.

**Entra ID → 사용자 → 모든 사용자 → 사용자 단위 MFA**

이동한 후 다음과 같이 설정합니다.

- 다단계 인증을 적용할 전역 관리자, 주요 관리자, 교직원 또는 사용자를 선택합니다.
- 상단의 **MFA 사용**을 선택합니다.
- 확인 화면에서 **사용**을 선택합니다.
- 선택한 사용자의 상태가 `enabled`로 변경되었는지 확인합니다.
- 사용자가 다음 로그인 과정에서 Microsoft Authenticator 등 사용할 인증 방법을 등록하도록 안내합니다.

계정 유형별 설정 기준은 다음과 같습니다.

- **전역 관리자 및 주요 관리자:** 사용자 단위 MFA 필수 적용
- **교직원 및 보호가 필요한 사용자:** 학교 보안 정책에 따라 MFA 적용
- **수업 중 MFA를 사용할 수 없는 학생:** MFA 사용 안 함 상태 유지
- **자동화 및 서비스 계정:** 서비스 영향을 확인한 후 별도 관리

> **중요:** Microsoft 관리 포털에서 요구하는 필수 MFA와 사용자 단위 MFA는 서로 다른 인증 요구사항입니다. **전역 관리자와 주요 관리자 계정을 다단계 인증 없이 운영해서는 안 됩니다.**

> **참고:** 사용자 단위 MFA 화면의 상태는 다음과 같은 의미를 가집니다.
>
> - `disabled`: 사용자 단위 MFA를 사용하지 않는 상태
> - `enabled`: 사용자 단위 MFA가 활성화되었으며 인증 방법 등록이 필요한 상태
> - `enforced`: 인증 방법 등록을 완료하여 사용자 단위 MFA가 적용된 상태

사용자 단위 MFA를 활성화한 사용자는 다음 로그인 과정에서 Microsoft Authenticator, 전화 또는 조직에서 허용한 다른 인증 방법을 등록할 수 있습니다.

[사용자 단위 다단계 인증 설정 바로가기](https://entra.microsoft.com/#view/Microsoft_AAD_IAM/MultifactorAuthenticationConfig.ReactView)   
<img width="1215" height="764" alt="image" src="https://github.com/user-attachments/assets/8e7487e6-162e-44e3-935f-ac050638fba0" />


