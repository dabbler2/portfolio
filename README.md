## 1. chatPT
#### 실시간 영상 기반 일대다 홈 퍼스널 트레이닝 서비스

기간: 2024.01.12 - 2024.02.20

인원: 백엔드 4명

<a href="https://www.youtube.com/watch?v=4tx2QPnlEFg">시연영상</a> <a href="https://github.com/kim-sunah/chatpt">Repository</a>

기술 : Javascript, Nest.js / React / MySQL / AWS EC2, S3 / WebRTC / WebSocket, Socket.io / RabbitMQ / GitHub Actions

역할

- Nest.js를 이용한 백엔드 api 구현
- MySQL에서 복합 인덱스, 풀텍스트 인덱스 등 활용해 DB 관리
- AWS S3를 이용한 이미지, 영상 자료 관리
- React를 이용한 프론트엔드 페이지
- 포트원, 토스페이먼츠에서 제공하는 api 활용해 테스트 결제
- Winston 라이브러리와 슬랙 웹훅을 연동해 슬랙 채널에 로깅
- GitHub Actions, AWS Codedeploy을 이용한 CI/CD
- 텍스트 등록 시 아호 코라식 알고리즘 활용한 금칙어 처리

트러블 슈팅

- 배포 후 EC2 인스턴스 메모리 부족으로 인한 프로그램 실행 난항
    - 인스턴스 업그레이드는 추가 과금 부담 존재
    - 메모리 스와핑을 활용해 물리적 메모리 한계를 우회
