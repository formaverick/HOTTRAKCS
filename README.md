# 🛍️ HOTTRACKS – 문구/라이프스타일 쇼핑몰 UI 데모

> 문구·리빙 쇼핑몰(핫트랙스 스타일) 랜딩/서브 페이지 데모 프로젝트입니다.  
> 정적 JSON을 jQuery로 비동기 로드하여 **배너**, **추천**, **랭킹**, **기획전** 등 주요 섹션을 **동적으로 구성**합니다.

---

<div align="center">
  <img width="45%" src="https://github.com/user-attachments/assets/313821f3-bcf8-4500-b5c7-8cfc20b00335" alt="hottracks preview" />
</div>

---

## 🖥️ 데모 페이지

🔗 **배포 링크:** [https://formaverick.github.io/HOTTRAKCS/](https://formaverick.github.io/HOTTRAKCS/)

- 🏠 **메인 페이지:** `index.html`  
- 📖 **서브 페이지:** `sub.html`

---

## 🛠️ 기술 스택

<div>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"/>
  <img src="https://img.shields.io/badge/jQuery.countdown-000000?style=for-the-badge&logo=jQuery&logoColor=white"/>
  <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white"/>
</div>

<br>

<div align="center">

| 구분         | 기술 구성                                                    |
| ------------ | ------------------------------------------------------------ |
| **Frontend** | HTML5, CSS3, jQuery 3.6.4 (CDN)                              |
| **Library**  | jQuery.countdown 2.2.0 (CDN)                                 |
| **Data**     | 정적 JSON 데이터(`json/*.json`), 이미지/아이콘(`img/*`)     |

</div>

---

## ✨ 주요 기능

### 🎠 메인 슬라이더  
- 자동 순환, 이전/다음 버튼, 중앙 포커스(주변 블러 효과)

### 💡 오늘의 추천  
- JSON 데이터 바인딩  
- 버튼 클릭 시 데이터 세트 교체로 섹션 갱신

### 🏆 랭킹 탭  
- 카테고리 클릭 시 JSON 소스 교체  
- 동일한 레이아웃 재사용으로 효율적 데이터 갱신

### 🗂️ 카테고리 내비게이션  
- Hover/slide 토글 기반의 2~3단 드롭다운 메뉴

### ⏰ 카운트다운 위젯  
- 타임딜/특가 영역 자동 갱신  
- jQuery.countdown 플러그인 사용

### 🖼️ 배너 / 기획전  
- 이미지 배너, 전시 섹션을 동적 JSON 데이터로 구성

---

## 📂 폴더 구조(요약)

```plaintext
HOTTRAKCS/
│
├── index.html                # 메인 페이지
├── sub.html                  # 서브 페이지
│
├── css/                      # 레이아웃 및 섹션 스타일
│   ├── common.css
│   ├── main.css
│   ├── sub.css
│   └── ...
│
├── js/                       # 기능 단위 스크립트
│   ├── mainSlider.js
│   ├── todayPick.js
│   ├── ranking.js
│   ├── categoryNav.js
│   ├── countdown.js
│   ├── bannerLoader.js
│   └── ...
│
├── json/                     # 정적 데이터
│   ├── today.json
│   ├── ranking.json
│   ├── banner.json
│   └── ...
│
└── img/                      # 이미지 및 아이콘 리소스
    ├── banner/
    ├── product/
    ├── icon/
    ├── event/
    └── ...
```

---

## 💡 프로젝트 인사이트

* **데이터 / 프레젠테이션 분리**
  JSON 교체만으로 다양한 상태를 손쉽게 시뮬레이션 가능

* **jQuery 기반의 빠른 프로토타이핑**
  중복 로직(특히 랭킹/추천 섹션)은 공통화 필요

* **접근성 / SEO 개선 여지**
  버튼/링크 역할 명확화, 대체 텍스트, 시맨틱 태그, 키보드 접근성 보강

* **반응형 전환 권장**
  고정폭 → 미디어쿼리 + 유연한 그리드 시스템 적용

* **리소스 최적화 필요**
  이미지 지연 로딩(Lazy Loading), 포맷 최적화, 스크립트 번들링/압축, 캐시 정책 적용

---

## 📝 기타

* 본 프로젝트는 **UI 프로토타입 데모용**으로 제작되었습니다.
* 상업적 사용이 아닌 **학습·포트폴리오 목적**으로만 사용됩니다.
* 문의 및 피드백은 **Issue 또는 PR**로 제안해주세요.
