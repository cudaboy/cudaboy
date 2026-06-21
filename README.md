# 안녕하세요, 전운열입니다

실무 문제를 AI 시스템을 이용하여 해결하는 것을 꿈꾸는 데이터 엔지니어가 되고 싶습니다.

통계학 기반의 분석 역량을 바탕으로, 데이터 파이프라인 구축·품질 점검·시계열 이상 탐지·AI 검색/생성 시스템 설계까지 다루는 엔지니어입니다. 

- 목표: 실무 데이터에서 의미 있는 의사결정을 만들 수 있는 안정적 데이터/AI 시스템을 운영 관점에서 구현
- 성향: 근거 중심 사고, 지표 기반 평가, 반복 가능한 검증 프로세스

---

## 🙋‍♂️ About Me

- 데이터 정확도(재현성, 결측/이상값, 지표 추적)를 최우선으로 봅니다.
- AI 시스템을 “결과 생성기”가 아닌 “업무 신뢰도를 높이는 도구”로 설계합니다.
- 금융/공공/연구 데이터 특성을 구분하고, 도메인별 제약을 반영해 파이프라인을 설계합니다.

---

## 🧩 Representative Projects

<details>
<summary><strong>1) BioLinker — 의학 논문 RAG 분석 플랫폼</strong> (2025.04 ~ 2025.05, 개인)</summary>

- **프로젝트 이름**: BioLinker — 의학 논문 RAG 분석 플랫폼
- **활동기간**: 2025.04 ~ 2025.05
- **역할**: 기획·설계·구현 (1인)
- **활용 기술 stack**: Python, FastAPI, LangChain, LangGraph, ChromaDB, PostgreSQL, Docker, GitHub
- **활동 내용**: 
  - PubMed 논문 메타데이터/초록 수집 및 정규화하여 PostgreSQL 저장
  - ChromaDB 기반 벡터 검색 인덱스 구축 및 LangGraph 라우팅(질문 의도별 분기)
  - 검색-요약-근거 연결 구조를 구성해 환각 가능성을 낮추고 근거 기반 응답 제공
  - FastAPI 백엔드 API로 서비스화하고 운영 단계에서 재현 가능한 로그 구조 정리
</details>

<details>
<summary><strong>2) KRX 시장경보제도 실효성 분석</strong> (2023.03 ~ 2024.02, 석사논문)</summary>

- **프로젝트 이름**: KRX 시장경보제도 실효성 분석
- **활동기간**: 2023.03 ~ 2024.02
- **역할**: 단독 연구 (데이터 수집, 통계 분석, 논문 작성)
- **활용 기술 stack**: Python (pandas, statsmodels), SQL, 통계모형(Joinpoint/분위수회귀), 시계열 분석
- **활동 내용**:
  - KRX 투자주의종목 18,384건 일별 가격 데이터를 활용해 시장 위험성 정량화
  - NCSKEW, DUVOL 지표로 변동성 변화를 추적하고 구조적 변곡점 탐지
  - Joinpoint + 분위수 회귀 기반 실무형 위험 패턴 해석 보고 체계 정리
</details>

<details>
<summary><strong>3) 공정위 AI·데이터 활용 공모전 (실시간 RAG 성능 개선)</strong> (2026.04 ~ 2026.05, 팀 프로젝트)</summary>

- **프로젝트 이름**: 공정위 AI·데이터 활용 공모전
- **활동기간**: 2026.04 ~ 2026.05
- **역할**: 검색-생성 파이프라인 설계 및 평가 설계 지원
- **활용 기술 stack**: Python, LangChain, ChromaDB, BGE-M3, 평가 지표(Recall@5, MRR, BERTScore, F1)
- **활동 내용**:
  - 의결서 질문 특성에 맞춰 dense/법조항 정확도 강조 sparse/multi-vector 하이브리드 검색 구성
  - RRF 결합 + 재정렬(reranker)로 상위 청크 노이즈를 줄이고 정합성 향상
  - 검색 단계·생성 단계 지표를 분리해 평가 기준에 맞춘 개선 루프 운영
