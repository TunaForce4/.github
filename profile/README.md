

### TunaHub - 물류 관리 및 배송 시스템

<div align="center">
  <h1>TunaHub - 물류 관리 및 배송 시스템</h1>
  <p>🚚 MSA 기반 B2B 물류 관리 및 배송 시스템 🚚</p>
</div>

<img width="1792" height="1024" alt="image" src="https://github.com/user-attachments/assets/9c2467cc-1df1-4ace-8a85-576941fe3b21" />


<br/>

<div align="center">
  <a href="">홈페이지</a>
  &nbsp; | &nbsp;
  <!-- <a href="">Swagger</a>
   &nbsp; | &nbsp; -->
  <a href="https://www.notion.so/teamsparta/2402dc3ef5148024a920c918967274c7?source=copy_link">Notion</a>
</div>

---


(** 다양한 이미지, gif, github에서 제공해 주는 태그 등을 활용-삭제예정)



## 0. 목차

1. [프로젝트 소개](#1)
2. [팀원 소개](#2)
3. [개발 일정](#3)
4. [기술 스택](#4)
5. [라이브러리 사용 이유](#5)
6. [컨벤션](#6)
7. [브랜치 및 디렉토리 구조](#7)
8. [인프라 구조도] ()
9. [erd]
10. [주요 기능 소개](#8)
11. [상세 담당 업무](#9)
12. [주요 코드 ](#10)
13. [트러블 슈팅](#11)
14. [프로젝트 회고](#12)
15. [시작 가이드](#13)

<br />

## <span id="1">🚩 1. 프로젝트 소개</span>

Notion: [프로젝트 노션 링크](https://www.notion.so/teamsparta/2402dc3ef5148024a920c918967274c7?source=copy_link)

프로젝트에 대한 전반적인 소개를 여기에 적어주세요.

<br>

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

## <span id="2">🏃 2. 팀원 소개</span>

<div align="center">

| <img src="https://img.shields.io/badge/Project_Leader-FF5733" /> | <img src="https://img.shields.io/badge/Documentation_Leader-%2310069F%20" /> |    |    |    |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: |  :--------------------------------------------------------------: |:--------------------------------------------------------------------------: | :-----------------------------------------------------------: |
|      <img src="https://github.com/" width="120px;" alt=""/>      |      <img src="https://github.com/" width="120px;" alt=""/>      |      <img src="https://github.com/" width="120px;" alt=""/>      |            <img src="https://github.com/" width="120px;" alt=""/>            |    <img src="https://github.com/" width="120px;" alt=""/>     |
|           [이다예](https://github.com/dayaelee)           |           [최우탁](https://github.com/legoChoi)           |                 [정성운](https://github.com/Hoody-rj)                 |                 [황선영](https://github.com/dinahland)                 |         [이강혁](https://github.com/GangHyeokLee)          |
|                             배송 도메인                             |                              상품 / 주문 도메인                             |                            슬랙 알림 / 업체 배송 관리                             |                                  허브 관리                                   |                          Gateway / 유저 / 업체                           |

</div>

<br>

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

## <span id="3">📅 3. 개발 일정</span>

> 프로젝트 개발 기간: 2025.08.11 - 2025.08.23 (13일)

<br>

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

## <span id="4">📚 4. 기술 스택</span>

### Environment

![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)



### Development

![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
<br>![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)


### Design

![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

### Communication

![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)

<br>

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

## <span id="5">❓ 5. 라이브러리 사용 이유</span>

각 라이브러리의 사용 이유를 설명해주세요.

> React

<br>

> Redux

<br>

> Axios


<br>

> Querydsl
- JPQL의 컴파일 시점 오류 확인 불가
- 쿼리 가독성과 타입 안정성을 보장하여 유지보수 용이

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

## <span id="6">🤝 6. 컨벤션</span>

### prettier

```json
{
  "printWidth": 80,
  "tabWidth": 2,
  "singleQuote": true,
  "trailingComma": "all",
  "semi": false
}
```

### 커밋 컨벤션

| **타입** | **설명**                                          | **예시**                                              |
| -------- | ------------------------------------------------- | ----------------------------------------------------- |
| feat     | 기능 구현                                         | [feat] - 페인페이지 레이아웃 구현                     |
| rename   | 파일/폴더 이름 변경 및 이동                       | [rename] - `src/old-folder`를 `src/new-folder`로 이동 |
| script   | 라이브러리 추가                                   | [script] - `supabase` 라이브러리 추가                 |
| fix      | 버그 수정                                         | [fix] - `supabase` env 미연결 문제 해결               |
| chore    | 빌드 업무 수정, 패키지 매니저 설정 수정           | [chore] - .env 설정 변경                              |
| refactor | 코드 리팩토링                                     | [refactor] - 함수 분리 및 코드 정리                   |
| style    | 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우 | [style] - 버튼 스타일 수정                            |
| test     | 테스트 코드, 리팩토링 테스트 코드 추가            | [test] - 유저 로그인 기능 테스트 추가                 |
| docs     | 문서 수정                                         | [docs] - API 문서 업데이트                            |

<br>

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

## 7.<span id="7"> 🗂️ 브랜치 및 디렉토리 구조</span>

> 브랜치

- `main`:
- `dev`:
-

<br>

(** 모든인원 작성 - 토글 안에 디렉토리구조 작성 부탁드립니다)

> 디렉토리 구조

```
📂 App
├── 📂 src
│   ├── 📂 components      # 컴포넌트 관련 파일
│   ├── 📂 pages           # 페이지 파일
│   ├── 📂 redux           # Redux 상태 관리 파일
│   ├── 📂 utils           # 유틸리티 파일
│   └── 📄 App.js          # 메인 App 컴포넌트
├── 📂 public
│   ├── 📄 index.html      # HTML 엔트리 파일
│   └── 📄 favicon.ico     # 사이트 아이콘
└── 📄 package.json        # 프로젝트 종속성 및 설정 파일

```


> 배송 도메인 디렉토리 구조

```
📂 App
├── 📂 src
│   ├── 📂 components      # 컴포넌트 관련 파일
│   ├── 📂 pages           # 페이지 파일
│   ├── 📂 redux           # Redux 상태 관리 파일
│   ├── 📂 utils           # 유틸리티 파일
│   └── 📄 App.js          # 메인 App 컴포넌트
├── 📂 public
│   ├── 📄 index.html      # HTML 엔트리 파일
│   └── 📄 favicon.ico     # 사이트 아이콘
└── 📄 package.json        # 프로젝트 종속성 및 설정 파일

```



> 배송 도메인 디렉토리 구조

<details>
<summary>Order</summary>

<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FoNJ0s%2FbtsP0kVtl0e%2FAAAAAAAAAAAAAAAAAAAAADM3LCZeBIdOc5jyhbO8V6yYYZd-1D2YjPrSTM_QLyl_%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DyXgSlq6KJHf4wJ9asK8sHiN33ck%253D" width="300" height="500" />

</details>

<details>
<summary>Product</summary>

<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2Fbt3DBS%2FbtsPYNYDHku%2FAAAAAAAAAAAAAAAAAAAAAME3BC2QgCGwb4NFkaS2lKaoVr_Dktz8DoaAWSidXjqG%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DYZZyl%252FtdBHZ7T%252FRXNeWgIFzOqUk%253D" width="300" height="500" />

</details>

<br>

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

## <span id="8">8. 💻 인프라 구조도</span>
![인프라 설계 (1)](https://github.com/user-attachments/assets/38608894-f9ec-45b5-bdd1-d9123bdebf57)


<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>


## <span id="9">9. 💻 ERD 설계</span>

<img width="3080" height="2522" alt="MSA-DeliverySystem" src="https://github.com/user-attachments/assets/49ce7366-15aa-4df1-8baf-9a269dc86d7e" />

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>



## <span id="10">10. 💻 주요 기능 소개</span>

프로젝트의 주요 기능을 GIF를 첨부하여 설명해주세요.

### 1) 상품 




| 기능                      | 메서드    | 엔드포인트                           | Query Params                  | status |
|-------------------------|--------|---------------------------------|-------------------------------|--------|
| 상품 생성                   | POST   | /products                       |                               | 201    |
| 상품 단건 조회                | GET    | /products/{productId}           |                               | 200    |
| 상품 전체 목록 조회 (페이지네이션)    | GET    | /products                       | page, size, sort, productName | 200    |
| 허브 등록 상품 목록 조회 (페이지네이션) | GET    | /products/hubs/{hubId}          | page, size, sort, productName | 200    |
| 업체 등록 상품 목록 조회 (페이지네이션) | GET    | /products/companies/{companyId} | page, size, sort, productName | 200    |
| 상품 수정                   | PATCH  | /products                       |                               | 204    |
| 상품 삭제                   | DELETE | /products                       |                               | 200    |

### 2) 주문

| 상세페이지 화면                                   | 게시물 작성 - ??                                  | 게시물 작성 - ??                                  |
| ------------------------------------------------- | ------------------------------------------------- | ------------------------------------------------- |
| <img src="" alt="-화면" width="288" height="608"> | <img src="" alt="-화면" width="288" height="608"> | <img src="" alt="-화면" width="288" height="608"> |

### 3) 404 & 로딩 화면

| - 화면                                            | - 화면                                            | - 화면                                            |
| ------------------------------------------------- | ------------------------------------------------- | ------------------------------------------------- |
| <img src="" alt="-화면" width="288" height="608"> | <img src="" alt="-화면" width="288" height="608"> | <img src="" alt="-화면" width="288" height="608"> |

<br>

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

## <span id="11">11. 📄 상세 담당 업무</span>

### 1) 이강혁

- **🎨 사용자 관리**

  - 로고 디자인 및 이미지 제작

- **💻 Gateway**

  - 로그인 화면
  - 검색 화면
  - 채팅 화면

- **🧑‍💻 업체 관리**

  - 로딩 페이지
    - 회원가입 후 로그인 모달이 올라오는 로딩페이지
  - 팔로워 목록 및 팔로워 취소&팔로우
    - 팔로워 목록을 getFollowerList로 서버에 요청하여 리스트 출력

- **♻️ 리팩토링**
  - 관련 설명

### 2) 최우탁

- **🎨 상품 관리(Order)**


  - 유저 권한별 각 기능 유효성 검증
    <details>
        <summary>
            주문 생성
        </summary>

  ![주문_생성](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FbkOHf3%2FbtsP418xBfU%2FAAAAAAAAAAAAAAAAAAAAANTAYV6Flmf0aYQFKiT4bxZ1rYOAtrKdJiaVmSiT-Djf%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DHfO4qIDI98YUiZOjXkxT9a%252FovSc%253D)

    </details>
    <details>
        <summary>
            주문 단건 조회
        </summary>

  ![주문_단건_조회](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FcENDh5%2FbtsP0TdqBr5%2FAAAAAAAAAAAAAAAAAAAAANf3fNevha4wHkfxJJ67djEjfy5lv1rKUe3KXfPKcgpX%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3D3U%252FQRnYrfBsrAEKrd0mYSjTZ5bU%253D)

    </details>
    <details>
        <summary>
            허브 주문 목록 조회
        </summary>

  ![허브_주문_목록_조회](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2Fb4gF5b%2FbtsP4e1BM6F%2FAAAAAAAAAAAAAAAAAAAAAK6eFEKK3E7u75yOHEyw7wyeLkgoXhoURZRjijhMSXAu%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DiF7Tes%252FSHgq6KK4yk8skVfxcetU%253D)

    </details>
    <details>
        <summary>
            업체 주문 목록 조회
        </summary>

  ![업체_주문_목록_조회](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FcBTWKX%2FbtsP4qnocyX%2FAAAAAAAAAAAAAAAAAAAAAB0R89YUWV3XmIA38WrNvcG-_dHulc9O1Eb-FpLAxjyY%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DGajD4ta0IdFS47DK2W%252BrkfmgUK4%253D)

    </details>
    <details>
        <summary>
            주문 수정
        </summary>

  ![주문_수정](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FxCLnK%2FbtsP4624ifa%2FAAAAAAAAAAAAAAAAAAAAADOQQIn41TP2pwZ0BqZHCZWjLL1KsOUAGAr106eHNrTi%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DmT3cGgJRQjY1AKMHSh2Xe6G8poI%253D)

    </details>
    <details>
        <summary>
            주문 삭제
        </summary>

  ![주문_삭제](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2Fb11bVy%2FbtsP4iQtGIB%2FAAAAAAAAAAAAAAAAAAAAAI8faBKIc_q6REmCQGIDYSxiT_pvo8IPVVOMuqHk75wi%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DF%252FQTJXHI3PKAvxOUBfWsQ8drl0A%253D)

    </details>

  
  - 전체적인 UI 디자인


<br>

- **💻 상품 관리(Product)**

  - 유저 권한별 각 기능 유효성 검증
    <details>
        <summary>
            상품 생성
        </summary>

  ![상품_생성](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FbkOHf3%2FbtsP418xBfU%2FAAAAAAAAAAAAAAAAAAAAANTAYV6Flmf0aYQFKiT4bxZ1rYOAtrKdJiaVmSiT-Djf%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DHfO4qIDI98YUiZOjXkxT9a%252FovSc%253D)

    </details>
    <details>
        <summary>
            상품 단건 조회
        </summary>

  ![상품_단건_조회](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FcENDh5%2FbtsP0TdqBr5%2FAAAAAAAAAAAAAAAAAAAAANf3fNevha4wHkfxJJ67djEjfy5lv1rKUe3KXfPKcgpX%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3D3U%252FQRnYrfBsrAEKrd0mYSjTZ5bU%253D)

    </details>
    <details>
        <summary>
            허브 등록 상품 목록 조회
        </summary>

  ![허브_등록_상품_목록_조회](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2Fb4gF5b%2FbtsP4e1BM6F%2FAAAAAAAAAAAAAAAAAAAAAK6eFEKK3E7u75yOHEyw7wyeLkgoXhoURZRjijhMSXAu%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DiF7Tes%252FSHgq6KK4yk8skVfxcetU%253D)

    </details>
    <details>
        <summary>
            업체 등록 상품 목록 조회
        </summary>

  ![업체_등록_상품_목록_조회](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FcBTWKX%2FbtsP4qnocyX%2FAAAAAAAAAAAAAAAAAAAAAB0R89YUWV3XmIA38WrNvcG-_dHulc9O1Eb-FpLAxjyY%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DGajD4ta0IdFS47DK2W%252BrkfmgUK4%253D)

    </details>
    <details>
        <summary>
            상품 수정
        </summary>

  ![상품_수정](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FxCLnK%2FbtsP4624ifa%2FAAAAAAAAAAAAAAAAAAAAADOQQIn41TP2pwZ0BqZHCZWjLL1KsOUAGAr106eHNrTi%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DmT3cGgJRQjY1AKMHSh2Xe6G8poI%253D)

    </details>
    <details>
        <summary>
            상품 삭제
        </summary>

  ![상품_삭제](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2Fb11bVy%2FbtsP4iQtGIB%2FAAAAAAAAAAAAAAAAAAAAAI8faBKIc_q6REmCQGIDYSxiT_pvo8IPVVOMuqHk75wi%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DF%252FQTJXHI3PKAvxOUBfWsQ8drl0A%253D)

    </details>

<br>

- **💻 공통(Common)**

- DTO의 `record` 타입 사용
    - 클라이언트의 요청에 대한 불변성과 안정성을 명시


- `Pageable`의 `sort` 쿼리 - 정렬 조건 타입 안정화
    - 정해진 정렬 조건만 허용 - 예기치 못한 쿼리 또는 에러 발생 방지
    - 동일한 `property` 정렬 시 예외 발생
    - `SortType` ENUM
      ```
      @Getter
      @RequiredArgsConstructor
      public enum SortType {
      
          CREATED_ASC("createdAt", Sort.Direction.ASC),
          CREATED_DESC("createdAt", Sort.Direction.DESC),
          UPDATED_ASC("updatedAt", Sort.Direction.ASC),
          UPDATED_DESC("updatedAt", Sort.Direction.DESC),
          PRICE_ASC("price", Sort.Direction.ASC),
          PRICE_DESC("price", Sort.Direction.DESC),
          ;
      
          private final String value;
          private final Sort.Direction direction;
      
          public static void validate(Sort sort) {
              Set<String> check = new HashSet<>();

              for (Sort.Order order : sort) {
                  if (!match(order)) {
                      throw new CustomRuntimeException(ProductException.UNSUPPORTED_SORT_TYPE);
                  }

                  if (!check.add(order.getProperty().toLowerCase())) {
                      throw new CustomRuntimeException(ProductException.DUPLICATED_SORT_TYPE);
                  }
              }
          }
      
          private static boolean match(Sort.Order order) {
              return Arrays.stream(SortType.values())
                      .anyMatch(sortType -> sortType.value.equalsIgnoreCase(order.getProperty()) &&
                         sortType.getDirection().equals(order.getDirection()));
          }
      }
      ```

- `Querydsl`의 `getOrderSpecifier()`을 통한 동적 정렬 조건 쿼리 구현
    - 클라이언트가 여러 개의 `sort` 쿼리를 넘기도록 하여 `.orderBy()`에 적용
      ```
      private OrderSpecifier<?>[] getOrderSpecifiers(Sort sort) {
        List<OrderSpecifier<?>> orderSpecifiers = new ArrayList<>();
    
        for (Sort.Order sortOrder : sort) {
            Order order = sortOrder.isAscending() ? Order.ASC : Order.DESC; // sort 쿼리 내 정렬 방향을 Order 객체로 파싱 
            PathBuilder<Product> pathBuilder
                    = new PathBuilder<>(product.getType(), product.getMetadata()); // sort 쿼리 내 정렬 값을 QClass 내 필드값에 해당하는 값으로 매핑  
    
            orderSpecifiers.add(new OrderSpecifier<>(order, pathBuilder.getString(sortOrder.getProperty())));
        }
    
        return orderSpecifiers.toArray(new OrderSpecifier[0]);
      }
      ```


<!-- - **♻️ 리팩토링**
  - 관련 설명 -->

### 3) 황선영

- **🎨 상품 관리**

  - 전체적인 UI 디자인

- **💻 주문 관리**

  - 공통 헤더 네브바
  - 공통 푸터 네브바
  - 삭제 / 신고 모달창

- **👩‍💻 구현 기능**

  - 라우터 초기 셋팅
  - 게시물 등록
    - 토글 Open, Close에 따라 인풋창 높이 자동 조절
    - api 전송 한계로 인해 한 공간에 저장하여 보낼 수 있게, 데이터를 연산자로 구분하여 한줄로 전송
      이미지 추가 및 삭제 가능
  - 게시글 삭제 / 신고
    - userId를 통해 유저를 구별하여 타인의 경우 신고 기능, 본인일 경우 삭제 기능 구현

- **♻️ 리팩토링**
  - 관련 설명

### 4) 이다예

- **🎨 상품 관리**

  - 전체적인 UI 디자인

- **💻 주문 관리**

  - 공통 헤더 네브바
  - 공통 푸터 네브바
  - 삭제 / 신고 모달창

- **👩‍💻 구현 기능**

  - 라우터 초기 셋팅
  - 게시물 등록
    - 토글 Open, Close에 따라 인풋창 높이 자동 조절
    - api 전송 한계로 인해 한 공간에 저장하여 보낼 수 있게, 데이터를 연산자로 구분하여 한줄로 전송
      이미지 추가 및 삭제 가능
  - 게시글 삭제 / 신고
    - userId를 통해 유저를 구별하여 타인의 경우 신고 기능, 본인일 경우 삭제 기능 구현

- **♻️ 리팩토링**
  - 관련 설명

### 5) 정성운

- **🎨 상품 관리**

  - 전체적인 UI 디자인

- **💻 주문 관리**

  - 공통 헤더 네브바
  - 공통 푸터 네브바
  - 삭제 / 신고 모달창

- **👩‍💻 구현 기능**

  - 라우터 초기 셋팅
  - 게시물 등록
    - 토글 Open, Close에 따라 인풋창 높이 자동 조절
    - api 전송 한계로 인해 한 공간에 저장하여 보낼 수 있게, 데이터를 연산자로 구분하여 한줄로 전송
      이미지 추가 및 삭제 가능
  - 게시글 삭제 / 신고
    - userId를 통해 유저를 구별하여 타인의 경우 신고 기능, 본인일 경우 삭제 기능 구현

- **♻️ 리팩토링**
  - 관련 설명



<br>

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

## <span id="12">✨ 12. 주요 코드</span>

<details>
<summary> 주요 코드에 대한 설명을 입력하세요. </summary>

<div>
설명

```jsx

```

</div>
</details>

<br>

<details>
<summary> 주요 코드에 대한 설명을 입력하세요. </summary>

<div>
설명

```jsx

```

</div>
</details>

<br>

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

## <span id="13">🚦 13. 트러블 슈팅</span>

<details>
<summary> OpenFeign Invalid HTTP method: PATCH </summary>

<div>

1. 문제 상황 <br />
   ![openfeign_trouble_1](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FsenN2%2FbtsP228uae0%2FAAAAAAAAAAAAAAAAAAAAAFPM1kh3cVJlaIyepRMGq-26xrPuLBlypU56BVkH8Kex%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3D1Adhf2iRqBIxWFno4%252BOSC6ThSec%253D)
   ![openfeign_trouble_2](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdna%2FcsXI7X%2FbtsP11WPACl%2FAAAAAAAAAAAAAAAAAAAAAFnLL7tOaohP5ePtMOrW6aTPrfonpf0_FuxwVNiufRCa%2Fimg.png%3Fcredential%3DyqXZFxpELC7KVnFOS48ylbz2pIh7yKj8%26expires%3D1756652399%26allow_ip%3D%26allow_referer%3D%26signature%3DkUVqHuGmZoJ2BENQnpyiIkVzt9Y%253D)

- `Order`서비스에서 `Product`서비스로 주문 상품 수량 수정이나 주문 취소시 차감했던 상품의 재고를 다시 변경하기 위해 `PATCH` 메소드 사용
- `OpenFeign`은 HTTP 요청을 추상화하여 메소드 호출로 REST API 호출 가능하도록 지원해주는데 HTTP 기본 구현체가 추가 의존성 없이 작동하도록 설계됨
- `HttpURLConnection`은 별도 라이브러리 의존 없이 사용 가능하므로 `OpenFeign`에서 사용
- `PATCH`는 비교적 최신 기능이라 `HttpURLConnection`에서 지원이 안되는 것

2. 해결방안 <br />

- 외부 HTTP 클라이언트 라이브러리를 사용하여 해결(커스텀)
    - ApachHttpClient, OkHttpClient
- 하지만 각 서비스 간 내부 통신이므로 Restful 규약을 준수할 필요는 없다고 생각함

3. 최종 결정

- `PATCH` -> `POST` 변경

</div>
</details>

<details>
<summary> 트러블 슈팅을 입력하세요. </summary>

<div>

1. 문제 상황 <br />

2. 시도 <br />

3. 해결방안 <br />

</div>
</details>

<details>
<summary> 트러블 슈팅을 입력하세요. </summary>

<div>

1. 문제 상황 <br />

2. 시도 <br />

3. 해결방안 <br />

</div>
</details>

<details>
<summary> 트러블 슈팅을 입력하세요. </summary>

<div>

1. 문제 상황 <br />

2. 시도 <br />

3. 해결방안 <br />

</div>
</details>

<br>

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

## <span id="14">14. 📝 프로젝트 회고</span>

### 최우탁

- 권한별 기능 설계 및 구현에 시간을 너무 사용하여 `OpenFeign` 통신 장애 대응 로직을 충분히 구현하지 못해 아쉽다.
- 각 기능의 최적화나 고도화를 진행하지 못한 점도 개선할 필요가 있다.
- 다음 프로젝트에서는 설계 단계에서 서비스의 전체적인 도메인에 대한 이해를 충분한 회의나 지식 공유등을 통해 정리하고 가는 것이 좋을 것 같다.




<br>

<!-- Top Button -->
<p style='background: black; width: 32px; height: 32px; border-radius: 50%; display: flex; justify-content: center; align-items: center; margin-left: auto;'><a href="#top" style='color: white; '>▲</a></p>

<br>

<!-- ## <span id="15">15. 🛠️ 시작 가이드</span>

### Installation

```shell
# 1. 클론하기
$ git clone https://github.com/CAREER-For-Me/Career-web.git .

# 2. 의존성 설치하기
$ yarn

# 3. 개발 서버 실행하기
$ yarn dev
```

<br> -->



참고링크(추후 삭제 예정)
https://mynamesieun.github.io/git/GitHub-README.md-%EC%9E%91%EC%84%B1-%EA%B0%80%EC%9D%B4%EB%93%9C/
