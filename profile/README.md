# 공공데이터를 이용한 공연 티켓팅 웹서비스 - 티켓온보딩

<p align="le">
  <img src="https://github.com/SKUWooU/.github/assets/126756270/453866d6-8496-413a-87c5-4f90934f3e88">
</p>

## 프로젝트 개요
- 현재 많은 서비스들이 대용량 데이터를 처리하는 기술을 활용하고 있습니다. 이러한 트렌드를 반영하여, Spring Batch를 이용하여 KOPIS의 공공데이터를 주기적으로 크롤링하고 DB를 업데이트 하는 시스템을 구축했습니다.
- 대규모 트래픽이 발생할 경우 부하분산과 성능 향상을 위해서 웹 어플리케이션 서버를 이중화 구축했습니다.


## 기술 스택
![figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
<img src="https://img.shields.io/badge/react-20232A?style=for-the-badge&logo=react&logoColor=white"/>
<img src="https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
![db](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![monitor](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white)
![pro](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white)
![env](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)



## 구현 기능
- 로그인 ( 관리자, 회원 ) 페이지 - JWT 토큰기반 로그인, Oauth 로그인 구현
- 회원가입 페이지 - 중복처리, SMS인증 구현
- 마이 페이지- 회원정보[조회,수정,삭제], 구매 목록 조회, 장바구니 목록 조회
- 메인 페이지- 공연 검색,  평점 높은 순 공연 & MD’s Pick 공연 목록 조회
- 공연 카테고리별 페이지- 공연검색, 장르&지역별 공연 목록 조회
- 검색 페이지- 공연 제목에 검색어를 포함하고 있는 공연 조회
- 공연 상세 정보 페이지- 공연 상세정보 조회, 공연 위치 (카카오 맵 API), 댓글 조회, 댓글 작성,  예약할 날짜&좌석 선택, 결제(포트원 API)
- 관리자 페이지- 회원정보[생성,조회,수정,삭제], 공연정보[생성,조회,수정,삭제], MD’s Pick 공연 선택, 결제및 환불관리


## 시스템 구성도
<p align="left">
  <img src="https://github.com/SKUWooU/.github/assets/126756270/1befaa8e-f148-45cf-98be-0efa0349b9f2" width="400" height="360">
</p>


## 시연영상
- [노션링크](https://www.notion.so/b3497643018747a9b9c5a55d181f1469?pvs=4)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
