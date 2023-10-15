# media-buddies-docs

## 1. 개요
미디어 버디스(media buddies)는 클라우드 기반의 플랫폼으로 미디어 자산 관리와 인코딩을 웹에서 손쉽게 이용할 수 있는 서비스를 제공하는 솔루션입니다. 
이 서비스를 통해 다양한 종류의 미디어 자산을 효율적으로 관리하고 처리하여 사용자들에게 콘텐츠를 제공합니다.
## 2. 프로젝트 서비스
![image](https://github.com/dogineer/mediabuddies-docs/assets/61046271/d73436ba-72cf-4923-8ea4-4dcc628ee1a8)

![image](https://github.com/dogineer/mediabuddies-docs/assets/61046271/57f5565d-c328-454e-b18a-a1c400dc3bb8)


### **서비스 경험하기**
- Media Buddies [방문하기](https://mediabuddies.kro.kr)
- FTP 접속 ( ftp://guest@mediabuddies.kro.kr | 1234 )
- 프리미어 프로 플러그인 [설치](https://github.com/dogineer/mediabuddies-adobe-panel)

### [**SERVER-01**](https://github.com/dogineer/mediabuddies-server01) :
![image](https://github.com/dogineer/mediabuddies-docs/assets/61046271/de3e1c4a-c8c2-40ae-8227-999b255e5625)

> 위의 링크 클릭 시 해당 리포지토리 상세 내용을 보실 수 있습니다.
- 프론트 오피스: 회원가입, 영상 등록, 영상 프리뷰, 프리미어 임포트
- 백 오피스: 유저, 부서, 계급, 팀 관리

### [**SERVER-02**](https://github.com/dogineer/mediabuddies-server02) :
![image](https://github.com/dogineer/mediabuddies-docs/assets/61046271/8d9f729f-0b62-4628-806a-28a6d8c057e9)

> 위의 링크 클릭 시 해당 리포지토리 상세 내용을 보실 수 있습니다.
- 다양한 형식과 포맷의 미디어를 변환하여 필요한 형태로 가공하여 트랜스코딩 서비스
- 메타데이터 추출 및 파일 관리

### [**Adobe-panel ( adobe-panel )**](https://github.com/dogineer/mediabuddies-adobe-panel) :
> 위의 링크 클릭 시 해당 리포지토리 상세 내용을 보실 수 있습니다.
- 어도비 소프트웨어 내에서 현재 프로젝트 서비스를 사용할 수 있습니다.

## 3. 프로젝트 기술 스택

### Application
java, spring boot
 
### Database
Mysql(서비스 DB), redis(세션 관리)

### CI/CD
GCP, docker, spring cloud(eureka, gateway)

## 4. ERD
![image](https://github.com/dogineer/mediabuddies-docs/assets/61046271/cfab9463-3e4e-49e5-a280-88b82af947c0)