</details>

<details>
<summary><strong>4) AI Analyst App</strong> (2026.03, 부트캠프 프로젝트)</summary>

- **프로젝트 이름**: AI Analyst App
- **활동기간**: 2026.03
- **역할**: FastAPI/Streamlit 기반 아키텍처 구현 및 역할 분리 설계
- **활용 기술 stack**: Python, LangGraph, LangChain, FastAPI, Streamlit, SQLite, Docker, MLflow
- **활동 내용**:
  - CFO/Analyst/Trader/Fund Manager로 역할을 분리한 멀티에이전트 분석 흐름 설계
  - 분석 히스토리 저장 및 리포트 조회 파이프라인 구성
  - Docker Compose 기반 실행/배포 정리로 재현 가능한 데모 구성
</details>

<details>
<summary><strong>5) Honda R&D EMS — 스마트 건물 에너지 모니터링</strong> (2026.05 ~ 진행 중, 팀 프로젝트)</summary>

- **프로젝트 이름**: Honda R&D EMS — 스마트 건물 에너지 모니터링
- **활동기간**: 2026.05 ~ 진행 중
- **역할**: 팀 프로젝트(분석/이상탐지 파트 참여)
- **활용 기술 stack**: Python, PostgreSQL, TimescaleDB, PyTorch, LightGBM, Isolation Forest, LSTM AutoEncoder, MLflow, Docker
- **활동 내용**:
  - 공개 시계열 데이터(81개 계량기, 장기 수집체계)를 기준으로 데이터 품질 점검(gap/coverage) 기준 정비
  - 특성 엔지니어링 및 예측 모델 실험을 통해 이상 신호 탐지 체계 설계
  - 실험 기록을 MLflow로 추적해 모델 성능 비교 및 운영 후보군 확보
</details>

<details>
<summary><strong>6) [R&D 과제] 코호트기반 신경계 질환 환경유해인자 분석 DB 구축</strong> (2024.01 ~ 2025.06, 학내외활동)</summary>

- **프로젝트 이름**: [R&D 과제] 코호트기반 실내외 신경계질환 유발 환경유해인자 DB 구축 및 가이드라인 개발
- **활동기간**: 2024.01 ~ 2025.06
- **역할**: 참여연구자
- **활용 기술 stack**: R, Python, 데이터 전처리, 시계열 분석, 통계 처리, 시각화
- **활동 내용**:
  - 신경계 환자 가구의 실내·실외 노출 데이터(도시/농촌/산업단지) 정제 및 통합
  - 중금속·휘발성 유기화합물 노출 농도와 시간활동양상 연계해 추세 분석
  - 환경유해인자 예측모형 개발을 위한 보조 분석 데이터셋 정리
</details>

<details>
<summary><strong>7) [연구용역] 차량·기계분야 혈액암 관련 현장조사</strong> (2025.02 ~ 2025.05, 학내외활동)</summary>

- **프로젝트 이름**: [연구용역] 차량·기계분야 혈액암 관련 현장조사 연구용역
- **활동기간**: 2025.02 ~ 2025.05
- **역할**: 외부 전문가 인력
- **활용 기술 stack**: R, R Shiny, Google Cloud Platform, Google Sheets, 통계분석
- **활동 내용**:
  - 설문 데이터 수집, 행정자료 병합, 누적노출량 산출 전 과정을 설계·실행
  - R Shiny 기반 설문 인프라를 구축하고 GCP로 배포
  - 벤젠 노출 추정치와 개인 특성 데이터를 통합해 연령/흡연 등 보정 분석 수행
</details>

<details>
<summary><strong>8) [용역과제] 시간에 따른 발암물질 노출 수준 변화 평가(11)</strong> (2024.05 ~ 2024.10, 학내외활동)</summary>

