### 컨테이너 기술이란 무엇입니까
호스트 OS상에 논리적인 구획을 만들고, 애플리케이션을 작동시키기 위해 필요한 라이브러리나 애플리케이션 등을 하나로 모아, 마치 별도의 서버인 것처럼 사용할 수 있게 만든 것.
### 도커란 무엇입니까
애플리케이션 실행에 필요한 환경을 하나의 이미지로 모아두고 그 이미지를 사용하여 다양한 환경에서 애플리케이션 실행 환경을 구축 및 운용하기 위한 오픈소스 플랫폼.
### 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?
도커 파일은 인프라 구성을 기술한 파일이다. 다시 말해 내부에 배이스가 될 도커 이미지, 도커 컨테이너 안에서 수행한 명령, 환경변수 등의 설정, 도커 컨테이너 안에서 작동시킬 데몬을 실행과 같은 내용이 포함되는 컨테이너 구성 정보를 기술하기 위한 파일이다.
도커 이미지는 애플리케이션의 실행에 필요한 프로그램 본체, 라이브러리, 미들웨어, OS나 네트워크 설정을 모은 파일들이 저장된 디렉토리이다.
도커 컨테이너는 사용자 공간을 추상화함으로써 경량 OS 수준의 가상화를 제공한다. 컨테이너는 호스트 시스템의 커널을 공유하며 호스트 OS에서 실행되는 컨테이너는 코드와 모든 종속성을 패키지화하여 애플리케이션이 다른 환경에서도 빠르고 안정적으로 실행될 수 있게 해주는 표준 소프트웨어 장치이다.
이를 종합하면 도커 파일은 도커 이미지를 만들기 위한 템플릿으로 볼 수 있고 도커 이미지는 도커 컨테이너를 실행하기 위한 템플릿이며 도커 컨테이너는 도커 이미지를 실행시킨 인스턴스이다.