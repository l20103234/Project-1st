# 1. 프로젝트 개요
Kubernetes를 활용한 3Tier 웹 서비스 구축

<br/>
<br/>

# 2. 프로젝트 기획 배경
컨테이너 환경구성( Web : NginX ,WAS : Tomcat , DB : mariadb 사용)

- WEB , WAS , DB 각각 3Tier 인프라 통신
- 부하에 따른 Autoscaling 가능해야 하며 이를 증명
- DB에 대한 정보 변경이 반드시 WAS에서 처리 가능

<br/>
<br/>

# 3. 아키텍처
![44444.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/28ac15ec-ceb9-4e66-b4ec-b6d88293f34e/82051f2b-7d2d-4a31-8f42-ce734c93e01f/44444.png)


<br/>
<br/>

# 4. Page
![image](https://github.com/user-attachments/assets/71f88818-3910-4b36-8b3b-83d63c0ee12c)
![image](https://github.com/user-attachments/assets/96c801b0-c762-4efd-860c-faec3ace0572)
![image](https://github.com/user-attachments/assets/0e2bb83e-3f42-4288-9a14-37a079b59adb)
![image](https://github.com/user-attachments/assets/40e3c5bf-7282-41c9-baf1-2701228c1259)
