# StudyBridge

팀 프로젝트 <br/>
주제 : E-러닝 애플리케이션 플랫폼

서비스 이름	역할
* gateway-service	API Gateway (클라이언트 요청을 각 서비스로 라우팅)
* auth-service	사용자 인증 (JWT, OAuth)
* lecture-service	강의 CRUD, 수강 신청
* payment-service	강의 결제 처리 (카카오페이, 카드)
* ai-teacher-service	AI 강사 (GPT API 연동, 챗봇식 대화)
* chat-service	강사와 학생 간 1:1 채팅 기능
* message-service	채팅 내용 저장 (MongoDB 사용 가능)
