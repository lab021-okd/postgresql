Postgresql
==========

OKD 클라우드 플랫폼 구축 시 각 세부를 지원하기 위해 Postgresql에 대한 Docker 이미지와 OKD Cateogry Templdate를 구축하였다.

## Posgresql

PostgreSQL은 확장 가능성 및 표준 준수를 강조하는 객체-관계형 데이터베이스 관리 시스템(ORDBMS)의 하나이다. BSD 허가권으로 배포되며 오픈소스 개발자 및 관련 회사들이 개발에 참여하고 있다. 데이터베이스 서버로서 주요 기능은 데이터를 안전하게 저장하고 다른 응용 소프트웨어로부터의 요청에 응답할 때 데이터를 반환하는 것이이다. 

## Docker
Dockerfile-PostgreSQL 용 Docker 컨테이너 이미지를 만든다.

## Template
OKD에서 실행 가능한 template 파일로서 기본적인 구성을 통해 사용자가 컴스텀하게 변경 가능하도록 구성을 했다