통합 로그 분석 시스템

Nginx 웹 서버 + Filebeat 테스트환경 동시 제공

사용법<br/>
Docker-compose.yml이 있는 경로에서 docker-compose up 입력

Niginx 웹 서버 포트: 80
localhost:80 접속하여 access log와 error log를 남길 수 있음
저장 경로
access log : nginx/log/host.access.log
error log : nginx/log/host.error.log

Kibana 포트: 5601
localhost:5601 접속하여 기록된 로그 내용을 확인하고 시각화하여 확인 가능
