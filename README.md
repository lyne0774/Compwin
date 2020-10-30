<H1>통합 로그 분석 시스템</H1>

Nginx 웹 서버 + Filebeat 테스트환경 동시 제공

<H2>사용법</H2>
Docker-compose.yml이 있는 경로에서 docker-compose up 입력

<H2>Niginx</H2>
포트: 80<br/>
localhost:80 접속하여 access log와 error log를 남길 수 있음<br/>
저장 경로<br/>
access log : nginx/log/host.access.log<br/>
error log : nginx/log/host.error.log

<H2>Kibana</H2>
포트: 5601<br/>
localhost:5601 접속하여 기록된 로그 내용을 확인하고 시각화하여 확인 가능
