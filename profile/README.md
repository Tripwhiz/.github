## *TRIPWHIZ* ✈️
> ### 여행용품 현지 픽업 온라인 편의점  
> **국내**에서 원하는 상품을 **구매 및 결제**한 뒤, **해외 현지의 편의점**에서 간편하게 **픽업**할 수 있는 서비스  
> \# 국내 결제 후 현지 픽업 &nbsp; \# 수화물 보관 및 이동 &nbsp; \# 챗봇

### ✅ 프로젝트기간: 24.10.15 ~ 24.12.24 (10주)

<details> 
    <summary>&nbsp;&nbsp;Server Repository</summary>  

🔗 [Admin](https://github.com/Tripwhiz/TripwhizAdminServer)
&nbsp;&nbsp;🔗 [User](https://github.com/Tripwhiz/TripwhizServer)

</details>

<details>
    <summary>&nbsp;&nbsp;Client Repository</summary>  

🔗 [Admin](https://github.com/Tripwhiz/TripwhizAdminClient)
&nbsp;&nbsp;🔗 [User](https://github.com/Tripwhiz/TripwhizClient)

</details>

---

### 1️⃣ *TEAM*
| Image                             |  Name   |     Role     |          Implemented Features           |                      GitHub                       |
|:----------------------------------|:-------:|:------------:|:---------------------------------------:|:-------------------------------------------------:|
| ![Juhui](../images/juhui.png)     |   박주희   | Team Leader  | 사용자/관리자 기능 총괄, 상품-주문, CI/CD, 관리자 화면 개발  |   [GitHub Profile](https://github.com/eggzuxi)    |
| ![Minju](../images/minju.png)     |   차민주   |  Full Stack  |      수화물 기능, 지도 API 연동, 데이터베이스 설계       | [GitHub Profile](https://github.com/backgoon0903) |
| ![Sinyong](../images/sinyong.png) |   박신영   |  Full Stack  |     게시판, 카테고리, 소셜로그인, 상태관리, 웹 퍼블리싱      |   [GitHub Profile](https://github.com/ssinyong)   |
| ![Sungoh](../images/sungoh.png)   |   진성오   |  Full Stack  |   이미지, 다국어지원, QR코드, 챗봇, 알림 기능, AWS 배포   | [GitHub Profile](https://github.com/jin-sung-oh)  |
| ![Seola](../images/seola.png)     |   최설아   |  Full Stack  |       UI/UX 디자인, 결제 시스템 연동, 재고 기능       |  [GitHub Profile](https://github.com/Seola-CHOE)  |

---

### 2️⃣ *TECH STACK*

|       **Languages**       ||
|:---------------------------:|:---------------------------------------:|
| ![Java](../images/Java.png) | ![Typescript](../images/TypeScript.png) |
|            Java             |               Typescript                |

|             **Framework**             |                               |
|:---------------------------------------:|:-----------------------------:|
| ![SpringBoot](../images/SpringBoot.png) | ![React](../images/React.png) |
|               SpringBoot                |             React             |

|          **Database**           |
|:---------------------------------:|
| ![MariaDB](../images/MariaDB.png) |
|              MariaDB              |

|   **Authentication**    |
|:-------------------------:|
| ![Jwt](../images/Jwt.png) |
|      Json Web Token       |

|        **Cloud Platform**         |
|:-----------------------------------:|
| ![Firebase](../images/Firebase.png) |
|                 FCM                 |

| **APIs & External Services** |                                       |                               |                               |                                               |
|:------------------------------:|:-------------------------------------:|:-----------------------------:|:-----------------------------:|:---------------------------------------------:|
|  ![Toss](../images/Toss.png)   | ![Langchain](../images/Langchain.png) | ![Zxing](../images/Zxing.png) | ![Jsoup](../images/Jsoup.png) | ![Google Cloud](../images/Google%20Cloud.png) |
|         Toss Payments          |              Lang chain               |             Zxing             |             Jsoup             |                  Google Maps                  |

|         **Network**         |                                   |
|:-----------------------------:|:---------------------------------:|
| ![Axios](../images/Azios.png) | ![Postman](../images/Postman.png) |
|             Axios             |              Postman              |

|                   **Deploy**                   |                                 |                           |                               |
|:-------------------------------------------------:|:-------------------------------:|:-------------------------:|:-----------------------------:|
| ![Github Actions](../images/GitHub%20Actions.png) | ![Docker](../images/Docker.png) | ![AWS](../images/AWS.png) | ![Nginx](../images/Nginx.png) |
|                  Github Actions                   |             Docker              |            AWS            |             Nginx             |

|        **Tools & Collaborations**        |                                 |                               |                             |                                 |                               |
|:------------------------------------------:|:-------------------------------:|:-----------------------------:|:---------------------------:|:-------------------------------:|:-----------------------------:|
| ![IntelliJ](../images/IntelliJ%20IDEA.png) | ![Github](../images/GitHub.png) | ![Figma](../images/Figma.png) | ![Jira](../images/Jira.png) | ![Notion](../images/Notion.png) | ![Slack](../images/Slack.png) |
|                  IntelliJ                  |             Github              |             Figma             |            Jira             |             Notion              |             Slack             |

---

### 3️⃣ *FEATURE*
- #### 국내 결제 후 해외 픽업
  **소셜로그인**한 사용자가 **카테고리 필터링** 또는 **키워드 검색**으로 원하는 상품을 담은 후 **토스페이**를 이용해
  결제하면 **QR코드**가 발급되도록 구현

- #### 수화물 보관 및 이동
  **Crawling**을 통해 **Google 지도**에 해외 편의점 지점을 표시, 사용자가 수화물 보관 신청을 완료하면 점주
  화면에 **FCM 알림** 구현

- #### 챗봇
  **Ollama**의 로컬환경에서 **LLM**을 학습시키고 **RAG기법**으로 정확한 답변을 하도록 구현

---

### 4️⃣ *Documents*
>[🔗 요구사항분석서](https://docs.google.com/spreadsheets/d/1ftDs0ndnl6fSZX--J9W0pJPFOnCpScSF/edit?usp=sharing&ouid=107081426996564712412&rtpof=true&sd=true)  
[🔗 시스템아키텍처](https://drive.google.com/file/d/1SyPPtqG4cjZyWcNDGwtHsM9rfOxLB8jr/view?usp=sharing)
