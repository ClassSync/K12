## 메일 수신을 위한 설정
### Gmail과 Exchange Online 양쪽으로 메일을 수신하기 위한 설정

> 레코드	값	순위	비고
> 
> MX	school-hs-kr.mail.protection.outlook.com	100
>        	
> MX	ALT1.ASPMX.L.GOOGLE.COM	5
>        	
> MX	ALT2.ASPMX.L.GOOGLE.COM	5
>        	
> MX	ALT3.ASPMX.L.GOOGLE.COM	10
>        	
> MX	ALT4.ASPMX.L.GOOGLE.COM	10
>        	
> MX	ASPMX.L.GOOGLE.COM	1
>        	
> TXT	"v=spf1 include:_spf.google.com include:spf.protection.outlook.com -all"	 0
>         

#### 메일 동시수신 설정 m365.kr 참고 이미지
![image](https://github.com/ClassSync/K12/assets/16409151/422274a9-dc3e-4d3c-a1c9-0ca0c7e30710)

