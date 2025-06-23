<div align="center">

# 🌀 The Nation of Smoke  
**청소년 전자담배 사용 현황 분석 프로젝트**

</div>

---

## 📌 프로젝트 개요

> **"청소년의 전자담배 흡연율 증가"**, 그 현실은 어떤가요?

본 프로젝트는 청소년의 전자담배 흡연 문제를 다룬 언론 보도를 계기로,  
**뉴스 분석**과 **온라인 접근성 조사**를 통해 그 **현실적인 문제점과 규제 필요성**을 데이터 기반으로 조명합니다.

- 📈 **형태소 분석을 통한 기사 내용의 흐름 파악**
- 🛒 **온라인 구매 가능성 실태조사**
- 🔍 **정책적 대안 제안**

🎤 **발표자료 보러가기 →**  
[![Canva](https://img.shields.io/badge/Presentation-Click%20Here-blue?logo=Canva)](https://www.canva.com/design/DAGacERlqqU/VLw600U8s9SdePvBxtOO1g/edit?utm_content=DAGacERlqqU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

---

## 🗂️ 폴더 구조

```
The-Nation-of-Smoke/
├── code/                              # 분석 코드 (.ipynb)
│   ├── 241228_뉴스_스크랩핑_형태소_분석_전자담배.ipynb
│   └── SmokeNation.ipynb
│
├── git/                               # Git 초기화용 디렉토리 (내부 비어 있음)
├── LICENSE                            # 라이선스 파일
└── README.md                          # 프로젝트 소개 문서 (이 파일)
```

---

## 🔎 주요 분석 내용

### 📰 뉴스 기사 분석
- 다양한 언론사의 **전자담배 관련 기사 크롤링**
- `Okt` 형태소 분석기로 **빈도 높은 키워드 추출**
- 워드클라우드 기반 **시각적 흐름 파악**

### 🛒 온라인 구매 접근성
- 쇼핑몰 및 커뮤니티 기반 검색 크롤링
- **나이 인증, 구매 제한, 우회 가능성 여부 분석**
- **실제 구매 가능성**과 규제의 사각지대 조명

---

## 🚫 데이터 제공 관련 안내

> 🗂️ `data/` 폴더는 프로젝트에서 사용되었으나, 외부 공개는 하지 않습니다.  
뉴스 크롤링 및 웹사이트 수집 데이터는 **저작권 및 개인정보 보호** 문제로 제외됩니다.

---

## 🧑‍💻 실행 방법

Jupyter Notebook 환경에서 아래 `.ipynb` 파일을 실행해주세요:

```bash
code/
├── 241228_뉴스_스크랩핑_형태소_분석_전자담배.ipynb
└── SmokeNation.ipynb
```

필요한 주요 패키지:

```bash
pip install pandas requests beautifulsoup4 konlpy wordcloud matplotlib
```

---

## 🛠️ 사용 기술

| 분야              | 라이브러리 및 도구                        |
|-------------------|--------------------------------------------|
| 데이터 수집       | `requests`, `BeautifulSoup`                |
| 형태소 분석       | `konlpy` (`Okt`)                            |
| 시각화            | `matplotlib`, `wordcloud`                  |
| 개발 환경         | `Jupyter Notebook`, `Python 3.x`           |

---

## 📜 라이선스

이 프로젝트는 [MIT License](./LICENSE)를 따릅니다.

---

<div align="center">

Made with ❤️ by  
**The Nation of Smoke Project Team**

</div>