- **프로젝트 이름**: [용역과제] 시간에 따른 발암물질 노출수준 변화 평가(11)
- **활동기간**: 2024.05 ~ 2024.10
- **역할**: 연구보조원
- **활용 기술 stack**: R, Python, 시계열 분석, Joinpoint Regression(연장형 추세 분석)
- **활동 내용**:
  - 2002~2023 작업환경 측정자료를 정리해 발암물질 노출 변화를 분석
  - 카드뮴/니켈/6가크롬/용접흄의 연도별 평균 및 분위수 추세를 예측 모형으로 정량화
  - 도메인 해석에 적합한 지표 정의로 보고서 산출 근거를 정리
</details>

---

## 🎓 대학원 프로젝트 (추가)

<details>
<summary>1) [R&D 과제] 코호트기반 실내외 신경계질환 유발 환경유해인자 DB 구축</summary>

- **프로젝트 이름**: [R&D 과제] 코호트기반 실내외 신경계질환 유발 환경유해인자 DB구축 및 가이드라인 개발
- **활동기간**: 2024.01 ~ 2025.06
- **역할**: 참여연구자
- **활용 기술 stack**: R, Python, 데이터 전처리, 시계열 분석
- **활동 내용**: 환경유해인자 노출과 시간활동양상을 통합 분석해, 신경계 질환 환자 가구의 시계열 환경 노출 특성을 정리한 보조 DB 구축 및 분석 수행
</details>

<details>
<summary>2) [연구용역] 차량·기계분야 혈액암 관련 현장조사</summary>

- **프로젝트 이름**: [연구용역] 차량·기계분야 혈액암 관련 현장조사 연구용역
- **활동기간**: 2025.02 ~ 2025.05
- **역할**: 외부 전문가 인력
- **활용 기술 stack**: R, R Shiny, Google Cloud Platform, Google Sheets, 통계 분석
- **활동 내용**: 서울교통공사 차량·기계분야 근무자 대상 설문 기반 데이터 수집-정제-분석을 수행하고, 연도별 벤젠 노출 추정을 통해 질환 연관성 통계를 검토
</details>

<details>
<summary>3) [R&D 과제] 경찰관 맞춤형 건강관리 지능형 플랫폼</summary>

- **프로젝트 이름**: [R&D 과제] 경찰관 맞춤형 건강관리 서비스를 위한 지능형 빅데이터 통합플랫폼 개발
- **활동기간**: 2024.01 ~ 2024.12
- **역할**: 참여연구자
- **활용 기술 stack**: R, R Shiny, Tableau, 키워드 매칭, 직무코드 표준화
- **활동 내용**: 건강의료·암등록·심사평가원·인사 데이터를 통합해 직무-노출 매트릭스 개발을 지원하고 87개 기능코드 표준화 체계를 정리
</details>

<details>
<summary>4) [용역과제] 발암물질 노출수준 변화 평가(11)</summary>

- **프로젝트 이름**: [용역과제] 시간에 따른 발암물질 노출수준 변화 평가(11)
- **활동기간**: 2024.05 ~ 2024.10
- **역할**: 연구보조원
- **활용 기술 stack**: R, Python, Joinpoint Regression, Spline 기반 추세 분석
- **활동 내용**: 2002~2023 작업환경 측정자료를 바탕으로 1급 발암물질 4종의 연도별 노출 추세를 모델링하고 추세 변화 패턴을 정량화
</details>

---

## 🛠️ Tech Stack (Polished)

### Core
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-1F2937?style=for-the-badge&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### AI / Data
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-1E90FF?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-0EA5E9?style=for-the-badge)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge)

### Backend / Data Service
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![uWSGI](https://img.shields.io/badge/uWSGI-2F4F4F?style=for-the-badge)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge)

### Operations
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📫 Contact

- Velog: [https://velog.io/@juoon10](https://velog.io/@juoon10)
- Email: [juoon10@naver.com](mailto:juoon10@naver.com)
- GitHub: [github.com/cudaboy](https://github.com/cudaboy)

> “데이터의 품질, 해석 가능성, 운영 안정성을 동시에 만족시키는 데이터/AI 엔지니어링”
