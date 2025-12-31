## java 프로젝트에서 maven 프로젝트로 변경 방법
1. 프로젝트 우클릭
2. Configure -> Convert to Maven Project 클릭
<img width="756" height="318" alt="image" src="https://github.com/user-attachments/assets/8f37d793-6d06-44e0-bac8-68fedeb54369" />

3. groupId 입력 후 finish
4. 여러 개의 디렉토리와 pom.xml이 생성됨
<img width="461" height="151" alt="image" src="https://github.com/user-attachments/assets/c730f83b-19f1-458f-8009-5531306a3dd6" />

5. pom.xml에 http로 되어있는 url을 전부 https로 변경
<img width="942" height="422" alt="image" src="https://github.com/user-attachments/assets/ba7540df-dbe5-4b87-a586-8a9f84a23963" />

6. maven repository에서 필요한 의존성 다운받아서 pom.xml에 입력하여 사용
