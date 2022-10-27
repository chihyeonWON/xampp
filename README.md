# xampp
xampp 관련 설정과 오류해결방법 정리

### 오류명 Error: MySQL shutdown unexpectedly.

2022-10-27 대학 과제 수행 중 xampp에서 mysql을 start 했을 때   
다음과 같은 오류가 발생하였다.
![image](https://user-images.githubusercontent.com/58906858/198321680-69174a75-46b1-480d-8c3f-79c2159293a0.png)


### 해결 방법

해결 방법은 간단했다.   

C:\xampp/mysql/backup 파일의 모든 파일을 복사해서

![image](https://user-images.githubusercontent.com/58906858/198322046-0500823b-e709-4187-a03b-598c6cc2eaf1.png)

C:\xampp/mysql/data 파일로 붙여쓰면(강제)

![image](https://user-images.githubusercontent.com/58906858/198322457-31138bec-6458-4e42-99f1-f3e1566c5110.png)

문제가 해결되고 정상적으로 구동되는 것을 알 수 있다.
![image](https://user-images.githubusercontent.com/58906858/198322616-206a2dc7-c4ba-40e5-92fa-3a8776112e19.png)

