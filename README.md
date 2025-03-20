# StudyBridge

팀 프로젝트 <br/>
주제 : E-러닝 애플리케이션 플랫폼

브랜치	역할
* main	배포용 브랜치. 안정적인 코드만 유지. 직접 작업 X
* develop	개발 진행 브랜치. 모든 기능 개발 후 여기로 병합
* feature/{기능명}	새로운 기능 개발용 브랜치
* hotfix/{버그명}	운영 중 긴급 버그 수정 브랜치
* release/{버전명}	배포 전 QA 및 테스트를 위한 브랜치

서비스 이름	역할
* gateway-service
  // API Gateway (클라이언트 요청을 각 서비스로 라우팅) // localhost:8080
* auth-service //	사용자 인증 (JWT, OAuth)
* lecture-service	 // 강의 CRUD, 수강 신청
* payment-service	 // 강의 결제 처리 (카카오페이, 카드)
* ai-teacher-service //	AI 강사 (GPT API 연동, 챗봇식 대화)
* chat-service //	강사와 학생 간 1:1 채팅 기능
* message-service //	채팅 내용 저장 (MongoDB 사용 가능)

