# paas-ta-webide-release Guide

##1. WebIde Configuration
- mysql :: 1 machine
- web-ide-broker :: 1 machine

##2. Deploy

>`$ sh deploy-vsphere.sh`

##3. src
src 폴더에 각 package의 설치파일이 위치해야 한다.

src <br>
├── java <br>
│     └── jre-8u77-linux-x64.tar.gz <br>
├── mariadb <br>
│     └── mariadb-10.1.22-linux-x86_64.tar.gz <br>
├── web-ide-broker <br>
      └── web-ide-broker.jar <br>
